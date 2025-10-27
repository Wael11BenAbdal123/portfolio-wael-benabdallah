# Portfolio de Wael Ben Abdallah

Portfolio personnel moderne et responsive pour Wael Ben Abdallah, développeur Business Intelligence et Full-Stack basé à Sfax, Tunisie.

## 📋 Structure du Site

Le portfolio est divisé en 4 pages principales :

### 1. **Accueil** (`index.html`)
- Message de bienvenue et présentation
- Aperçu des compétences principales
- Appels à l'action vers les projets et contact

### 2. **À propos** (`about.html`)
- Biographie détaillée
- Formation académique (ISAAS Sfax)
- Compétences techniques organisées par catégorie
- Centres d'intérêt professionnels

### 3. **Projets** (`projects.html`)
- Info.Shop (Site e-commerce HTML/CSS)
- Système de Gestion Scolaire (C# .NET + SQL Server)
- Tableau de Bord Power BI (Analyse de ventes)
- Vue d'ensemble des technologies utilisées

### 4. **Contact** (`contact.html`)
- Formulaire de contact avec validation
- Informations de contact (email, téléphone, localisation)
- Liens vers réseaux sociaux (LinkedIn, GitHub)
- Section FAQ

## 🎨 Caractéristiques

- **Design moderne** : Interface épurée avec thème clair et couleurs d'accentuation teal/cyan (#0891b2)
- **Responsive** : Optimisé pour tous les appareils (desktop, tablette, mobile)
- **Navigation fixe** : Header fixe avec menu hamburger pour mobile
- **Animations** : Transitions douces et animations au scroll
- **Icônes** : Font Awesome 6.4.0 pour une interface visuelle riche
- **Formulaire de contact** : Validation côté client et messages de feedback

## 🛠️ Technologies Utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles modernes avec variables CSS, Flexbox, Grid
- **JavaScript (Vanilla)** : Interactions et validations
- **Font Awesome** : Bibliothèque d'icônes

## 📁 Structure des Fichiers

```
Profolio/
├── index.html              # Page d'accueil
├── about.html              # Page À propos
├── projects.html           # Page Projets
├── contact.html            # Page Contact
├── README.md               # Documentation
└── assets/
    ├── css/
    │   └── styles.css      # Fichier CSS principal
    ├── js/
    │   └── script.js       # Fichier JavaScript
    └── images/
        └── CV Phoo.png     # Photo de profil
```

## 🚀 Installation et Utilisation

### Méthode 1 : Ouverture directe
1. Téléchargez tous les fichiers dans un même dossier
2. Double-cliquez sur `index.html` pour ouvrir dans votre navigateur

### Méthode 2 : Serveur local (recommandé)

**Avec Python :**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Avec Node.js (http-server) :**
```bash
npx http-server -p 8000
```

**Avec PHP :**
```bash
php -S localhost:8000
```

Puis accédez à : `http://localhost:8000`

## 🎯 Fonctionnalités

### Navigation
- Menu de navigation fixe avec indicateur de page active
- Menu hamburger responsive pour mobile
- Transitions douces entre les sections

### Formulaire de Contact
- Validation en temps réel
- Messages d'erreur et de succès
- Champs requis : Nom, Email, Sujet, Message

### Animations
- Apparition des éléments au scroll
- Effets hover sur les cartes et boutons
- Transitions fluides

## 📱 Responsive Design

Le site est optimisé pour :
- **Desktop** : 1200px et plus
- **Tablette** : 768px - 1199px
- **Mobile** : 320px - 767px

Points de rupture :
- 768px : Passage au menu hamburger
- 480px : Ajustements pour petits écrans

## 🎨 Palette de Couleurs

```css
--primary-color: #0891b2    /* Teal/Cyan principal */
--primary-dark: #0e7490     /* Teal foncé */
--secondary-color: #06b6d4  /* Cyan secondaire */
--accent-color: #22d3ee     /* Accent cyan clair */
--text-dark: #1e293b        /* Texte foncé */
--text-light: #64748b       /* Texte clair */
--bg-light: #f8fafc         /* Fond clair */
--bg-white: #ffffff         /* Blanc */
```

## 📧 Informations de Contact

- **Email** : benabdallah.wael@isaas.u-sfax.tn
- **Téléphone** : +216 21 780 447
- **Localisation** : Sfax, Tunisie
- **LinkedIn** : [Wael Ben Abdallah](https://www.linkedin.com/in/wael-benabdallah-096758302)
- **GitHub** : [Wael11BenAbdal123](https://github.com/Wael11BenAbdal123)

## 🎓 À propos

**Wael Ben Abdallah**  
Étudiant en 3e année de Licence en Informatique de Gestion  
Spécialité : Business Intelligence  
ISAAS Sfax - Institut Supérieur des Arts Appliqués de Sfax

Actuellement à la recherche d'un stage de fin d'études de 3 mois à partir de février dans les domaines :
- Business Intelligence
- Développement Web Full-Stack
- Analyse de Données

## 🔄 Corrections Appliquées (2025-10-27)

### ✅ Optimisations de Performance

1. **Animations Conditionnelles**
   - Animations lourdes désactivées sur mobile
   - Curseur personnalisé uniquement sur desktop avec souris
   - Particules réduites et optimisées (10 au lieu de 20)
   - Vérification de `prefers-reduced-motion` pour l'accessibilité

2. **JavaScript Optimisé**
   - Détection de la taille d'écran avant d'activer les animations
   - Utilisation de `requestAnimationFrame` pour le parallax
   - Réduction du nombre de particules créées
   - Intervalle de création des particules augmenté (1000ms au lieu de 300ms)

3. **CSS Amélioré**
   - Utilisation de `translate3d` pour l'accélération GPU
   - Media queries améliorées pour mobile
   - Animations masquées sur mobile avec `display: none !important`
   - Meilleur overflow handling pour le menu mobile

### ✅ Corrections Fonctionnelles

1. **Formulaire de Contact**
   - Ajout de la validation du champ "Sujet" (subject)
   - Intégration mailto pour envoi d'emails
   - Messages d'erreur améliorés et plus clairs
   - Redirection vers le client email après validation

2. **Navigation Mobile**
   - Défilement vertical ajouté pour les menus longs
   - Animation de clic sur le bouton toggle
   - Meilleure transition du menu (left au lieu de transform)
   - Hauteur maximale définie avec overflow scroll

3. **Responsive Design**
   - Boutons pleine largeur sur mobile
   - Espacement optimisé pour petits écrans
   - Grilles adaptatives améliorées
   - Images de profil redimensionnées correctement
   - Description du héro en taille responsive

### ✅ Améliorations d'Accessibilité

1. **Support de `prefers-reduced-motion`**
   - Désactivation automatique des animations pour les utilisateurs sensibles
   - Durées d'animation minimales appliquées
   - Curseur et particules désactivés si mouvement réduit

2. **Navigation au Clavier**
   - Labels aria présents sur les boutons
   - Focus visible sur les éléments interactifs
   - Structure sémantique HTML améliorée

### 🐛 Bugs Corrigés

- ✅ Animations saccadées sur mobile → Désactivées pour meilleures performances
- ✅ Curseur custom apparaissant sur tactile → Limité aux devices avec souris
- ✅ Formulaire manquait la validation du sujet → Ajoutée
- ✅ Menu mobile débordant sur petits écrans → Scroll ajouté
- ✅ Parallax causant des sauts → Optimisé avec RAF et limites
- ✅ Trop de particules ralentissant le site → Réduit à 10

## 🔄 Mises à Jour Futures

- [ ] Intégration d'un backend pour le formulaire de contact
- [ ] Ajout d'un blog
- [ ] Version multilingue (FR/EN)
- [ ] Mode sombre
- [ ] Galerie de projets étendue
- [ ] Téléchargement de CV

## 🛠️ Dépannage

### Le formulaire de contact ne fonctionne pas
- Assurez-vous qu'un client email est installé (Outlook, Thunderbird, etc.)
- Le site doit être servi via HTTP (pas en file://)
- Vérifiez que JavaScript est activé dans votre navigateur

### Les animations sont saccadées
- Vérifiez que votre navigateur supporte l'accélération GPU
- Les animations lourdes sont automatiquement désactivées sur mobile
- Essayez de désactiver les extensions de navigateur

### Le menu mobile ne s'affiche pas
- Vérifiez que JavaScript est activé
- Nettoyez le cache du navigateur (Ctrl+F5)
- Vérifiez la console pour les erreurs JavaScript

### Images ne se chargent pas
- Vérifiez que le fichier `assets/images/CV Phoo.png` existe
- Vérifiez les chemins relatifs dans les fichiers HTML
- Servez le site via un serveur local plutôt qu'en file://

## 📄 Licence

© 2025 Wael Ben Abdallah. Tous droits réservés.

---

**Conçu avec ❤️ et passion pour le code propre**
