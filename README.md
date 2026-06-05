# Like Quality - Site Web Vitrine

Site web vitrine moderne et complet pour l'entreprise Like Quality, spécialisée dans les systèmes de management de la Qualité, de la Sécurité et de l'Environnement (QSE). Mis en ligne à l'adresse https://francefath.com

## 🚀 Caractéristiques

### Structure du site
- **8 pages complètes** : Accueil, Conseil et Accompagnement, Audit, Formation Professionnelle, À propos, Contact, Mentions Légales, Politique de Confidentialité
- **Navigation responsive** avec menu mobile
- **Recherche intégrée** avec modal de recherche
- **Formulaire de contact** fonctionnel avec validation

### Design moderne
- **Charte graphique professionnelle** basée sur les couleurs du logo
- **Typographie moderne** avec Montserrat et Open Sans (Google Fonts)
- **Design responsive** adapté à tous les écrans (mobile, tablette, desktop)
- **Animations fluides** au défilement et interactions
- **Effets visuels** : hover effects, transitions, ombres

### Fonctionnalités
- **Animations au scroll** avec Intersection Observer
- **Menu mobile hamburger** pour les petits écrans
- **Bouton retour en haut** de page
- **Navigation active** selon la page courante
- **Préchargement des images** critiques
- **Transitions de page** fluides
- **Formulaire de contact** avec validation JavaScript

### SEO optimisé
- **Balises meta** complètes (description, keywords, author)
- **Open Graph tags** pour les réseaux sociaux
- **Structure sémantique** HTML5
- **Attributs alt** sur toutes les images
- **URLs propres** et descriptives

### Accessibilité
- **Navigation clavier** fonctionnelle
- **Attributs ARIA** sur les éléments interactifs
- **Contraste des couleurs** respecté
- **Liens skip-to-content** pour les lecteurs d'écran

## 📁 Structure du projet

```
site_like_quality/
├── index.html                          # Page d'accueil
├── conseil-accompagnement.html         # Page Conseil et Accompagnement
├── audit.html                          # Page Audit
├── formation-professionnelle.html      # Page Formation Professionnelle
├── a-propos.html                       # Page À propos
├── contact.html                        # Page Contact
├── mentions-legales.html               # Page Mentions Légales
├── politique-confidentialite.html       # Page Politique de Confidentialité
├── css/
│   └── styles.css                      # Feuille de style principale
├── js/
│   └── main.js                         # JavaScript principal
├── images/                             # Dossier des images
│   ├── logo_like_quality.jpg
│   ├── conseil_accompagnement.jpg
│   ├── audit.jpg
│   ├── formation_professionnelle.jpg
│   ├── valeurs.jpg
│   ├── qualite.jpg
│   ├── sante_securite.jpg
│   ├── environnement.jpg
│   ├── responsabillite_societale.jpg
│   ├── logo_sgs.png
│   ├── logo_althea.png
│   ├── logo_arinite.webp
│   └── logo_sofis.jpg
├── cahier_des_charges.txt              # Cahier des charges original
└── README.md                           # Ce fichier
```

## 🎨 Charte graphique

### Couleurs
- **Primaire** : #1e3a5f (bleu foncé)
- **Primaire clair** : #2d5a8a (bleu moyen)
- **Secondaire** : #4a90e2 (bleu clair)
- **Accent** : #f39c12 (orange)
- **Texte** : #333 (gris foncé)
- **Texte clair** : #666 (gris moyen)
- **Fond clair** : #f8f9fa (gris très clair)

### Typographie
- **Titres** : Montserrat (300-800)
- **Texte** : Open Sans (300-700)

## 🌐 Déploiement

### Option 1: Serveur local simple
Ouvrez simplement `index.html` dans votre navigateur.

### Option 2: Serveur HTTP (recommandé)
Pour éviter les problèmes avec les fichiers locaux, utilisez un serveur HTTP :

```bash
# Avec Python 3
python -m http.server 8000

# Avec Python 2
python -m SimpleHTTPServer 8000

# Avec Node.js (http-server)
npx http-server
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

### Option 3: Hébergement web
Déployez le contenu du dossier sur n'importe quel hébergeur web :
- Netlify
- Vercel
- GitHub Pages
- Hébergeur traditionnel (FTP)

## 📝 Contenu

Le site respecte scrupuleusement le cahier des charges fourni :
- Tous les textes exacts du cahier des charges
- Toutes les images spécifiées
- Structure complète de chaque page
- Navigation complète entre les pages

Des éléments supplémentaires ont été ajoutés pour améliorer l'expérience utilisateur :
- Animations au défilement
- Bouton retour en haut
- Effets hover sur les cartes
- Formulaire de contact avec validation
- Menu mobile responsive
- Modal de recherche
- Transitions fluides

## 🔧 Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `css/styles.css` :
```css
:root {
    --primary-color: #1e3a5f;
    --secondary-color: #4a90e2;
    --accent-color: #f39c12;
    /* ... */
}
```

### Modifier les textes
Les textes sont directement dans les fichiers HTML. Modifiez-les selon vos besoins.

### Ajouter de nouvelles pages
1. Créez un nouveau fichier HTML dans le dossier racine
2. Copiez la structure d'une page existante
3. Ajoutez le lien dans le menu de navigation (header et footer)
4. Mettez à jour le fichier `js/main.js` si nécessaire

## 📱 Responsive

Le site est entièrement responsive et s'adapte automatiquement à :
- **Mobile** (< 480px)
- **Tablette** (480px - 768px)
- **Desktop** (768px - 968px)
- **Large Desktop** (> 968px)

## 🔒 Sécurité

- Pas de dépendances externes critiques
- Pas de cookies de tracking
- Protection contre les injections XSS
- Validation côté client des formulaires

## 📧 Formulaire de contact

Le formulaire de contact est configuré pour :
- Valider les champs en JavaScript
- Vérifier le format de l'email
- Afficher un message de confirmation

**Note** : Pour rendre le formulaire fonctionnel, vous devez intégrer un backend ou un service de traitement de formulaires (Formspree, EmailJS, etc.).

## 🎯 Performance

- Images optimisées
- CSS minifié (production)
- JavaScript optimisé
- Préchargement des images critiques
- Lazy loading des images (via Intersection Observer)

## 📄 Licence

Ce site a été développé pour Like Quality. Tous droits réservés.

## 👤 Contact

Pour toute question ou modification, contactez France Fath : francefath@gmail.com

---

**Développé avec ❤️ pour Like Quality**
