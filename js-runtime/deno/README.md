# Here’s an example **Hello World in Deno** with some **runtime context**

`````markdown
# Deno Hello World

````typescript
// hello-world.ts
console.log("Hello, World!");
`````

---

## ▶️ How to Run

### 1. Run with Deno (✅ Recommended)

```bash
deno run hello-world.ts
```

Deno runs **TypeScript and JavaScript out of the box**, no build step required.

---

### 2. Run with Permissions

Deno is **secure by default**.
If your program needs file, network, or environment access, you must explicitly allow it:

```bash
deno run --allow-net hello-world.ts
```

---

### 3. Run in Watch Mode

Automatically re-run when your file changes:

```bash
deno run --watch hello-world.ts
```

---

## ℹ️ About Deno

* **Created by Ryan Dahl** (the original creator of Node.js).
* Designed as a **modern runtime** for JavaScript and TypeScript.
* **Secure by default** (no file, network, or env access without flags).
* **TypeScript support is built-in** — no `tsc` or `ts-node` needed.
* Ships with a **standard library** (no need for npm for many utilities).
* Has first-class support for **Web APIs** like `fetch`, `WebSocket`, `URL`, etc.

---

## ✅ Recommendation

* Use **Deno** if you want a secure, modern runtime with built-in TypeScript.
* Use **Node.js** if you want maximum ecosystem compatibility.
* Use **Bun** if you want speed and modern tooling.
