Eugénie Ragon

# QUESTIONS

## Définissez ce qu'est une variable

Les variables sont des "cases" où sont stockés une donnée.
Elles sont stockées en mémoire vive (RAM).
Les variables ne peuvent contenir que des nombres ou des lettres (sans accents).
Par convention une variable commence par une minuscule et l'on écrit chaque débuts de mots par une majuscule (exemple : JeSuisUneVariable)

## Quels sont les trois types principaux de variables

Les 3 types principaux de variables sont : 
- les nombres (1, 2, 3, 4 ...)
- les chaînes de caractères ("Je suis une chaîne de caractères" ou 'Je suis aussi une chaîne de caractères' ou `ça aussi c'est une chaîne`),
- les booléens 

## Combien de valeurs différentes peut prendre une variable de type booléen ?

Une variable de type booléen peut prendre 2 valeurs : true ou false (vrai ou faux).


## Que se passe-t-il si l'on execute le code suivant ? Comment cela s'appelle-t-il ?

```
let debut = 0;

while (debut > 0) {
    console.log("Je continue");
    debut += 1;
}

console.log("J'arrête");
```

Lorsque l'on execute le code suivant, le message qui va s'afficher sera "J'arrête". 
Ce type de code est une boucle.
La valeur déclaré pour debut est de 0. Et l'on dit que tant que debut est strictement supérieur à 0 on affichera "Je continue". A chaque tours de boucle, on ajoute +1 à début.
Lorsque la valeur de debut est inférieure à 0 on affiche le message "J'arrête".
Hors debut n'atteind jamais de valeur strictement supérieur à 0 donc un seul message "J'arrête" s'affiche.


## Si je veux stocker une suite d'éléments dans une variable, que dois-je utiliser ?

Pour stocker une suite d'éléments dans une variable on doit utiliser un tableau. Un tableau peu contenir des nombre, des cahînes de caractères et des booléens.

## Qu'est ce que les paramètres d'une fonction ? Qu'est ce que le retour (return) d'une fonction ?

Les paramètres d'une fonction sont les éléments qui vont entrer dans la fonction. 
Le paramètre "return" permet de retourner une valeur de la fonction. C'est-à-dire la valeur que l'on veut extraire de la fonction. On le met dans le corps de la fonction.