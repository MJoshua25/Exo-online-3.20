# Exo-online-3.20
  exercice pour les etudiants python online N3.20
# Methode de travail
1. => créer un repositorie github nommé exo_NaN-3.20
2. => mettre le repos en privé
3. => m'ajouter en tant que collaborateur
# Code de conduite
Vous aller traiter tout les exos que je vais données dans des fichiers différents  et les ajouter à votre repos exo_NaN-3.20 avant le samedi 28/03/2020 23h59min59s. Aussi, vous devez nommer les fichiers comme le nom de l'exercice.

## Exercice 1
  Initialisez deux entiers : a = 0 et b = 10.
  Écrire une boucle affichant et incrémentant la valeur de a tant qu’elle reste inférieure
  à celle de b.
## Exercice 2
Écrire une autre boucle décrémentant la valeur de b et affichant sa valeur si elle est
impaire. Boucler tant que b n’est pas nul.
## Exercice 3
Écrire une saisie filtrée d’un entier dans l’intervalle 1 à 10, bornes comprises. Affichez
la saisie.
## Exercice 4
Affichez chaque caractère d’une chaîne en utilisant une boucle for.
## Exercice 5
Affichez chaque élément d’une liste en utilisant une boucle for.
## Exercice 6
Affichez les entiers de 0 à 15 non compris, de trois en trois, en utilisant une boucle for
et l’instruction range().
## Exercice 7
Utilisez l’instruction break pour interrompre une boucle for d’affichage des entiers
de 1 à 10 compris, lorsque la variable de boucle vaut 5.
## Exercice 8
Utilisez l’instruction continue pour modifier une boucle for d’affichage de tous en-
tiers de 1 à 10 compris, sauf lorsque la variable de boucle vaut 5.
## Exercice 9
Utilisez une exception pour calculer, dans une boucle évoluant de -3 à 3 compris, la
valeur de sin(x)/x.
## Exercice 10
Écrire une fonction cube qui retourne le cube de son argument.
Écrire une fonction volumeSphere qui calcule le volume d’une sphère de rayon r fourni
en argument et qui utilise la fonction cube.
Tester la fonction volumeSphere par un appel dans le programme principal.
## Exercice 11
Écrire une fonction maFonction qui retourne f(x)= 2X^3 +X -5.
Écrire une procédure tabuler avec quatre paramètres : fonction, borneInf, borneSup
et nbPas. Cette procédure affiche les valeurs de fonction, de borneInf à borneSup,
tous les nbPas. Elle doit respecter borneIn < borneSup.
## Exercice 12
Écrire une fonction somme avec un argument « tuple de longueur variable » qui calcule
la somme des nombres contenus dans le tuple.
Tester cette fonction par des appels avec différents tuples d’entiers ou de flottants.
## Exercice 13
Écrire une fonction unDictionnaire avec un argument « dictionnaire de longueur variable », et qui affiche son argument.
## Exercice 14
définir la liste : liste =[17, 38, 10, 25, 72], puis effectuez les actions suivantes :
  * triez et affichez la liste ;
  * ajoutez l’élément 12 à la liste et affichez la liste ;
  * renversez et affichez la liste ;
  * affichez l’indice de l’élément 17 ;
  * enlevez l’élément 38 et affichez la liste ;
  * affichez la sous-liste du 2è au 3è élément ;
  * affichez la sous-liste du début au 2eélément ;
  * affichez la sous-liste du 3è élément à la fin de la liste ;
  * affichez la sous-liste complète de la liste ;
  * affichez le dernier élément en utilisant un indiçage négatif.
## Exercice 15
Écrire un module de calcul des racines du trinôme réel : ax^2 +bx Åc.
Le module définit une fonction trinome avec les trois paramètres du trinôme, a, b et
c. La fonction doit retourner un tuple dont le premier élément est le nombre de racines
du trinôme (0, 1 ou 2), et les autres éléments sont les racines éventuelles.
Testez votre fonction avec les trois jeux de valeurs suivantes : 1,-3,2, 1,-2,1 et 1,1,1.
## Exercice 16
Définir une classe Rectangle avec un constructeur donnant des valeurs (longueur et
largeur) par défaut et un attribut nom = "rectangle", une méthode d’affichage et
une méthode surface renvoyant la surface d’une instance.
Définir une classe Carre héritant de Rectangle et qui surcharge l’attribut d’instance :
nom = "carré".
Dans le programme principal, instanciez un Rectangle et un Carre et affichez-les.
## Exercice 17
Un permis de chasse à points remplace désormais le permis de chasse traditionnel.
Chaque chasseur possède au départ un capital de 100 points. S’il tue une poule il perd
1 point, 3 points pour 1 chien, 5 points pour une vache et 10 points pour un ami. Le
permis coûte 200 euros.
Écrire une fonction amende qui reçoit le nombre de victimes du chasseur et qui renvoie
la somme due.
Utilisez cette fonction dans un programme principal qui saisit le nombre de victimes
et qui affiche la somme que le chasseur doit débourser.
## Exercice 18
Un programme principal saisit une chaîne d’ADN valide et une séquence d’ADN va- ▹
lide (« valide » signifie qu’elles ne sont pas vides et sont formées exclusivement d’une
combinaison arbitraire de "a", "t", "g" ou "c").
Écrire une fonction valide qui renvoie vrai si la saisie est valide, faux sinon.
Écrire une fonction saisie qui effectue une saisie valide et renvoie la valeur saisie sous
forme d’une chaîne de caractères.
Écrire une fonction proportion qui reçoit deux arguments, la chaîne et la séquence et
qui retourne la proportion de séquence dans la chaîne (c’est-à-dire son nombre d’oc-
currences).
Le programme principal appelle la fonction saisie pour la chaîne et pour la séquence
et affiche le résultat.
Exemple d’affichage :
Il y a 13.33 % de "ca" dans votre chaîne.
## Exercice 19
Écrire une fonction conv() qui reçoit deux paramètres, une température et un entier
n, et qui retourne la conversion Celsius->Fahrenheit (n = 1), ou Fahrenheit->Celsius
(n = 2).
Rappel : TF = 32 + 1.8 * TC
## Exercice 20
Fonction renvoyant plusieurs valeurs sous forme d’un tuple.
Écrire une fonction minMaxMoy qui reçoit une liste d’entiers et qui renvoie le minimum,
le maximum et la moyenne de cette liste. Le programme principal appellera cette fonc-
tion avec la liste : [10, 18, 14, 20, 12, 16].
## Exercice 21
Un tableau contient n entiers (2 < n < 100), tous compris entre 0 et 500. Vérifier qu’ils
sont tous différents.
## Exercice 22
Saisir un entier entre 1 et 3999 (pourquoi cette limitation ?). L’afficher en nombre ro-
main.
## Exercice 23
Améliorer le script précédent en utilisant la fonction zip().
## Exercice 24
L’utilisateur donne un entier n entre 2 et 12, le programme donne le nombre de façons
de faire n en lançant deux dés.
