# tailwindcss-notes

**#TailwindCSS Installtion Guide**
- npm install tailwindcss
- npx tailwindcss init
- add this script below to src/styles.css:
  ```
    @tailwind base;
    @tailwind components;
    @tailwind utilities;
  ```
- add script build css at package.json:
    "build:css": "npx tailwindcss-cli build -i src/styles.css -o public/styles.css"
- run script build:css
- start code!
