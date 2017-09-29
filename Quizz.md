## Qu'est ce qu’un navigateur ?

```
C'est un logiciel conçu pour consulter le web.



```

________________________________________________________________________________________

## Définissez l’ensemble HTML/CSS/JavaScript et leur utilités.


```
HTML : c'est le code source de la page.
CSS : sert à mettre en page le code HTML.
Javascript : sert à animer la page.

```
________________________________________________________________________________________


## Qu’est-ce qu’un élément HTML ? Un attribut ?

```
Un élément HTML c'est tout ce qui est contenu entre la balise ouvrante et fermante <html></html>.
Un attribut c'est toutes les informations supplémentaires utiliser sur un élément pour définir la manière de fonctionner.


```
________________________________________________________________________________________


## Dans quels cas utilisez-vous des id au lieu des classes (et vice-versa) ?


```
Il vaut mieux utiliser les "id" si il y en a qu'un. Les "classes" sont utilisées si elles sont répétées au sein du code.



```
________________________________________________________________________________________


## Qu’est-ce que EcmaScript ?

```




```

________________________________________________________________________________________

## Pourquoi est-il important de bien indenter vos fichiers ?

```




```
________________________________________________________________________________________


## Quelle est la différence entre margin et padding ? 

```
margin : marges extérieures pour séparer plusieurs blocs.
padding : marges intérieures. 



```

________________________________________________________________________________________


## Citez au moins 3 types de positionnement en CSS et expliquer leurs rôles.

```
position relative : peut décaler un élément par rapport à sa position de départ.
position absolute: il n'est plus lier aux autre éléments.
position fixe: l'élément est fixe est ne bougera pas même si on scroll vers le bas.

```
________________________________________________________________________________________

## Qu’est-ce qu’une variable ?

```
Une variable stocke le type de données (chaîne de caractèrezs, tableau...) qui est utile lors de la fonction.



```
________________________________________________________________________________________


## Citez le plus de types JavaScript possible et définissez les rapidement.


```




```
________________________________________________________________________________________


##  À quoi sert le mot-clef “if” ?

```
If exprime une condition au sein d'une fonction.



```

________________________________________________________________________________________

##  Définissez l’objet XHR en JavaScript, son abréviation. À quoi sert-il ?


```




```

________________________________________________________________________________________

## Qu’est-ce qu’une requête HTTP ? 

```
C'est ce qui va permettre au client de discuter avec un serveur connecté au réseau



```
________________________________________________________________________________________


## Quelle sont les deux types de requêtes permettant de récupérer et d’envoyer de la donnée sur un serveur HTTP ?

```




```

________________________________________________________________________________________

## À quoi sert le Header d’une requête ? Le “Content-Type” ?

```




```
________________________________________________________________________________________


## Donnez au moins 3 codes de réponse HTTP et définissez les.


```
200 : OK
300 : redirection
400 : erreur



```
________________________________________________________________________________________


## Définissez les rôles de Scrum Master et Product Owner.


```
Le Product Owner est la personne qui communique entre l'équipe de developpeurs et le client.
Le Scrum Master est la personne qui gère le planning des sprint, de la revue des sprint et de la retrospective. Il fait appliquer l'utilisation des planning des sprints.



```
________________________________________________________________________________________


## Citer 4 commandes utilisées avec GIT et expliquer leurs rôles.
```
Git checkout -b : création de branche et basculement vers celle-ci.
Git branch : Voir sur quelle branche on se trouve.
Git add . :  ajouter tous les fichiers ou dossiers sur la branche.
Git commit -m "message": message pour dire ce qu'on a modifier/ajouter sur la branche



```
________________________________________________________________________________________


## Expliquer le code suivant et indiquer le résultat retourné par la fonction.

```
function counter(){
        const sentence = "Validation de la première phase";
        const words = sentence.split(' ');
        let count = 0;


        for (let i = 0; i < words.length; i++) {
            var word = words[i];
            count += word.length;
        }
        return count;
}
```
```
La fonction counter a été créer avec deux constantes (variables qui ne changeront jamais):
	sentence
	word
Il y a aussi une variable let pour dire que le compteur part de 0.
Une boucle a été ouverte. Entre paranthèses la boucle a été initialiser:
	index = 0
	la longueur de l'index
	à chaque boucle, on rajoute 1 à l'index.
Une variable a été créer qui a pour valeur la consante "words" avec la valeur de l'index.
A chaque tour de compteur, on indique la longueur de la variable word.
A chaque tour, le compteur retourne la longueur du mot.

```
________________________________________________________________________________________


## Algo 

Ecrire l’algorithme d’une fonction prenant en paramètre 2 arguments : le premier est une chaîne de caractère et le second correspondant au caractère recherché. Cette fonction retourne le nombre de fois que le caractère recherché est rencontré dans la chaîne de caractères.
Ex. 
   * chaîne : ‘examen’, caractère : ‘x’ => 1
   * chaîne : ‘wild code school’, caractère : ‘w’ => 1



```
let String1 = 'ceci est une chaîne de caractères';
let car = x;
let char = w;
function algo (car, char)



```


