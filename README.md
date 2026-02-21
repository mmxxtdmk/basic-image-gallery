# FAETHFLEX Official NFT Gallery

**Minimal • Lightbox-only • Auto-detects every image**

A single-file, ultra-clean gallery built specifically for GitHub Pages.  
No thumbnails on the homepage — just a stunning full-screen lightbox experience.

### ✨ Features
- Automatically detects **any number** of images in the `/images/` folder  
- Images must be named: `nft-0001.png`, `nft-0002.png`, `nft-0003.png` …  
- Full-screen immersive lightbox with smooth navigation  
- One-click “COPY DIRECT ENDPOINT” (perfect for OpenSea metadata `external_url`)  
- Keyboard controls: ← → Esc  
- Pure HTML/CSS/JS — zero dependencies, zero build step  

### 🚀 How to Deploy (2 minutes)

1. Create a new repository on GitHub (example: `faethflex-nft`)
2. Clone it locally or use the web uploader
3. Add these files:
   - `index.html` (the lightbox-only gallery)
   - `README.md` (this file)
   - `LICENSE`
   - `.gitignore`
4. Create folder `images/` and upload your NFTs named `nft-0001.png`, `nft-0002.png`, etc.
5. Go to **Settings → Pages → Source → Deploy from main branch** → Save
6. Your gallery is live at:  
   `https://MMXXTDMK.github.io/faethflex-nft`

### ⚙️ Configuration

Open `index.html` and edit the `CONFIG` object near the bottom:

```js
const CONFIG = {
  githubUsername: "MMXXTDMK",      // ← YOUR GITHUB USERNAME
  repoName: "faethflex-nft",       // ← YOUR REPO NAME
  imageFolder: "images/",
  prefix: "nft-",
  padding: 4,
  extension: ".png"                // or ".jpg"
};
```

### Folder Structure

faethflex-nft/

├── index.html

├── README.md

├── LICENSE

├── .gitignore

└── images/

    ├── nft-0001.png

    ├── nft-0002.png

    └── ...

Made with ❤️ by @MMXXTDMK