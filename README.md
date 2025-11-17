# Site Vitrine Hôpital - HTML5 & CSS3

Un site vitrine moderne et responsive pour un hôpital, développé en **HTML5 pur et CSS3** sans aucun framework.

## Caractéristiques

✨ **Design Moderne**
- Interface élégante et professionnelle
- Palette de couleurs médicale (bleu professionnel)
- Animations fluides et transitions CSS3

📱 **Responsive Design**
- Entièrement responsive sur tous les appareils
- Mobile-first approach
- Breakpoints optimisés pour tablettes et téléphones

🏗️ **Structure Sémantique**
- HTML5 sémantique
- Accessibilité optimisée
- SEO-friendly

⚡ **Performance**
- Pas de dépendances externes
- Chargement rapide
- Optimisé pour tous les navigateurs

## Structure du Projet

```
hopital-html5/
├── index.html          # Page principale
├── css/
│   └── styles.css      # Styles CSS3
├── js/
│   └── script.js       # JavaScript vanilla
├── images/
│   ├── hero-hospital.jpg
│   └── doctor-team.jpg
└── README.md          # Ce fichier
```

## Sections du Site

1. **En-tête (Header)** - Navigation sticky avec logo
2. **Section Héros** - Présentation principale avec CTA
3. **Services** - 6 services médicaux avec icônes
4. **Équipe** - Présentation de 4 professionnels
5. **Témoignages** - 3 avis clients
6. **Contact** - Formulaire et informations
7. **Pied de page** - Liens et informations légales

## Utilisation

### Ouvrir le site
1. Décompressez le dossier `hopital-html5`
2. Double-cliquez sur `index.html` pour ouvrir dans votre navigateur
3. Ou utilisez un serveur local (recommandé):

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js
npx http-server

# Avec PHP
php -S localhost:8000
```

Puis ouvrez `http://localhost:8000` dans votre navigateur.

## Personnalisation

### Modifier les couleurs
Éditez les variables CSS au début du fichier `css/styles.css`:

```css
:root {
    --primary-color: #1e40af;      /* Couleur principale */
    --primary-dark: #1e3a8a;       /* Couleur sombre */
    --primary-light: #3b82f6;      /* Couleur claire */
    /* ... autres variables ... */
}
```

### Modifier le contenu
- **Texte**: Éditez directement dans `index.html`
- **Images**: Remplacez les fichiers dans le dossier `images/`
- **Styles**: Modifiez `css/styles.css`

### Ajouter des sections
Copiez une section existante dans `index.html` et adaptez le contenu.

## Compatibilité Navigateurs

✅ Chrome (dernière version)
✅ Firefox (dernière version)
✅ Safari (dernière version)
✅ Edge (dernière version)
✅ Mobile browsers

## Fonctionnalités JavaScript

- Scroll fluide vers les sections
- Validation du formulaire de contact
- Animations au chargement
- Gestion des clics sur les CTA

## Optimisations CSS3

- **Flexbox** pour la mise en page
- **CSS Grid** pour les grilles de services
- **Media Queries** pour la responsivité
- **Animations CSS** pour les effets
- **Transitions** pour les interactions
- **Variables CSS** pour la maintenabilité

## Conseils de Déploiement

1. **Optimisez les images** - Compressez les images JPG/PNG
2. **Minifiez le CSS** - Réduisez la taille du fichier CSS
3. **Testez la responsivité** - Vérifiez sur tous les appareils
4. **Vérifiez les liens** - Assurez-vous que tous les liens fonctionnent
5. **Testez le formulaire** - Validez le formulaire de contact

## Licence

Libre d'utilisation pour usage personnel et commercial.

## Support

Pour toute question ou modification, consultez la documentation HTML5 et CSS3 officielle.

---

**Créé avec ❤️ en HTML5 et CSS3 pur**
