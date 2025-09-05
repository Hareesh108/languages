# Here’s the **Bun Hello World** in the same style as Node.js and Deno, with runtime context included

`````markdown
# Bun Hello World

````javascript
// hello-world.js
console.log("Hello, World!");
`````

---

## ▶️ How to Run

### 1. Run with Bun (✅ Recommended)

```bash
bun hello-world.js
```

Bun can run both **JavaScript** and **TypeScript** files directly.

---

### 2. Run with TypeScript

Unlike Node.js, Bun has **native TypeScript support** — no build step required:

```bash
bun hello-world.ts
```

---

### 3. Run in Watch Mode

Automatically re-run when your file changes:

```bash
bun --watch hello-world.js
```

---

## ℹ️ About Bun

* **Created by Jarred Sumner**, designed as a **modern fast runtime**.
* Written in **Zig** for performance.
* Drop-in replacement for **Node.js** in many cases.
* Includes a **JavaScript/TypeScript runtime, test runner, bundler, and package manager** in one tool.
* Focuses on **speed** — often faster startup and execution than Node.js or Deno.
* Compatible with much of the **npm ecosystem**.

---

## ✅ Recommendation

* Use **Bun** if you want a super fast runtime with built-in tooling.
* Use **Deno** if you want built-in security and a standard library.
* Use **Node.js** if you want maximum ecosystem stability and support.
