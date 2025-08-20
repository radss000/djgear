# DJ GEAR Website

## 🎵 Your Event Sounds Better With Us

Site vitrine professionnel pour DJ GEAR - Location de matériel son et lumière haut de gamme pour événements, yachting et luxe.

## 📁 Structure du Projet

```
DJ-GEAR-WEBSITE/
│
├── index.html              # Page principale
├── README.md              # Documentation
│
├── css/
│   └── style.css          # Styles principaux
│
├── js/
│   └── script.js          # JavaScript principal
│
├── images/
│   ├── logo-djgear.png    # Logo principal
│   ├── favicon.ico        # Favicon
│   ├── hero-bg.mp4        # Vidéo de fond hero
│   │
│   ├── expertise-dj.jpg   # Image section expertise
│   │
│   ├── icon-sonorisation.svg
│   ├── icon-lumiere.svg
│   ├── icon-direction.svg
│   ├── icon-yachting.svg
│   │
│   ├── competence-1.jpg
│   ├── competence-2.jpg
│   ├── competence-3.jpg
│   │
│   ├── vision-equipment.jpg
│   ├── vision-collaboration.jpg
│   ├── vision-detail.jpg
│   │
│   ├── logo-panda-events.png
│   ├── logo-apa.png
│   ├── logo-lastation.png
│   ├── logo-gf.png
│   │
│   ├── realisation-1.jpg
│   ├── realisation-2.jpg
│   ├── realisation-3.jpg
│   ├── realisation-4.jpg
│   ├── realisation-5.jpg
│   ├── realisation-6.jpg
│   ├── realisation-7.jpg
│   ├── realisation-8.jpg
│   ├── realisation-9.jpg
│   │
│   ├── icon-facebook.svg
│   └── icon-instagram.svg
│
└── fonts/
    └── (Google Fonts - Inter)
```

## 🚀 Installation

1. **Cloner le repository**
```bash
git clone https://github.com/djgear/website.git
cd dj-gear-website
```

2. **Héberger les images**
   - Placer toutes les images dans le dossier `/images/`
   - Respecter exactement les noms de fichiers indiqués

3. **Lancer le site**
   - Ouvrir `index.html` dans un navigateur
   - Ou utiliser un serveur local (Live Server, XAMPP, etc.)

## 🎨 Caractéristiques

### Design
- **Palette de couleurs** : Noir (#000), Gris foncé (#0a0a0a), Bleu (#1e40af, #3b82f6), Violet (#7c3aed)
- **Typographie** : Inter (Google Fonts) - 300, 400, 600, 700, 900
- **Style** : Moderne, minimaliste, professionnel avec touches néon

### Sections
1. **Hero** - Message principal avec animation
2. **L'expertise événementielle** - Présentation du savoir-faire
3. **Services** - 4 services principaux (Sonorisation, Lumière, Direction Technique, Yachting)
4. **Nos compétences** - 3 compétences clés
5. **Notre vision et savoir-faire** - 3 piliers
6. **Réussir avec vous** - Témoignages clients
7. **Nos réalisations** - Galerie de projets
8. **FAQs** - Questions fréquentes
9. **Contact** - Informations de contact

### Fonctionnalités
- ✅ Navigation sticky avec effet au scroll
- ✅ Menu mobile responsive
- ✅ Animations au scroll (fade-in, parallax)
- ✅ Accordéon FAQ interactif
- ✅ Galerie avec lightbox
- ✅ Effets hover sur tous les éléments interactifs
- ✅ Optimisé SEO
- ✅ Performance optimisée (lazy loading, debounce/throttle)

## 📱 Responsive Design

- **Desktop** : 1920px et plus
- **Laptop** : 1024px - 1919px
- **Tablet** : 768px - 1023px
- **Mobile** : 320px - 767px

## 🛠 Technologies Utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Animations, Flexbox, Grid
- **JavaScript** - Vanilla JS (ES6+)
- **Google Fonts** - Typographie Inter

## 📊 Performance

- Lazy loading pour les images
- Minification CSS/JS recommandée en production
- Optimisation des images (WebP recommandé)
- Débounce/Throttle sur les événements scroll/resize

## 📞 Contact

**DJ GEAR**
- 📱 Phone: +33 6.03.03.36.24
- 📧 Email: djge4r@gmail.com
- 📍 Location: Nice, France
- 🌐 Since: 2015

## 🔧 Maintenance

### Pour ajouter une réalisation :
1. Ajouter l'image dans `/images/realisation-X.jpg`
2. Ajouter le HTML dans la section réalisations :
```html
<div class="realisation-card" data-category="[categorie]">
    <img src="images/realisation-X.jpg" alt="Description">
    <div class="realisation-overlay">
        <h3>Titre du Projet</h3>
    </div>
</div>
```

### Pour ajouter une FAQ :
1. Ajouter dans la section FAQs :
```html
<div class="faq-item">
    <div class="faq-question">
        <span>VOTRE QUESTION ?</span>
        <span class="faq-toggle">+</span>
    </div>
    <div class="faq-answer">
        <p>Votre réponse détaillée.</p>
    </div>