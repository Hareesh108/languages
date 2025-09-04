# TypeScript Hello World

````markdown
# Hello World in TypeScript

This is a simple TypeScript program that prints **Hello, World!** to the console.

````

---

## ▶️ How to Run

There are a few ways to run this program:

### 1. Run (✅ Recommended)

`node version 23 and above` allows you to run TypeScript directly without compiling manually.

```bash
node hello-world.ts
```

### 1. Run with ts-node

`ts-node` allows you to run TypeScript directly without compiling manually.

```bash
ts-node hello-world.ts
```

This is the most common and recommended way if you are practicing TypeScript as a programming language.

---

### 2. Compile to JavaScript and Run with Node.js

First compile:

```bash
npx tsc hello-world.ts
```

This generates `hello-world.js`. Now run:

```bash
node hello-world.js
```

---

### 3. Run Inside an HTML File (via compiled JS)

You need to include the compiled JavaScript file:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Hello World</title>
  </head>
  <body>
    <script src="hello-world.js"></script>
  </body>
</html>
```

Open this file in a browser, and check the browser’s console (F12 → Console).

---

## ✅ Recommendation

* Use **ts-node** if you want to run TypeScript quickly.  
* Use **tsc + Node.js** if you want to see how TypeScript compiles into JavaScript.  
* Use **Browser (with compiled JS)** if you are focusing on web development basics.
