# Vite Vanilla Project

This folder is intended for a Vite + Vanilla JavaScript project.

## Getting Started

1. If you haven't already, initialize a Vite project in this folder:
   ```sh
   npm create vite@latest vitevanila -- --template vanilla
   cd vitevanila
   npm install
   npm run dev
   ```
2. Open the local development server URL in your browser.


## Project Structure

- `index.html`: The main HTML file. Make sure it includes a `<canvas id="canvas"></canvas>` element for Three.js rendering.
- `main.js`: The JavaScript entry point. Sets up a Three.js scene with a dodecahedron, a box, lighting, OrbitControls, and a responsive animation loop.
- `style.css`: (Optional) Styles for your app.

## Notes

- The canvas element with `id="canvas"` is required in your HTML for rendering.
- OrbitControls are used for interactive camera movement. Ensure the import path matches your Three.js version/setup.
- The animation loop and window resize handler are included for smooth rendering and responsiveness.

## Learn More
- [Vite Documentation](https://vitejs.dev/)

## License
This project is for learning and demonstration purposes.
