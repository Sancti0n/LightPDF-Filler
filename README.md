# LightPDF-Filler

**LightPDF-Filler** est un éditeur et remplisseur de formulaires PDF ultra-léger, interactif et 100 % autonome, exécuté intégralement dans le navigateur web.

Il a été conçu pour cocher des cases, saisir du texte et annoter n'importe quel document PDF de manière visuelle, rapide et sécurisée, sans nécessiter l'installation de logiciels lourds ni le transfert de documents vers des serveurs tiers.

---

## Fonctionnalités détaillées

### 1. Édition visuelle sur document (Canvas)
* **Import instantané :** Glissez-déposez ou sélectionnez n'importe quel fichier PDF local.
* **Cochoir rapide (Croix X) :** Placement en un clic de croix d'une taille idéale pour cocher des cases de formulaires.
* **Insertion de texte :** Saisie de champs textuels (noms, dates, adresses, remarques) positionnables à l'endroit exact souhaité.
* **Repositionnement par Glisser-Déposer (Drag & Drop) :** Cliquez et maintenez n'importe quel texte ou croix déjà posé sur le document pour le déplacer à la souris en temps réel.

### 2. Personnalisation des couleurs
* **Couleur par défaut :** Tous les ajouts sont imprimés en noir par défaut pour s'intégrer harmonieusement aux formulaires officiels.
* **Sélecteur de couleur dédié :** Choisissez n'importe quelle teinte depuis la barre d'outils avant l'insertion.
* **Ajustement a posteriori :** Modifiez la couleur d'une annotation spécifique après son placement via un sélecteur individuel.

### 3. Panneau latéral d'inventaire et de suivi
* **Tableau de bord des modifications :** Récapitulatif dynamique de toutes les annotations ajoutées au document.
* **Édition de texte à la volée :** Modifiez directement le contenu d'un champ texte depuis le tableau d'inventaire ; le rendu sur le PDF se met à jour instantanément.
* **Repères géométriques $(X, Y)$ :** Affichage en temps réel des coordonnées exactes de chaque élément (calculées selon le système de coordonnées PDF standard).
* **Suppression sélective :** Retirez une modification précise en un clic sans affecter le reste du travail.
* **Indicateur de page :** Suivi clair de la page sur laquelle se trouve chaque modification.

### 4. Navigation & Export
* **Gestion multipage :** Visualisation et édition fluide des documents composés de plusieurs pages grâce aux commandes de navigation intégrées.
* **Génération PDF en local :** Un clic sur le bouton de téléchargement applique l'ensemble des modifications vectorielles et génère le fichier `formulaire_rempli.pdf` prêt à l'emploi.

### 5. Sécurité et Confidentialité (100 % Client-Side)
* **Zéro serveur :** L'intégralité du traitement (rendu visuel, modifications et assemblage du fichier final) est exécutée par le moteur JavaScript de votre propre navigateur.
* **Données protégées :** Vos documents confidentiels ne quittent jamais votre ordinateur.

---

## Interface utilisateur

L'application s'articule autour d'une interface sobre et réactive :

1. **Barre d'outils supérieure :** Chargement du fichier, navigation entre les pages, choix du mode (*Croix* ou *Texte*), sélecteur de couleur principal, réinitialisation et téléchargement du PDF final.
2. **Zone de travail centrale :** Visualisation haute définition du PDF avec gestion du survol et du glisser-déposer.
3. **Panneau latéral droit :** Inventaire interactif avec mise à jour en direct des champs et des coordonnées.

---

## Prise en main

Aucune installation, compilation ou dépendance Node.js n'est requise.

---

### Utilisation locale

1. Cloner le dépôt :
```bash
   git clone https://github.com/Sancti0n/LightPDF-Filler.git
```

2. Ouvrir le fichier index.html dans n'importe quel navigateur web moderne (Chrome, Firefox, Edge, Safari).

---

### Utilisation en ligne (GitHub Pages)

https://Sancti0n.github.io/LightPDF-Filler/

---

### Stack technique

    PDF.js — Rendu visuel et conversion des pages PDF sur élément HTML5 Canvas.

    pdf-lib — Manipulation vectorielle et assemblage du fichier PDF final.

    HTML5 / CSS3 / JavaScript (Vanilla JS) — Architecture légère sans framework externe pour un chargement instantané.

---

## Licence

Ce projet est sous licence MIT. Consulter le fichier LICENSE pour plus d'informations.