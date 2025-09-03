
<!-- ========================= -->
<!-- FILE: README.md           -->
<!-- ========================= -->
# Porte_folio_CV — Patrick Munier

Base moderne, modulaire et **entièrement commentée** pour un site CV multipage (RH only).

## 📦 Arborescence
```
.
├── index.html
├── parcours.html
├── recommandations.html
├── contact.html
├── assets/
│   ├── css/
│   │   ├── tokens.css
│   │   ├── base.css
│   │   ├── layout.css
│   │   └── components.css
│   ├── js/
│   │   └── main.js
│   └── img/
├── .editorconfig
├── .gitignore
└── CONTRIBUTING.md
```

## 🚀 Démarrer
1. Ouvrir le dossier avec VS Code.
2. Lancer un serveur local (ex. Live Server) et ouvrir `index.html`.
3. Modifier la palette dans `assets/css/tokens.css`.
4. Ajouter les images dans `assets/img/` (portrait, logos).

## 🧱 Piliers
- **Séparation stricte** HTML / CSS / JS.
- **Accessibilité** par défaut (skip link, aria, `prefers-reduced-motion`).
- **Commentaires** systématiques par section.
- **Nommage clair** (BEM light : `.block`, `.block__element`, `.block--modifier`).

## 🔧 Déploiement
- GitHub Pages (si besoin public) ou hébergement interne RH.
