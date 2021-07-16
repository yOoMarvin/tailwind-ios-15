# iOS 15 Rebuild with tailwindcss

This repository only serves educational purpose and ist based on a video by [Tailwind Labs](https://www.youtube.com/watch?v=eSzNNYk7nVU).

## Steps for the development environment

1. Create a new folder with `mkdir`
2. Create a simple `package.json` file with `npm init -y`
3. Install the needed packages with `npm i tailwindcss postcss autoprefixer vite`. In this case, [vite](https://github.com/vitejs/vite/tree/main/#readme) is the server.
4. Configure tailwind with `npx tailwind init -p`
5. create a `css` folder, import tailwind and link the stylesheet in `index.html`
6. Change the npm dev script to "vite". Run the server with `npm run dev`. Vite is looking for the `index.html` file
