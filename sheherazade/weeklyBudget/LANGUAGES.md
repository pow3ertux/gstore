# Guide de traduction multilingue - MyWeeklyBudget

## 🌍 Langues supportées

L'application MyWeeklyBudget supporte 9 langues :

1. 🇫🇷 **Français** (fr) - ✅ Complété
2. 🇬🇧 **English** (en) - ✅ Complété
3. 🇪🇸 **Español** (es) - ⏳ À faire
4. 🇩🇪 **Deutsch** (de) - ⏳ À faire
5. 🇮🇹 **Italiano** (it) - ⏳ À faire
6. 🇵🇹 **Português** (pt) - ⏳ À faire
7. 🇳🇱 **Nederlands** (nl) - ⏳ À faire
8. 🇯🇵 **日本語** (ja) - ⏳ À faire
9. 🇸🇦 **العربية** (ar) - ⏳ À faire

## 📁 Structure des fichiers

```
weeklyBudget/
├── index.html              # Français (défaut)
├── privacy-policy.html     # Français
├── terms-of-service.html   # Français
├── en/
│   ├── index.html
│   ├── privacy-policy.html
│   └── terms-of-service.html
├── es/
│   ├── index.html
│   ├── privacy-policy.html
│   └── terms-of-service.html
├── de/
│   ├── index.html
│   ├── privacy-policy.html
│   └── terms-of-service.html
└── ... (autres langues)
```

## 🔧 Comment ajouter une nouvelle langue

### Étape 1 : Créer le dossier
```bash
mkdir -p weeklyBudget/[code-langue]
```

### Étape 2 : Copier les fichiers anglais
```bash
cp weeklyBudget/en/*.html weeklyBudget/[code-langue]/
```

### Étape 3 : Traduire le contenu

Ouvrez chaque fichier HTML et traduisez :

#### Dans `index.html` :
- `<html lang="en">` → `<html lang="[code]">`
- Titre : "Weekly Budget Management"
- Hero section
- Fonctionnalités (6 cartes)
- Section "How does it work"
- Bouton de téléchargement
- Footer

#### Dans `privacy-policy.html` :
- Toutes les sections de la politique de confidentialité
- Titres et sous-titres
- Listes à puces
- Informations de contact

#### Dans `terms-of-service.html` :
- Toutes les sections des conditions d'utilisation
- Clauses légales
- Informations techniques

### Étape 4 : Mettre à jour les liens

Dans chaque fichier, vérifiez que les liens pointent correctement :
- `href="../logo.png"` (logo)
- `href="../styles.css"` (CSS)
- `href="../script.js"` (JavaScript)
- `href="../../index.html"` (retour Sheherazade)

### Étape 5 : Mettre à jour le sélecteur de langue

Dans le `<select>`, assurez-vous que l'option de la langue actuelle est sélectionnée :
```html
<option value="index.html" selected>🇪🇸 Español</option>
```

## 📝 Éléments à traduire

### Textes communs à toutes les pages

**Navigation :**
- Home / Accueil
- Privacy / Confidentialité
- Terms / Conditions

**Footer :**
- "Weekly budget management app - Finance Category - 13+"
- Application, Legal, Follow us
- Features, Download, Support, FAQ
- Privacy Policy, Terms of Service, Legal Notice
- "All rights reserved"

### Page d'accueil (index.html)

**Hero :**
- "Weekly Management"
- "Master your budget, week after week"
- Description complète
- "Download the app"
- "Learn more"

**Fonctionnalités (6 cartes) :**
1. Weekly Budget Management
2. Real-Time Expense Tracking
3. Group Budget Sharing
4. Offline & Synced Mode
5. Secure Authentication
6. Multilingual Support

**Comment ça marche (3 étapes) :**
1. Set your budget
2. Add your expenses
3. Track your progress

**Téléchargement :**
- "Ready to take control of your budget?"
- "Download MyWeeklyBudget for free..."

### Politique de confidentialité (privacy-policy.html)

**Sections principales :**
1. Introduction
2. Informations que nous collectons
3. Comment nous utilisons vos informations
4. Partage de vos informations
5. Sécurité de vos données
6. Conservation des données
7. Vos droits
8. Cookies et technologies similaires
9. Services tiers
10. Protection des mineurs
11. Transferts internationaux
12. Modifications de cette politique
13. Contact
14. Informations techniques de l'application
15. Consentement

### Conditions d'utilisation (terms-of-service.html)

**Sections principales :**
1. Acceptation des conditions
2. Description du service
3. Éligibilité et compte utilisateur
4. Utilisation acceptable
5. Propriété intellectuelle
6. Gratuité de l'application
7. Confidentialité et données
8. Avertissements et limitations
9. Limitation de responsabilité
10. Indemnisation
11. Résiliation
12. Modifications de l'application
13. Liens tiers
14. Loi applicable et juridiction
15. Résolution des litiges
16. Dispositions générales
17. Contact
18. Informations techniques
19. Acceptation

## 🎨 Considérations spéciales

### Pour l'arabe (ar)
- Ajouter `dir="rtl"` à la balise `<html>`
- Inverser l'ordre des éléments de navigation si nécessaire
- Adapter les marges et paddings pour la lecture RTL

### Pour le japonais (ja)
- Vérifier que la police Inter supporte bien les caractères japonais
- Ajuster la hauteur de ligne si nécessaire

### Pour toutes les langues
- Garder le nom "MyWeeklyBudget" et "Sheherazade" non traduits
- Garder l'email jerome@bechu.org
- Garder les informations techniques (Package ID, Version, etc.)
- Les emojis peuvent rester identiques

## ✅ Checklist de traduction

Pour chaque langue :
- [ ] Créer le dossier de langue
- [ ] Copier les 3 fichiers HTML
- [ ] Traduire index.html
- [ ] Traduire privacy-policy.html
- [ ] Traduire terms-of-service.html
- [ ] Vérifier tous les liens
- [ ] Tester la navigation entre les pages
- [ ] Vérifier le sélecteur de langue
- [ ] Tester sur mobile et desktop

## 🚀 Déploiement

Une fois les traductions complétées, déployez tous les fichiers :
```
weeklyBudget/
├── index.html (fr)
├── privacy-policy.html (fr)
├── terms-of-service.html (fr)
├── styles.css
├── script.js
├── logo.png
├── en/
├── es/
├── de/
├── it/
├── pt/
├── nl/
├── ja/
└── ar/
```

## 📧 Contact

Pour toute question sur les traductions : jerome@bechu.org
