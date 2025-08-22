MODMIX MkDocs Assets
====================
Files in this folder are sized for MkDocs Material.

- logo.png (256x256) — use in mkdocs.yml as theme.logo: assets/logo.png
- favicon.png (64x64) — use in mkdocs.yml as theme.favicon: assets/favicon.png
- banner-hero-1600x300.(jpg|webp) — wide hero for index.md
- promo-1200.(jpg|webp) — general promo image for guides or pages

Recommended project structure:
docs/
  assets/
    logo.png
    favicon.png
    banner-hero-1600x300.jpg
    promo-1200.jpg
    extra.css

Example in index.md:
![MODMIX Banner](assets/banner-hero-1600x300.jpg){ loading=lazy align=center }

