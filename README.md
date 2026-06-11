# 💎 Credson UI Kit Premium (Tailwind CSS)

> **La bibliothèque ultime de composants Tailwind CSS prêts à l'emploi pour les développeurs exigeants.**
> Construisez des interfaces modernes, rapides et époustouflantes en un simple Copier-Coller.

![Version](https://img.shields.io/badge/Version-3.0-blue.svg)
![Composants](https://img.shields.io/badge/Composants-70%2B-success.svg)
![Tailwind](https://img.shields.io/badge/Tailwind-CSS-06b6d4.svg)
![Licence](https://img.shields.io/badge/Licence-Open%20Source%20%2F%20Commercial-a78bfa.svg)

---

## 🌟 Présentation du Kit

Credson UI Kit n'est pas juste une collection de bouts de code. C'est un **Design System complet** conçu spécialement pour le Dark Mode avec des effets premiums : *Glassmorphism, animations fluides (shimmer, pulse), et dégradés élégants*. 

Oubliez les designs fades. Chaque composant a été méticuleusement conçu par **Crédo ADJIGNON (Credson)** pour offrir une expérience utilisateur ("WOW effect") immédiate.

### 🔥 Fonctionnalités clés
- **70+ Composants** répartis dans 16 catégories logiques.
- **Zéro Dépendance JS Externe** : Fonctionne avec du HTML pur et Tailwind CSS (et un zeste de JS vanille pour l'interactivité).
- **Copie Intelligente** : Un clic sur le bouton "Copier le code" de chaque composant suffit.
- **Dark Mode Natif** : L'esthétique premium sombre (Deep Violet & Neon Cyan) est intégrée par défaut.
- **Responsive Design** : Pixel-perfect du mobile à l'écran 4K.

---

## 🚀 Démarrage Rapide (Usage Local)

Si vous souhaitez modifier le code source ou adapter les couleurs de base à votre marque, vous pouvez lancer l'environnement de développement inclus.

### 1. Installation

Assurez-vous d'avoir [Node.js](https://nodejs.org/) installé sur votre machine.
Ouvrez votre terminal dans le dossier du projet et installez les dépendances :

```bash
npm install
```

### 2. Mode Développement (Watch)

Pour compiler le CSS en temps réel à chaque modification dans `index.html` :

```bash
npm run dev
```

### 3. Mode Production (Build)

Pour générer le fichier CSS minifié, purgé et optimisé pour la mise en ligne :

```bash
npm run build
```

---

## 📦 Que contient ce Kit ? (Les 16 Catégories)

Le fichier `index.html` est votre tableau de bord interactif. Voici ce que vous y trouverez :

1. 🔘 **Boutons & CTAs** (Shimmer, glow, états de chargement)
2. 🏷️ **Badges & Tags** (Statuts, puces lumineuses)
3. 👤 **Avatars & Profils** (Groupes, halos animés)
4. ⌨️ **Inputs & Toggles** (Champs animés, switchers iOS-like)
5. 🃏 **Cartes & Pricing** (Glassmorphism, hover 3D, plans SaaS)
6. 🪟 **Modales & Dialogs** (Popups de confirmation, modales d'information)
7. 📋 **Menus Déroulants** (Dropdowns élégants)
8. 🔔 **Alertes & Toasts** (Notifications de succès, erreur, avertissement)
9. 🧭 **Navbars** (Navigation desktop et mobile avec blur)
10. 🚀 **Hero Sections** (En-têtes de sites spectaculaires)
11. 📊 **Stats & FAQ** (Accordéons fluides, compteurs)
12. 🦶 **Footers** (Pieds de page complexes multi-colonnes)
13. 📈 **Tableaux & Données** (Datatables premium avec badges)
14. 🧭 **Navigation & Filtres** (Pagination, breadcrumbs)
15. 📝 **Contenu & Social** (Timelines, grilles d'articles)
16. ✨ **Marketing & CTAs** (Bannières promotionnelles, newsletter)

---

## 🎨 Personnalisation du Thème (Marque Blanche)

Le kit utilise Tailwind CSS via CDN dans `index.html` avec un objet de configuration intégré (`tailwind.config`). 

Pour changer la couleur primaire du projet, modifiez simplement les clés `brand` dans la balise `<script>` au début du fichier `index.html` :

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        brand: {
          50: '#...', 100: '#...',
          500: '#8b5cf6', // Votre couleur principale ici
          // ...
        }
      }
    }
  }
}
```

---

## 🛠️ Hébergement / Déploiement

Vous pouvez héberger le projet `index.html` (et `about.html`) où vous le souhaitez. 
Puisque le site est **statique**, nous vous recommandons :

1. **GitHub Pages** (Gratuit, parfait pour les portfolios et documentations).
2. **Vercel** (Gratuit, ultra-rapide, excellent pour attacher un domaine personnalisé).
3. **Netlify** (Gratuit, très simple par glisser-déposer).

---

## 🙋‍♂️ À propos du Créateur

Créé avec passion par **Crédo ADJIGNON (Credson)**, étudiant en IA & Big Data, développeur et designer au Togo 🇹🇬.
Ce projet fait partie du catalogue de **Chariow**, la boutique de ressources de Credson Studio.

- 🌐 **Portfolio** : [Mon Portfolio](https://creedemmanuel7-sketch.github.io/mon-portfolio)
- 💬 **WhatsApp** : [+228 96 56 97 61](https://wa.me/22896569761)
- 📧 **Email** : creedemmanuel7@gmail.com

---

## 📄 Licence

Ce kit est fourni sous **Licence Ouverte / Libre (Commerciale & Personnelle)**.
- **Ce que vous pouvez faire :** L'utiliser dans vos projets clients, vos SaaS, vos portfolios personnels, le modifier et même l'inclure dans un template payant que vous développez.
- **Ce qui est interdit :** Revendre le kit *exactement tel quel* sans aucune modification significative en prétendant en être l'auteur original.

<br>
<div align="center">Fait avec ❤️ par <strong>Credson Studio</strong> × <strong>Chariow</strong></div>
