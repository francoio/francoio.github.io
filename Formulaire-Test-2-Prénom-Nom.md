---
title: "Formulaire de réponse pour le test 2"
output: pdf_document
---
Abdoul Azize Yougbare
** **





##### Question 1

* Calculer la probabilité de battre un record à l'épreuve $m$

###### Réponse : 

** **

##### Question 2

* Donner l'espérance de $N$ pour $n = 27$. 

###### Réponse : 

** **

##### Question 3

* Calculer ${\rm E}[Y_n]$.

###### Réponse : 

** ** P(U1<U2)=L'union sur k variant dans [0.1] des probabilités :P(U1=k∩U2>k)=P(U1=k)P(U2>k)=1-k
car les deux lois sont independante 
En integrant sur [0,1] on a bien P(U1<U2)=0.5
** ** P(U1<U2<U3)= L'union sur k variant dans [0.m]et sur m variant dans [0.1]des probabilités:P(U1=k∩U3=m∩k<U2<m)=m-k
 En integrant deux fois on obtient  P(U1<U2<U3)=1/6.
** ** E[Yn]=∑i=1n−1E[Xi]= (n-1)E[X1]=(n-1)P(U1<U2)=0.5(n-1)


##### Question 4

* Calculer la valeur de la variance Var$[Y_3]$.

###### Réponse : 

** **

##### Question 5

* Calculer Var$[Y_n]$ pour tout $n \geq 2$.

###### Réponse : 

** ** V[X1]=0.25
** ** Cov(X1,X2)=-0.0833
** ** V[Y3]=1.33


##### Question 6

* Combien de tirages suffisent pour qu'avec une probabilité supérieure à 0.99, $A_{n-1}$ soit proche de la valeur 1/2 à $10^{-2}$ près. 

###### Réponse : 

** **On ontient l'expression demandée en utilisant la formule de developpement du carré d'une somme, et en remarquant que pour i<j :Cov(Xi,Xj) est nulle dès que j=i+2 car dès lors Xiet Xj n'ont plus de dependance.
** ** Il faut que n valent au moins:11939

##### Question 7

* Déterminer la valeur de $c$.



###### Réponse : 

** ** c=10


##### Question 8

* Déterminer la fonction de répartition de la variable $Y$. Donner sa valeur au point $t = 2/3$. 

###### Réponse : 

** **La fonction de repartition de Y est t^5
** **En t=2/3, elle vaut:0.00823


##### Question 9


* Ecrire un algorithme de simulation d'un couple de densité $f(x,y)$.  

###### Réponse : 

** **

##### Question 10


* On pose $Z =  X Y$. Déterminer la densité de la loi de la variable $Z$.
   
###### Réponse : 


** ** 


