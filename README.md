# Formatif formel

C'est le temps de mettre en pratique ce que vous avez appris en Design Web depuis le début de la session. 

**Téléchargez projet de base disponible sur Github Classroom.** Votre enseignant vous fournira le lien.

## Étape 1 : Assurer la conformité des documents reçus

- [x] Le fichier index.html fourni n'est pas conforme. Apportez les corrections nécessaires pour ==assurer la validité du document== selon les standarts W3C en conservant l'affichage initial. 
- [x] Établissez le lien entre le document HTML et les styles CSS. 

## Étape 2 : Mise en forme

Aidez ce pauvre Pikachu à replacer son visage.

- Vous pouvez modifier le html et le css comme bon vous semble.
- Comme l'image en background est fixe, le visage de Pikachu devra l'être aussi (Si on redimensionne l'écran, il restera en place)

Dans ma version, j'ai utilisé les propriétés **position**, **top** et **left** pour disposer mon conteneur "principal" dans la page. Il y a un exemple commenté dans le fichier css du projet de base sous le id **texte_css**.

``````css
#texte_css {
	position: absolute; /* Permet de positionner le texte sans tenir compte des autres éléments */
	top: 600px; /* Positionne le texte à 600px du haut de la page */
	left: 20px; /* Positionne le texte à 20px de la gauche de la page */
	font-size: 3em;
}
``````

## Remise et correction

Nous allons effectuer la remise sur GitHub Classroom et une autocorrection ensemble au prochain cours.

Voici les critères que nous utiliserons : 

- Validité de la structure HTML (2)
- Validité de la liaison entre le document HTML et les styles CSS (2)
- Positionnement des éléments du visage (6) 
