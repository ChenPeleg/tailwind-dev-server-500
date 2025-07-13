# Reproduction
npm create vite@latest my-project
Chosen react-ts template
npm install tailwindcss @tailwindcss/vite

added `@import "tailwindcss";` to "App.css"
added   `plugins: [react(),tailwindcss(),]` to `vite.config.ts`

added component `Component`
added `Component.module.css`

The additional semicolon is causing the error
