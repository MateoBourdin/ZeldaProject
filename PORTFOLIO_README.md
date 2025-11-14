# 🎮 Portfolio Zelda II Project

## 📄 Description

Ce repository contient une page portfolio professionnelle pour présenter le projet **Zelda II: The Adventure of Link**, un jeu RPG en terminal développé en Python.

## 🌐 Visualiser le Portfolio

### Option 1 : Ouvrir localement
1. Clonez le repository
2. Ouvrez le fichier `portfolio.html` dans votre navigateur web

### Option 2 : GitHub Pages (Recommandé)
Pour héberger gratuitement votre portfolio sur GitHub Pages :

1. Allez dans **Settings** de votre repository
2. Descendez jusqu'à la section **Pages**
3. Dans **Source**, sélectionnez la branche `main` (ou `master`)
4. Cliquez sur **Save**
5. Votre portfolio sera accessible à : `https://mateobourdin.github.io/ZeldaProject/portfolio.html`

### Option 3 : Renommer pour l'index
Si vous voulez que la page s'affiche directement sur `https://mateobourdin.github.io/ZeldaProject/` :
```bash
mv portfolio.html index.html
```

## 📁 Structure du Projet

```
ZeldaProject/
├── portfolio.html              # Page portfolio (ce fichier!)
├── PORTFOLIO_README.md         # Documentation du portfolio
├── Projet IPI 2024/           # Code source du jeu
│   ├── main.py                # Point d'entrée
│   ├── Player.py              # Système de joueur
│   ├── Monster.py             # Système de monstres
│   ├── PNJ.py                 # NPCs
│   ├── Background.py          # Gestion des cartes
│   └── *.txt                  # Fichiers de cartes
└── README.md                  # README principal
```

## ✨ Fonctionnalités du Portfolio

- ✅ Design moderne et responsive
- ✅ Prévisualisation ASCII du jeu
- ✅ Extraits de code colorés
- ✅ Lien direct vers GitHub
- ✅ Documentation complète des features
- ✅ Instructions d'installation
- ✅ Architecture technique détaillée
- ✅ Animations et effets visuels

## 🎨 Personnalisation

### Modifier les couleurs
Les couleurs principales sont définies dans les gradients CSS :
- Violet principal : `#667eea`
- Violet secondaire : `#764ba2`

### Ajouter des sections
Ajoutez une nouvelle section avec cette structure :
```html
<div class="section">
    <h3>Titre de la section</h3>
    <p>Contenu...</p>
</div>
```

### Modifier le lien GitHub
Cherchez et remplacez toutes les occurrences de :
```
https://github.com/MateoBourdin/ZeldaProject
```

## 📱 Compatibilité

Le portfolio est optimisé pour :
- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Tablette
- ✅ Mobile
- ✅ Tous les navigateurs modernes

## 🚀 Déploiement Rapide

### Netlify
1. Connectez-vous sur [Netlify](https://www.netlify.com/)
2. Glissez-déposez le fichier `portfolio.html`
3. Votre site est en ligne !

### Vercel
```bash
npm i -g vercel
vercel --prod
```

## 💡 Conseils

1. **Captures d'écran** : Pour améliorer le portfolio, vous pouvez ajouter de vraies captures d'écran du jeu en remplaçant les prévisualisations ASCII par des images
2. **Vidéo** : Ajoutez une démo vidéo du jeu en action
3. **Analytics** : Intégrez Google Analytics pour suivre les visiteurs
4. **SEO** : Ajoutez des meta tags pour améliorer le référencement

## 📧 Contact

Pour toute question concernant ce portfolio ou le projet Zelda :
- GitHub : [MateoBourdin](https://github.com/MateoBourdin)

---

**Créé avec ❤️ pour présenter un projet de passion**
