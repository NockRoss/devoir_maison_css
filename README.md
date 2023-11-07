# devoir_maison_css

# Devoir_Maison

J'ai eu beaucoup de mal à faire ce devoir car c'est la première fois que je touche au CSS.

Pour la barre de navigation en Bootstrap, je suis dans un premier temsp aller voir les modèles proposé par Bootstrap.

Pour le format telephone on utilise:

- "<button class="navbar-toggler">" qui permet justement de réduire à son maximum la barre de navigation. le "data-toggle" et le "data-target" son des éléments Bootstrap.

- <div class="collapse navbar-collapse"> est la partie de la nav barre qui s'ouvre ou se ferme en fonction du bouton de bascule dont je viens de parler.

- <li class="nav-item dropdown"> sont fait comme des menus déroulants Bootstrap, lorsque l'on clique dessus ils affichent les options supplémentaire

- <div class="dropdown-menu"> que j'ai mis sur chaque élément de navigation, s'ouvre lorsque l'on clique sur un element.

- <nav class="navbar navbar-expand-lg navbar-dark"> 

En ce qu'il s'agit de cette partie du code de manière générale:

<nav class="navbar navbar-expand-lg navbar-dark">

			<div>

                <ul class="navbar-nav w-100">

				<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">


Nous définissons la barre de navigation de notre site.

- <nav class="navbar navbar-expand-lg navbar-dark"> : Nous disons au site que nous allons créer une barre de navigation. Les classes navbar et navbar-expand-lg indiquent comment la barre de navigation doit apparaître, et navbar-dark spécifie que la barre de navigation aura un fond sombre.

<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"> : Nous créons un bouton qui agit comme un interrupteur pour montrer ou cacher le menu de navigation. Le bouton est configuré pour "basculer" (toggle) le menu quand on clique dessus. Les attributs data-target, aria-controls, aria-expanded, et aria-label sont utilisés pour aider les personnes qui utilisent des technologies d'assistance, comme les lecteurs d'écran, à comprendre comment fonctionne le bouton.

En résumé, ces lignes de code créent la structure de base de la barre de navigation, y compris un bouton pour ouvrir ou fermer le menu, et elles assurent que le menu prendra tout l'espace disponible horizontalement.


Toutes les images s'affichent bien.

Le bloc du milieu n'est pas aligné correctement mais nous avons bien un bloc responsive.


La bare de recherche et la première photo sont aussi responsive, si nous sommes sur téléphone, les éléments seron l'un au dessus de l'autre.

C'est pour que j'ai utilisé:

@media (max-width: 768px) {

            header {

                flex-direction: column;

                text-align: center;
				
            }
