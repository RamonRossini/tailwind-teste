Angular CLI: 13.2.6
Node: 16.15.1
Package Manager: npm 8.11.0
OS: win32 x64

Instalação do tailwindcss no Angular:
1. npm install -D tailwindcss postcss autoprefixer
2. npx tailwindcss init
3. no arquivo tailwind.config.js, adicionar content: ["./src/**/*.{html,ts}"]
4. no arquivo styles.scss, adicionar as diretivas @tailwind base; @tailwind components; @tailwind utilities;