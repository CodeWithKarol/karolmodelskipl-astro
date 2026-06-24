# Header Component Implementation Plan

**Goal:** Implement a minimalist, sticky header navigation component inspired by the "Bobbin" style.

**Architecture:** Create a reusable `Header.astro` component and integrate it into the `main.astro` layout.

**Tech Stack:** Astro, Tailwind CSS.

---

## Chunk 1: Create Header Component

- [ ] **Step 1: Create `src/components/Header.astro`**

```astro
---
---
<header class="sticky top-0 z-50 w-full bg-white/80 backdrop-blur-md border-b border-gray-100">
  <nav class="mx-auto flex h-16 max-w-7xl items-center justify-between px-6">
    <a href="/" class="text-xl font-bold tracking-tighter">BOBBIN</a>
    <div class="flex items-center gap-6">
      <a href="/work" class="text-sm font-medium hover:text-gray-600 transition-colors">Work</a>
      <a href="/about" class="text-sm font-medium hover:text-gray-600 transition-colors">About</a>
      <a href="/contact" class="rounded-full border border-black px-4 py-1.5 text-sm font-medium hover:bg-black hover:text-white transition-colors">Contact</a>
    </div>
  </nav>
</header>
```

- [ ] **Step 2: Update `src/layouts/main.astro` to include the header**

```astro
---
import "@/styles/global.css"
import Header from "@/components/Header.astro"
---

<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <link rel="icon" type="image/svg+xml" href="/favicon.svg" />
    <title>Astro App</title>
  </head>
  <body>
    <Header />
    <slot />
  </body>
</html>
```

- [ ] **Step 3: Commit**

```bash
git add src/components/Header.astro src/layouts/main.astro
git commit -m "feat: add sticky header component"
```
