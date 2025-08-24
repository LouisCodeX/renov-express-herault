# Orb & Linteau – Maçonnerie & Rénovation en Hérault

Ce dépôt contient le code source d’un site vitrine pour **Orb & Linteau**, une entreprise de maçonnerie générale et de rénovation tous corps d’état implantée à Béziers et active dans tout l’Hérault. Le site présente les services proposés (ouverture de murs porteurs, dalles et fondations, reprises en sous‑œuvre, rénovation complète), des réalisations, des témoignages clients et un formulaire de contact enrichi.

## Structure du projet

- **`index.html`** : la page principale du site, structurée en sections (header, hero, services, réalisations, à propos, témoignages, blog/FAQ, contact et footer). Le contenu est rédigé en français, optimisé pour le référencement local et facile à modifier.
- **`styles.css`** : feuille de style complète qui définit la palette de couleurs (rouge profond et anthracite), les typographies (Montserrat et Merriweather), la mise en page responsive, les icônes Font Awesome et les animations de survol. Elle gère également l’apparence des formulaires, du portfolio et des témoignages.
- **Images** : 
  - `logo_orb_linteau_simple.png` – logo officiel sans devise utilisé dans l’en‑tête.  
  - `hero_bg.png` – image de fond personnalisée pour la section hero.  
  - `project_bathroom3.png`, `project_living3.png`, `project_kitchen3.png`, `project_loft2.png`, `project_rooftop.png`, `project_patio_flower.png` – photos de réalisations récentes à Béziers et Marseillan (nouvelle salle de bain, salon et escalier, cuisine contemporaine, salon sous combles, terrasse vue toits, patio fleuri).  
  - `favicon.png` – icône simplifiée de l’arche et du linteau pour l’onglet du navigateur.
  - D’autres images peuvent être ajoutées au besoin pour enrichir la galerie.
- **`README.md`** : ce fichier qui décrit la structure et fournit des instructions d’utilisation et de déploiement.

## Utilisation

Pour visualiser le site en local, ouvrez simplement `index.html` dans votre navigateur. Pour une mise en ligne :

1. Créez un nouveau dépôt GitHub ou utilisez celui-ci, puis poussez les fichiers dans la branche `main` (ou `master`).
2. Activez **GitHub Pages** dans les paramètres du dépôt et sélectionnez la branche `main` et le dossier racine (root) comme source. GitHub génèrera automatiquement le site à l’adresse `https://<utilisateur>.github.io/<nom-du-dépôt>/`.
3. (Optionnel) Configurez un **nom de domaine personnalisé** via vos DNS pour rediriger vers le site GitHub Pages.

## Personnalisation

- **Contenus** : Modifiez les textes des différentes sections dans `index.html` pour qu’ils correspondent à votre entreprise (services proposés, présentation, témoignages, blog/FAQ, coordonnées).  
- **Images** : Remplacez les images fournies par vos propres photos de chantiers. Placez les nouvelles images dans le dossier du projet et mettez à jour les attributs `src` dans `index.html`.
- **Couleurs et polices** : Adaptez la palette de couleurs et la typographie en ajustant les variables CSS dans `styles.css` (`--primary-color`, `--secondary-color`, etc.) et en changeant les familles de polices.
- **Formulaire** : Le formulaire de contact comprend un champ de téléchargement de photo et des champs pour le type de projet et le budget estimé. Modifiez l’action et la méthode du formulaire selon votre backend (ex. service d’email ou API).
- **Blog / FAQ** : Les blocs de blog sont des exemples. Remplacez les titres et textes par vos propres articles. Vous pouvez aussi les transformer en liens vers une page externe ou un CMS.
- **Mentions légales** : Ajoutez un fichier `mentions-legales.html` et un lien dans le footer pour respecter la réglementation française.

## Dépendances externes

Le site utilise des ressources externes chargées via CDN :

- **Google Fonts** pour les polices Montserrat et Merriweather.  
- **Font Awesome 6** pour les icônes utilisées dans les services et la liste des valeurs.  
- **CSS resets** via nos propres définitions `* { box-sizing: border-box; }`.

Toutes les ressources sont chargées en HTTPS pour garantir la sécurité et la compatibilité avec les navigateurs modernes.

## Licence

Ces fichiers sont fournis sans garantie et peuvent être utilisés, modifiés et distribués librement. L’auteur décline toute responsabilité en cas d’utilisation non conforme aux réglementations locales (notamment en matière de mentions légales, de protection des données personnelles et de garanties de travaux).