# Framer Expert

# 💎 Masterclass : Créer des Templates Framer "Marketplace-Ready"

Ce guide est ta feuille de route pour transformer tes designs Figma en produits numériques haut de gamme prêts à être vendus.

- --

## 🛠️ Phase 1 : Le "Perfect Figma" (Pré-requis)

Un template pro commence par une structure Figma chirurgicale. Si c'est propre dans Figma, c'est 90% du travail fait dans Framer.

- **Styles Globaux :** Utilise des Styles de Couleurs et de Textes. Framer les importera comme "Variables", ce qui permettra à l'acheteur de changer tout le thème en 2 clics.
- **Auto Layout Absolu :** Tout doit être en Auto Layout. Pas de groupes (`Cmd+G`), uniquement des Frames (`Option+Cmd+G`).
- **Nomenclature "BEM" :** Nomme tes calques de façon logique (ex: `Hero / Content / Badge`). L'acheteur verra ces noms dans l'arborescence Framer.
- --

## 🏗️ Phase 2 : L'Architecture Framer (Le "Pro Way")

Une fois le copier-coller effectué via le plugin, tu dois "nettoyer" la structure pour la rendre indestructible.

1. La règle des "3 F" (Layout)

2. Les Stacks & Grids

- Utilise les **Stacks** (Piles) pour l'alignement vertical/horizontal.
- Utilise les **Grids** (Grilles) pour les sections complexes (ex: une galerie de cartes). C'est beaucoup plus propre pour le responsive.
- --

## 🚀 Phase 3 : Créer des Composants Intelligents

C'est ici que ton template prend de la valeur. Un acheteur paie pour la **flexibilité**.

- **Variables de Composants :** Ne crée pas 10 boutons. Crée **un** composant bouton avec des variables :

• *Plain Text* pour le label.

• *Link* pour la destination.

• *Color* pour le fond.

• *Boolean* (On/Off) pour afficher ou masquer une icône.

- **Hover & Pressed States :** Ajoute systématiquement des interactions sur tes composants pour un effet "Premium".
- --

## 📊 Phase 4 : Le CMS (Content Management System)

Un template qui se vend bien est souvent un template avec un Blog ou un Portfolio dynamique.

1. Crée une **Collection CMS** (ex: "Projets").

2. Lie tes éléments de design aux champs du CMS.

3. Prépare la page **"CMS Detail"** : c'est la page qui s'auto-génère pour chaque article.

- --

## 📱 Phase 5 : Le Responsive Sans Couture

Sur Framer, on ne fait pas juste du "Redimensionnement", on adapte l'expérience.

- **Desktop (1440px) :** Ta base.
- **Tablet (810px) :** Souvent négligée, fais-en un point fort.
- **Phone (390px) :** Change tes Stacks de "Horizontal" à "Vertical".
- **Breakpoints :** Vérifie que rien ne dépasse sur les côtés (pas de scroll horizontal indésirable).
- --

## ✨ Phase 6 : Finitions & Performance (Le Check "Nickel")

Framer et les acheteurs détestent les sites lents.

- **Optimisation Image :** Utilise le format WebP. Framer le fait souvent seul, mais vérifie le poids.
- **Styles de Texte (H1-H6) :** Crucial pour le SEO. Ton titre principal doit être en H1.
- **Custom Cursor :** Ajoute un curseur personnalisé pour ce petit côté "Luxe".
- **Effets de Scroll :** Utilise les `Section in View` pour animer l'apparition des blocs.
- --

## 📂 Phase 7 : Hiérarchie & Organisation des Composants (Design System)

C'est la partie cruciale pour que ton template soit "pro" et facile à maintenir. Organise tes composants par catégories.

1. Boutons (Buttons)

- **Variantes de Style :** `Primary`, `Secondary`, `Ghost` (contour uniquement), `Link`.
- **Variables de Propriétés :**

• `Title` (Texte)

• `Link` (Lien URL)

• `Show Icon` (Booléen : Oui/Non)

• `Loading` (État de chargement)

- **États (States) :** Assure-toi que chaque variante a un état `Hover` (survol) et `Pressed` (clic) fluide.

2. Formulaires & Saisies (Inputs)

- **Structure :** Label + Input Field + Helper Text/Error.
- **Variables :** `Placeholder`, `Required` (Astérisque), `Type` (Text, Email, Password).
- **Focus State :** L'encadré doit changer de couleur quand l'utilisateur clique dedans pour l'accessibilité.

3. Cartes (Cards)

- **Structure Flexible :** Utilise des Stacks imbriquées.

• *Top :* Image (Format `Fill` ou ratio 16:9).

• *Middle :* Badge/Catégorie + Titre + Description.

• *Bottom :* Date ou Bouton "Lire la suite".

- **Animations :** Ajoute un léger `Hover Scale` (agrandissement) ou un changement d'ombre (Box Shadow) pour rendre la carte interactive.
- --

## 💰 Phase 8 : Préparation pour la Vente

Avant de soumettre ton template :

1. **Page de Documentation :** Crée une page cachée ou un guide PDF expliquant comment utiliser le template.

2. **Page de Styleguide :** Une page qui liste toutes les couleurs, typos et composants utilisés.

3. **Lien de Remix :** Génère ton lien de Remix propre (testé en mode navigation privée).