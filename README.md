# Reproduction
To reproduece the issue, follow these steps:
1. run `npm create vite@latest my-project`
2. Chosen react-ts template
3. run `npm install tailwindcss @tailwindcss/vite`
4. added `@import "tailwindcss";` to "App.css"
5. added   `plugins: [react(),tailwindcss(),]` to `vite.config.ts`
7. added component `Component.tsx` file
8. added `Component.module.css` file 
9. run `npm run dev`

The additional semicolon is causing the error


# To install

You can clone the repo and do `npm install` (node 24.x.x)
