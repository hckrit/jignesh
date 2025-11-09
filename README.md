# Jignesh Malviya — Modern 2025 Portfolio

This is a modern, responsive static portfolio for *Jignesh Malviya* (3D Designer).  
Built with Tailwind CSS (CDN), AOS for scroll animations, and **model-viewer** for live 3D model previews.

## How to use
1. Replace `assets/sample.glb` with your actual GLB/GLTF model (rename accordingly).
2. Replace placeholder images in `assets/`.
3. Update email & social links in `index.html`.
4. Push to GitHub and enable GitHub Pages (Serve from `main` branch root).

## Quick deploy (CLI)
```bash
git init
git add .
git commit -m "Modern 2025 portfolio"
gh repo create jignesh-malviya-3d-portfolio --public --source=. --remote=origin -y
git push -u origin main
gh pages enable --branch main --path /
```

