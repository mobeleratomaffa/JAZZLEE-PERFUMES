# Jazzlee Perfumes

A dependency-free static website for Jazzlee Perfumes. The site is configured for Render Static Sites through `render.yaml`.

## Preview locally

Open `public/index.html` in a browser, or serve the `public` directory with Python:

```powershell
python -m http.server 8000 --directory public
```

Then visit `http://localhost:8000`.

## Deploy to Render

In Render, create a new Blueprint and connect this GitHub repository. Render will read `render.yaml`, publish the `public` directory as a static site, and redeploy when changes are pushed to `main`.