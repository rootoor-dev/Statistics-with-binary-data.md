# Données factices ou binaires ou d'empreintes digitales

**Une variable binaire** ***(x)*** est une variable qui ne contient qu'une seule des deux valeurs qui sont **0** et **1**.

Étant donné que tous les xi sont égaux à 0 ou 1, la somme de toutes les observations équivaut à compter le nombre de 1. La formule suivante pour la moyenne de l'échantillon révèle qu'elle est égale à la proportion de l'échantillon.

```
- somme(xi) = count_of_1 = count(xi=1) = total de 1 = N(xi=1)
- moyenne(xi) = μ = somme(xi)/n = N/n = la proportion (p) d'un échantillon qui est égale à 1
- variance(xi) = p*q = p(1-p)
- p = proportion(xi=1) = probabilité(xi=1) = moyenne en %
- la valeur moyenne de la population pour une variable binaire est la proportion de fois où la variable binaire est égale à 1 ou la probabilité que xi=1 ==> moyenne(%) = proportion

- mode = max(N(x=0),N(x=1)) , si N(xi=0) < N(xi=1) donc mode = N(xi=1) sinon mode = N(xi= 0)
- médiane = proportion_de_1_arrondie = round(moyenne)
- variance = p*q = p(1-p) = moyenne(1-moyenne)
- écart-type = σ = pow(variance,2) = (variance)²
 
 ** μ signifie ; σ sd

EXEMPLE:

Soit ces données binaires:

personne1, 1 0 0 0 0
personne2, 1 0 0 0 0
personne3, 1 1 0 0 0
personne4, 1 1 1 0 0
personne5, 1 1 1 1 0
personne6, 1 1 1 1 1

----------- calcul ------------
somme(personne1)= N(x=1) = 1+0+0+0+0 = 1
somme(personne2)= N(x=1) = 1+0+0+0+0 = 1
somme(personne3)= N(x=1) = 1+1+0+0+0 = 2
somme(personne4)= N(x=1) = 1+1+1+0+0 = 3
somme(personne5)= N(x=1) = 1+1+1+1+0 = 4
somme(personne6)= N(x=1) = 1+1+1+1+1 = 5


moyenne(personne1)= N(x=1)/n = (1+0+0+0+0)/n = 1/5 ~ 0,2
moyenne(personne2)= N(x=1)/n = (1+0+0+0+0)/n = 1/5 ~ 0,2
moyenne(personne3)= N(x=1)/n = (1+1+0+0+0)/n = 2/5 ~ 0,4
moyenne(personne4)= N(x=1)/n = (1+1+1+0+0)/n = 3/5 ~ 0,6
moyenne(personne5)= N(x=1)/n = (1+1+1+1+0)/n = 4/5 ~ 0,8
moyenne(personne6)= N(x=1)/n = (1+1+1+1+1)/n = 5/5 ~ 1,0


proportion(personne1)=moyenne(%) = 0,2 ~ 20%
proportion(personne2)=moyenne(%) = 0.2 ~ 20%
proportion (personne3) = moyenne (%) = 0,4 ~ 40%
proportion(personne4)=moyenne(%) = 0,6 ~ 60%
proportion (personne5) = moyenne (%) = 0,8 ~ 80%
proportion(personne6)=moyenne(%) = 1.0 ~ 100%


mode(personne1)= max(N(x=0),N(x=1)) = max(4,5) = 5
mode(personne2)= max(N(x=0),N(x=1)) = max(4,5) = 5
mode(personne3)= max(N(x=0),N(x=1)) = max(3,2) = 3
mode(personne4)= max(N(x=0),N(x=1)) = max(2,3) = 3
mode(personne5)= max(N(x=0),N(x=1)) = max(1,4) = 4
mode(personne6)= max(N(x=0),N(x=1)) = max(0,5) = 5

médian(personne1)= proportion = rond(0.2) ~ 0
médian(personne2)= proportion = rond(0.2) ~ 0
médian(personne3)= proportion = rond(0.4) ~ 0
médian(personne4)= proportion = rond(0.6) ~ 1
médiane (personne5) = proportion = ronde (0,8) ~ 1
médian(personne6)= proportion = rond(1.0) ~ 1

variance(personne1)= p*q = 0,2*(1-0,2) ~ 0,16
variance(personne2)= p*q = 0,2*(1-0,2) ~ 0,16
variance(personne3)= p*q = 0,4*(1-0,4) ~ 0,24
variance(personne4)= p*q = 0,6*(1-0,6) ~ 0,24
variance(personne5)= p*q = 0,8*(1-0,8) ~ 0,16
variance(personne6)= p*q = 1.0*(1-1.0) ~ 0

écart_type(personne1)= pow(variance,2) = 0,16² = 0,256
écart_type(personne2)= pow(variance,2) = 0,16² = 0,256
écart_type(personne3)= pow(variance,2) = 0,24² = 0,0576
écart_type(personne4)= pow(variance,2) = 0,24² = 0,0576
écart_type(personne5)= pow(variance,2) = 0,16² = 0,256
standard_deviation(person6)= pow(variance,2) = 0² = 0



somme


```
NB : Pour estimer une **probabilité** qu'un événement se produise, on peut utiliser des méthodes statistiques standard utilisant une variable de résultat binaire.

# ENTROPIE
**H = - SUM(pi.log(pi))**, où **pi** est la ***probabilité d'un état i d'un système***, et **H** est le symbole traditionnel de l'**entropie**.

Un exemple de système est un ensemble de variables binaires.

Dans le cas particulier d'une variable binaire : **H = - (p log p + (1-p) log (1-p))**.






# SOURCES

- [https://murraylax.org/rtutorials/binprop.html](https://murraylax.org/rtutorials/binprop.html)
- [https://stats.oarc.ucla.edu/wp-content/uploads/2016/02/p046.pdf](https://stats.oarc.ucla.edu/wp-content/uploads/2016/02 /p046.pdf)
- [https://mylittleneuron.com/2021/01/12/traitement-des-donnees-incompletes-ou-imputation/](https://mylittleneuron.com/2021/01/12/traitement-des-donnees-incompletes-ou-imputation/)
