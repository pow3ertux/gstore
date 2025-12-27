# Sheherazade - Site Web Statique

Un site web statique élégant et moderne inspiré par les contes des Mille et Une Nuits.

## 🌟 Caractéristiques

- **Design moderne et responsive** - S'adapte à tous les écrans (mobile, tablette, desktop)
- **Navigation fluide** - Menu de navigation avec défilement doux
- **Animations élégantes** - Effets de transition et animations au scroll
- **Formulaire de contact** - Avec validation et message de confirmation
- **Galerie d'images** - Grille responsive pour présenter vos réalisations
- **Performance optimale** - Code léger et optimisé

## 📁 Structure du Projet

```
sheherazade/
├── index.html      # Page principale
├── styles.css      # Styles et design
├── script.js       # Interactivité et animations
└── README.md       # Documentation
```

## 🚀 Installation et Utilisation

### Option 1 : Ouvrir directement dans le navigateur

1. Naviguez vers le dossier `sheherazade`
2. Double-cliquez sur `index.html`
3. Le site s'ouvrira dans votre navigateur par défaut

### Option 2 : Utiliser un serveur local

Pour un développement optimal, utilisez un serveur local :

```bash
# Avec Python 3
cd sheherazade
python3 -m http.server 8000

# Avec Node.js (npx)
npx serve

# Avec PHP
php -S localhost:8000
```

Puis ouvrez votre navigateur à l'adresse : `http://localhost:8000`

## 🎨 Personnalisation

### Couleurs

Modifiez les variables CSS dans `styles.css` :

```css
:root {
    --primary-color: #8b4789;      /* Couleur principale (violet) */
    --secondary-color: #d4af37;    /* Couleur secondaire (or) */
    --dark-color: #1a1a2e;         /* Couleur sombre */
    --light-color: #f8f9fa;        /* Couleur claire */
}
```

### Contenu

- **Textes** : Modifiez directement dans `index.html`
- **Images** : Remplacez les placeholders SVG par vos propres images
- **Informations de contact** : Mettez à jour la section contact avec vos coordonnées

### Polices

Le site utilise :
- **Playfair Display** pour les titres (élégant, serif)
- **Inter** pour le texte (moderne, sans-serif)

## 📱 Sections du Site

1. **Accueil** - Hero section avec titre et call-to-action
2. **À Propos** - Présentation de votre activité
3. **Services** - Trois cartes de services avec icônes
4. **Galerie** - Grille de 6 images
5. **Contact** - Formulaire et informations de contact
6. **Footer** - Liens et réseaux sociaux

## 🛠️ Technologies Utilisées

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript Vanilla (ES6+)
- Google Fonts

## 📝 Fonctionnalités JavaScript

- Menu mobile responsive avec animation hamburger
- Défilement fluide vers les sections
- Animations au scroll (Intersection Observer)
- Changement de style de la navbar au scroll
- Validation et soumission du formulaire de contact
- Messages de confirmation animés

## 🎯 Compatibilité

- ✅ Chrome, Firefox, Safari, Edge (versions récentes)
- ✅ Responsive : Mobile, Tablette, Desktop
- ✅ Pas de dépendances externes (sauf Google Fonts)

## 📦 Déploiement

### GitHub Pages

1. Créez un repository GitHub
2. Poussez les fichiers
3. Activez GitHub Pages dans les paramètres
4. Votre site sera accessible à `https://username.github.io/sheherazade`

### Netlify

1. Glissez-déposez le dossier sur [Netlify Drop](https://app.netlify.com/drop)
2. Votre site est en ligne instantanément !

### Autres options

- Vercel
- Cloudflare Pages
- Firebase Hosting

## 🔧 Améliorations Possibles

- Ajouter de vraies images dans la galerie
- Intégrer un backend pour le formulaire de contact
- Ajouter un système de blog
- Implémenter un mode sombre
- Ajouter des animations plus complexes
- Intégrer Google Analytics

## 📄 Licence

Ce projet est libre d'utilisation pour vos projets personnels et commerciaux.

## 👤 Contact

Pour toute question ou suggestion, n'hésitez pas à nous contacter via le formulaire sur le site.

---

**Fait avec ❤️ pour Sheherazade**
