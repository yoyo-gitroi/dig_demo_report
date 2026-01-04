# dig_demo_report

Static report site for competitor analysis with a built-in video asset.

## Project layout
- `index.html`: Primary report page served at the site root.
- `Dramatic Ink Diffusion Visual - Competitor Analysis.mp4`: Video referenced by the report.

## Deploying to Vercel
1. From Vercel, create a new project and import this repository.
2. Choose the **Other** framework preset so Vercel treats the project as a static site.
3. Leave the build command empty and set the output directory to the repository root (`.`) so `index.html` is served directly.
4. Deploy. Vercel will host `index.html` at the root and serve the MP4 asset alongside it.
