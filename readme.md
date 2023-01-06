# les fichiers interessants sont :

* config.yml (on y indique l'export en json pour algolia, les clés pour l'API autocomplete.js)
* list.algolia.twig pour générer le fichier json (à adapter avec ce qu'on souhaite avoir comme éléments pour la recherche et dans la barre d'autocomplète)
* page.html.twig, j'ai ajouté un include pour mettre la barre de recherche.
* partials/algolia.html.twig, c'est le fichier qui contient la barre d'autocomplète. La version commentée fonctionne, mais c'est une ancienne version a priori, le code plus haut est la nouvelle solution, mais je n'ai pas encore affiché les réponses.
