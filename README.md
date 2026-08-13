
# Interfaces modernes : HTML5/CSS3 avancés & performance (Grid/Flex + API de stockage)

Cet atelier comporte deux volets. Le Volet A (nouveau) est un entraînement Grid/Flex avancés avec une solution fournie (codes) que vous pouvez copier et tester. Le Volet B conserve l’activité API de stockage Web (LocalStorage) de l’énoncé existant.

## Cahier des charges
Je dois :

• Une page : 01_GridFlex/index.html + 01_GridFlex/css/style.css.

• Structure : Header (logo + nav), Sidebar (optionnelle), Main (cartes/sections), Footer.

• Header en Flexbox, layout global en Grid (areas ou 12 colonnes).

• Grille de cartes responsive : repeat() + minmax() + auto-fit/auto-fill.

• 2 breakpoints minimum (ex. 900px et 600px).

• Performance : sobriété (≤2 polices), images légères ; animations raisonnables.

### EXERCICES GUIDES

Je dois :

• Créez index.html avec <header>, <nav>, <main>, <aside> (optionnel) et <footer>.

• Créez style.css et définissez un layout global en Grid via .layout.

• Option recommandée : grid-template-areas.

• Mettez le header en Flex : aligner logo/nom à gauche et menu à droite.

• Ajoutez un style hover + focus visible.

• Créez une grille de cartes en CSS Grid avec repeat(auto-fit, minmax(...)).

• Ajoutez une carte ‘featured’ qui occupe 2 colonnes sur desktop.

• À 900px : réduire la sidebar si besoin ; à 600px : passer en une seule colonne.

• Assurez-vous que le menu ne casse pas la mise en page.

• Ouvrir DevTools → Network : vérifier le poids total et le nombre de requêtes.

• Limiter polices et images ; éviter bibliothèques lourdes ; supprimer CSS inutilisé.






## API de stockage Web (LocalStorage)

L’API Web Storage (HTML5) permet de stocker des données localement dans le navigateur, sans base de données externe. Les données sont stockées sous forme de couples clé/valeur (chaînes de caractères). Dans cette annexe, vous allez créer une page qui mémorise le thème choisi (jour/nuit) et, dans une version avancée, mémorise aussi un paragraphe saisi par l’utilisateur.

### Objectif de l’activité pratique
• Créer une page HTML5 avec deux thèmes CSS3 : ‘jour’ et ‘nuit’.

• L’utilisateur choisit le thème via des boutons.

• Le dernier thème choisi est mémorisé dans localStorage et restauré au prochain chargement.

• IMPORTANT (Semaine 1) : ne pas utiliser addEventListener. Utiliser uniquement onload/onclick (événements HTML classiques). 


#### Travail Personnel — Version 1 & 2 (v1 & v2)
• Ajouter d’autres thèmes (ex. bleu, vert, contrasté).

• Ajouter un bouton par thème (onclick).

• Mémoriser et restaurer le thème choisi via localStorage.

• Nom du fichier à déposer : Nom_Prenom_LocalStorage_v1.zip

Et dans la version 2, je dois saisir un texte dans un champ, puis cliquer sur un bouton pour remplacer le paragraphe existant. Le dernier thème ET le dernier paragraphe doivent être restaurés au prochain chargement.

