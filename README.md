# Snark factory — Pixel-perfect integration (refined)
 Ce dépôt contient l’intégration HTML/CSS fidèle à la maquette Figma (header arrondi, hero avec Union.svg, carte “newsletter” chevauchant le footer, footer en grille, etc.).


 ## Structure 

 ```
├─ assets/
│  ├─ icon/                 # icônes SVG (facebook.svg, twitter.svg, LangChange.svg, Union.svg, flag-*.svg…)
│  ├─ img/                  # images (Snark_logo_noir.png, Snark_logo_blanc.png, Image.png, Salade.png…)
├─ styles/
│  ├─ globals.css           # reset léger + variables globales (peut contenir les tokens)
│  └─ style.css             # styles de page (topbar, hero, newsletter, footer…)
├─ index.html               # page unique
└─ README.md
```

## Exports Figma à placer dans assets/

- Logo : assets/img/Snark_logo_noir.png, assets/img/Snark_logo_blanc.png
- Héros : assets/img/Image.png (16:9), décor Union : assets/icon/Union.svg
- Badge/illustrations : assets/img/Salade.png
- Icônes sociaux : assets/icon/facebook.svg, twitter.svg, instagram.svg, linkedin.svg
- Langue : assets/icon/flag-uk.svg (et variantes), assets/icon/LangChange.svg 
