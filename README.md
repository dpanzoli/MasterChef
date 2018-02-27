# MasterChef
Projet MasterChef pour les Master GAME

*Les développements alternatifs de ce projet sont visibles dans les autres branches*

## Branche recette_auto
Dans cette branche, la recette (i.e. les interactions) est simplement stockée sous forme de règles et un script automatise le déroulement du jeu. Les règles permettent de stipuler des préconditions et des post-conditions, sous la forme de changement d'états des objets. 
* Préconditions: de la forme A (interaction réflexive) ou AxB (interaction entre 2 objets). A et B représentent des couples <objet/état>. Une interaction est possible si A et B sont associés ET si les états dans le monde corresopndent aux états pré-requis.
* Postconditions : de la forme AxBxC..xZ. Où chaque lettre est un couple <objet/état>. L'application des post-conditions met chaque objet dans l'état désiré. La modification graphique est automatique car les états sont associés à des représentations.

![](screenshot.png)
