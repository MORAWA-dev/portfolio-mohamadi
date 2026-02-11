# Portfolio — KABORE Mohamadi

Site web portfolio minimaliste pour **KABORE Mohamadi** — Opérateur d'engin / Magasinier.

## Déploiement sur GitHub Pages

1. **Créer un dépôt GitHub** :
   - Va sur [github.com/new](https://github.com/new)
   - Nomme le dépôt (ex : `portfolio` ou `kabore-mohamadi`)
   - Laisse-le en **Public**

2. **Pousser les fichiers** :
   ```bash
   cd /Users/albarka/Downloads/bro
   git init
   git add .
   git commit -m "Portfolio initial"
   git branch -M main
   git remote add origin https://github.com/TON_USERNAME/TON_REPO.git
   git push -u origin main
   ```

3. **Activer GitHub Pages** :
   - Va dans **Settings** → **Pages**
   - Source : **Deploy from a branch**
   - Branche : **main** / dossier **/ (root)**
   - Clique **Save**

4. **Le site sera disponible à** :
   ```
   https://TON_USERNAME.github.io/TON_REPO/
   ```

## Structure
```
├── index.html          ← Page principale
├── style.css           ← Styles
├── photos/             ← Photos de profil
├── *.pdf               ← CV et lettres de motivation
└── README.md           ← Ce fichier
```
