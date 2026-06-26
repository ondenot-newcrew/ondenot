# Yann Christian ONDENOT - Site Web Professionnel

Un site web moderne et responsive présentant un profil professionnel avec sections de prestations, galerie photo et contact.

## 📋 Contenu du Site

- **Accueil** : Hero section avec appel à l'action
- **Profil** : Présentation personnelle et compétences
- **Prestations** : Grid de services (4 cartes personnalisables)
- **Galerie Photo** : Portfolio visuel (6 emplacements photos)
- **Contact** : Formulaire de contact + informations
- **Footer** : Navigation et informations supplémentaires

## 🎨 Caractéristiques

✅ Design responsive (mobile, tablet, desktop)
✅ Navigation sticky avec menu mobile
✅ Animations fluides et transitions
✅ Formulaire de contact avec validation
✅ Galerie photo interactive
✅ Optimisé pour l'accessibilité
✅ Couleurs professionnelles personnalisables
✅ Performance optimisée

## 📁 Structure du Projet

```
site web/
├── index.html                 # Page principale
├── assets/
│   ├── css/
│   │   ├── styles.css        # Styles principaux
│   │   └── responsive.css    # Design responsive
│   ├── js/
│   │   └── main.js           # Fonctionnalités JavaScript
│   ├── images/
│   │   └── profil.jpg        # Photo de profil (placeholder)
│   └── gallery/
│       ├── photo-1.jpg       # Photos galerie (placeholders)
│       ├── photo-2.jpg
│       ├── photo-3.jpg
│       ├── photo-4.jpg
│       ├── photo-5.jpg
│       └── photo-6.jpg
└── README.md                 # Cette documentation

```

## 🚀 Mise en Démarrage

1. Ouvrez le fichier `index.html` dans votre navigateur
2. Ou utilisez un serveur local :
   ```bash
   # Avec Python 3
   python -m http.server 8000
   
   # Avec Node.js (http-server)
   npx http-server
   ```

3. Accédez à `http://localhost:8000`

## 🎯 Personnalisation

### Modifier les Informations de Contact
Éditez le fichier `index.html` et trouvez la section Contact pour modifier :
- Email : `contact@ondenot.be`
- Téléphone : `+32 (0)X XXX XX XX`

### Ajouter Vos Photos
1. Placez vos images dans le dossier `assets/images/` (profil) ou `assets/gallery/` (galerie)
2. Mettez à jour les références `src` dans `index.html`

### Modifier les Prestations
Éditez les 4 cartes de prestations dans `index.html` avec vos services

### Personnaliser les Couleurs
Modifiez les variables CSS dans `assets/css/styles.css` :
```css
:root {
    --primary-color: #1a73e8;      /* Bleu principal */
    --secondary-color: #34a853;    /* Vert */
    --accent-color: #fbbc04;       /* Jaune accent */
    ...
}
```

## 🌐 Déploiement

### Option 1 : Hébergement Gratuit (GitHub Pages)
1. Créez un dépôt GitHub nommé `ondenot.be`
2. Poussez les fichiers
3. Activez GitHub Pages dans les paramètres
4. Configurez le nom de domaine personnalisé

### Option 2 : Hébergement Classique
1. Connectez-vous à votre fournisseur d'hébergement
2. Téléchargez les fichiers via FTP
3. Pointez votre domaine vers le serveur

### Option 3 : Netlify / Vercel
1. Connectez votre dépôt GitHub
2. Déploiement automatique en quelques clics

## 📱 Responsivité

Le site s'adapte automatiquement à tous les appareils :
- **Desktop** : Affichage complet 1200px+
- **Tablet** : Layout optimisé 768px-1023px
- **Mobile** : Interface tactile 320px-767px

## ⌨️ Raccourcis Clavier

- **S** : Aller aux prestations
- **C** : Aller à la section contact

## 📊 Fonctionnalités JavaScript

- Menu mobile responsive
- Validation de formulaire
- Animations au scroll
- Lightbox galerie (optionnelle)
- Smooth scrolling
- Navigation active au scroll

## 🔧 Améliorations Possibles

- [ ] Intégrer backend pour formulaire email
- [ ] Blog ou actualités
- [ ] Système de réservation/commande
- [ ] Intégration réseaux sociaux
- [ ] SEO optimisé
- [ ] Support multi-langues
- [ ] Dark mode
- [ ] Animations avancées

## 📞 Support et Contact

Pour personnaliser davantage le site ou ajouter des fonctionnalités :
- Modifiez directement les fichiers HTML/CSS/JS
- Consultez les commentaires dans le code
- Testez dans différents navigateurs

## 📄 Licence

Ce projet est libre d'utilisation. Adaptez-le selon vos besoins.

---

**Version** : 1.0
**Dernière mise à jour** : Juin 2026
