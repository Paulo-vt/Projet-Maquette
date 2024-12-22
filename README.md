Projet : Song Universe

Song Universe est une plateforme immersive permettant aux utilisateurs d’explorer un univers musical unique généré par l’IA. Ce projet met en avant des genres musicaux moins connus tout en offrant une interface intuitive pour explorer des collections d’audios, de vidéos et d’artistes.

Différence entre HTML et CSS

HTML est utilisé pour structurer le contenu d'une page web. Il définit des éléments tels que les titres, paragraphes, images, liens, etc.
CSS est utilisé pour styliser le contenu HTML. Il contrôle l'apparence visuelle : couleurs, polices, marges, dispositions, etc.

Explication du squelette HTML

<!DOCTYPE html> : Spécifie le type de document.
<header> : Contient la barre de navigation avec des liens vers les sections principales : Accueil, Collections, À propos et Contact.
<section id="home"> : Introduction avec une image de fond, un titre et un bouton pour explorer.
<section id="collection"> : Présente les catégories "Audio", "Vidéo" et "Artistes" avec des images cliquables.
<section id="audios"> : Liste d’audios avec des informations (titre, style, artiste).
<section id="videos"> : Affiche des vidéos avec des lecteurs intégrés.
<section id="artists"> : Présente des artistes avec des liens externes.
<section id="about"> : Informations sur le site et sa mission.
<section id="services"> : Formulaire de contact pour contribuer à la plateforme.
<footer> : Mention de copyright.

Définition de la sémantique

En HTML, la sémantique signifie utiliser des balises appropriées pour décrire la nature du contenu (par exemple, <header> pour l’en-tête, <article> pour un article, <footer> pour le pied de page). Cela améliore l’accessibilité et le référencement.

Différence entre un ID et une classe

ID : Identifiant unique (id="example") pour un élément spécifique. Un ID ne peut être utilisé qu'une seule fois par page.
Classe : Groupe des éléments similaires (class="example") pour appliquer un style commun. Une classe peut être réutilisée sur plusieurs éléments.

Différence entre flexbox, grid et position

Flexbox : Alignement d’éléments sur une seule dimension (ligne ou colonne).
Grid : Mise en page sur deux dimensions (lignes et colonnes), idéal pour des dispositions complexes.

Position : Contrôle de l’emplacement d’un élément dans le document (e.g., relative, absolute, fixed, sticky).

Fonctionnement des pseudo-classes et transitions

Pseudo-classes : Permettent de sélectionner un élément selon son état, par exemple, :hover pour un élément survolé.
Transitions : Ajoutent des effets d’animation entre deux états CSS (e.g., transition: all 0.3s ease-in-out;).

Explication des attributs HTML et leur utilité

Les attributs ajoutent des informations supplémentaires aux éléments HTML. Exemple :
src pour spécifier la source d’une image ou d’une vidéo.
alt pour fournir une description textuelle d’une image.
href pour les liens hypertextes.
required pour indiquer qu'un champ de formulaire est obligatoire.

Fonctionnement d’un formulaire HTML
Un formulaire HTML collecte des entrées utilisateur via des champs comme <input>, <textarea>, etc. Ces données sont ensuite envoyées à une URL spécifiée via les attributs action (destination) et method (GET ou POST).

Fonctionnement des media queries

Les media queries adaptent les styles CSS en fonction des caractéristiques de l’appareil (taille d’écran, résolution). Exemple :

@media (max-width: 768px) {
    body {
        background-color: lightgray;
    }
}
Cela permet de créer des designs réactifs.
