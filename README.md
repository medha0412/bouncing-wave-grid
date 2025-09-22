## ⚡ Neural Wave Matrix

An eye‑catching, animated grid visual built with React where a colorful “neural wave” sweeps across a dynamic matrix. Tune rows, columns, and speed on the fly with sleek neon‑styled controls.

- **Live demo**: [bouncing-grid-game.netlify.app](https://bouncing-grid-game.netlify.app)

### ✨ Highlights
- **Dynamic wave animation** with smooth direction changes and vivid HSL color cycling
- **Interactive controls**: adjust `ROWS`, `COLS`, and `SPEED` without page reloads
- **Responsive layout** that scales from mobile to desktop
- **Polished UI** with neon gradients, scanline effects, and soft glows

### 🎮 Controls
- **ROWS**: 8–25
- **COLS**: 8–20
- **SPEED**: Higher value = faster animation
- **Pause / Reset**: Toggle playback and reset the wave position/phase

### 🧱 Tech Stack
- React 18 (Create React App)
- CSS (custom neon theme)

### 🚀 Getting Started
```bash
git clone <your-repo-url>
cd "wave assignment/wave assignment/assignment2"
npm install
npm start
```
Open `http://localhost:3000` in your browser.

### 🏗️ Build
```bash
npm run build
```
Outputs an optimized production build to the `build` folder.

### ☁️ Deployment

Netlify (recommended)
- Build command: `npm run build`
- Publish directory: `build`

Vercel
- Framework preset: Create React App
- Build command: `npm run build`
- Output directory: `build`

GitHub Pages
1) `npm i -D gh-pages`
2) Add to `package.json`:
   - `"homepage": "https://<user>.github.io/<repo>"`
   - scripts: `predeploy` → `npm run build`, `deploy` → `gh-pages -d build`
3) `npm run deploy`

### 👩‍💻 Project Structure
```
assignment2/
  public/
  src/
    App.js
    App.css
    index.js
    index.css
  package.json
```

### 🧭 Notes
- The `SPEED` slider maps higher values to a smaller interval internally to ensure “right = faster”.
- Global styles avoid horizontal overflow and maintain a full‑bleed background.

### 📜 License
MIT — feel free to use and adapt.


