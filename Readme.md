# 🏠 StreamZy – Page d’Accueil

## 🎬 Présentation

La **page d’accueil ** est la porte d’entrée principale du site.  
Elle présente une interface immersive inspirée des plateformes de streaming modernes (comme Netflix, Xalaflix), avec une mise en avant visuelle du contenu et une navigation fluide entre les sections **Reprise de lecture**, **Films**, **Séries**, et **Catégories spéciales**.

## 🌟 Structure générale

- **Header** :
    - Logo du site **StreamZy**  (gauche)
    - Menu de navigation : Accueil, Séries, Films, Ma liste, Nouveautés
    - Icônes : recherche 🔍 et profil 👤 (droite)

- **Bannière principale** :
    - Image grand format du contenu vedette : **Futurama**
    - Titre, description, année et genres affichés
    - Deux boutons d’action :
        - `Lecture` → Lien vers la bande-annonce YouTube
        - `Voir plus` → Renvoie vers la page dédiée à la série

- **Section “Reprendre la lecture”** :
    - Présente les contenus déjà commencés par l’utilisateur (ex : *The Big Bang Theory*, *Malcolm*, *Rush*, *Coraline*).
    - Chaque carte contient une image, le temps restant et le titre du contenu.

- **Section “Séries d’animation”** :
    - Un carrousel animé avec plusieurs slides mettant en avant des séries humoristiques et animées (*American Dad*, *Family Guy*, *Les Simpson*, *Rick & Morty*, etc.).
    - Navigation fluide grâce à un système de boutons de la droite et vers la gauche.

- **Section “Séries”** :
    - Présente une sélection de séries cultes et populaires : *The Walking Dead*, *Dexter*, *Stranger Things*, *Gossip Girl*, etc.
    - Même structure que la section précédente, avec un carrousel horizontal.

- **Section “Inspirés de livres”** :
    - Catégorie thématique mettant en avant des films adaptés de romans célèbres (*Le Cercle des poètes disparus*, *Harry Potter*, *Divergent*, *Narnia*...).

- **Footer** :
    - Mentions légales, politique de confidentialité et lien de contact.
    - Texte de bas de page : “© 2025 Un site web de qualité. Profitez.”

## 💡 Objectifs de conception

Cette page a été pensée pour :
- Offrir une **expérience utilisateur immersive et fluide**.
- Valoriser les contenus à travers des **visuels forts et attractifs**.
- Une **mise en page responsive** s’adaptant à tous les écrans.
- Une **cohérence graphique** entre toutes les pages du site (accueil, films, séries...).

## ⚙️ Technologies utilisées

- **HTML5** : structure de la page
- **SCSS (Sass)** : Gestion du style, de la mise en page et des animations, mise en forme et responsive design
- **Flexbox** → Organisation des cartes d’épisodes
- **Images fichier Puclic** : `.webp`, `.jpeg`, `.png`
- ** Lien YouTube** pour la bande-annonce
- **Liens internes** → Navigation fluide entre les pages du site (*index.html*, *pagefuturama.html*, etc.)

//////

# 📺Streamzy : Page d'information : Film Coraline

## 🧩 Présentation

La page **Film Coraline** est une page dédiée **à la présentation d’un film. En donnant un maximum d'information claire.**

## 🌟 Structure générale

- **Menu de navigation Navbar** : permet d’accéder aux autres sections du site (Accueil, Séries, Films, Ma liste, Nouveautés).
-  **Icônes utilisateur et recherche** : pour une navigation simplifiée.
- **Image de fond immersive** : met en valeur l’univers du film "Coraline".
- **Logo du film** : affiché en avant sur le fond.
- **Bouton retour** : pour permettre de revenir en arrière.
- **Fil d'ariane** : afficher les étapes de lecture du site.
- **Informations principales** :
    - Année de sortie : 2009
    - Durée : 1h40
    - Genres : Enfants, Horreur
    - Réalisateur : Henry Selick
    - Studio : ITV Studios
    - Distribution : Dakota Fanning, Teri Hatcher, Keith David, Ian McShane
- **Description** : courte présentation du synopsis.
- **Boutons d’action** :
    - `Lecture` → renvoie vers la bande-annonce YouTube
    - `Reprendre au début` → relance le film depuis le début
- **Section “À voir aussi”** : présente d’autres films similaires sous forme de cartes visuelles.
- **Footer** : inclut les mentions légales, la politique de confidentialité et un lien de contact.

## 💡 Objectif de conception

Cette page a été conçue pour :
- Apporter des **informations claires** et précises sur le film.
- Valoriser le **contenu visuel** (images et typographies) pour renforcer l’ambiance du film.
- Maintenir une **navigation fluide et accessible** grâce à un design simple et cohérent.

## ⚙️ Technologies utilisées

- **HTML5** : structure de la page
- **SCSS (Sass)** : Gestion du style, de la mise en page et des animations, mise en forme et responsive design
- **Flexbox** → Organisation des cartes d’épisodes
- **Images fichier Puclic** : `.webp`, `.jpeg`, `.png`
- ** Lien YouTube** pour la bande-annonce
- **Liens internes** → Navigation fluide entre les pages du site (*index.html*, *pagefuturama.html*, etc.)

////

# 📺 StreamZy – Page d'information : Série The Big Bang Theory

## 🎬 Présentation :

Cette page permet à l’utilisateur de **découvrir les épisodes, lire les résumés, et lancer la lecture** de façon simple.

## 🌟 Structure générale :

- **Header**
    - Logo StreamZy
    - Menu principal : Accueil / Séries / Films / Ma Liste / Nouveautés
    - Icônes de recherche et de profil

- **Bannière principale**
    - **Image de fond** représentant la série
    - **Bouton retour** : pour permettre de revenir en arrière.
    - **Fil d'ariane** : afficher les étapes de lecture du site.
    - **Logo officiel** *The Big Bang Theory*
    - **Informations principales** : âge, HD, sous-titres, années de diffusion
    - Description courte de l’épisode sélectionné
    - **Deux boutons** :
        - **Lecture** → Renvoie vers la bande-annonce YouTube
        - **Reprendre au début** → Redirection vers une autre page de série

## 📚 Navigation des saisons :

Une **barre de navigation horizontale** permet d’accéder facilement aux différentes saisons :
- De **Saison 1 à Saison 12**
- Le bouton de la saison active est mis en surbrillance

## 💡 Objectifs de conception

La liste de chaque épisode est présenté sous forme de **carte visuelle**, contenant :
- Une **image de prévisualisation**
- Le **titre de l’épisode**
- Un **résumé détaillé**
- La **durée moyenne**

-> Les épisodes sont organisés dans un **grille fluide** qui s’adapte à toutes les tailles d’écran.

## ⚙️ Technologies utilisées

- **HTML5** : structure de la page
- **SCSS (Sass)** : Gestion du style, de la mise en page et des animations, mise en forme et responsive design
- **Flexbox** → Organisation des cartes d’épisodes
- **Images fichier Puclic** : `.webp`, `.jpeg`, `.png`
- ** Lien YouTube** pour la bande-annonce
- **Liens internes** → Navigation fluide entre les pages du site (*index.html*, *pagefuturama.html*, etc.)   