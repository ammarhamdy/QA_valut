
# Node.js  is:
> A runtime environment that allows you to run **JavaScript outside of a browser**.

- **Node.js** = JavaScript engine + extra tools to run scripts on your computer

- **`npm`** = the package manager that installs libraries like Playwright or TypeScript

- Together, they let you build modern tools without opening a browser


# Why we need Node.js for Playwright
Playwright is written in **JavaScript/TypeScript**.  
To run it:
- We need **Node.js** to execute the code outside the browser.
- Node.js also manages **dependencies** (Playwright, TypeScript, etc.) via **`npm`** (Node Package Manager).


# `npx`
- Comes with Node.js
- It runs a package **without installing it globally**
- It will:
    - Use the local version in your project (if installed), or
    - Temporarily download and run it
Example:
```
npx playwright test
```
`playwright`
- Refers to Playwright
- A framework for **end-to-end (E2E) testing** of web apps
- Supports browsers like Chromium, Firefox, and WebKit
`test`
- This tells Playwright to:
    - Find all test files (usually in `tests/` or `*.spec.ts`)
    - Execute them
    - Show results in the terminal

