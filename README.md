En tant que joueur de D&D, je souhaiterai pouvoir configurer un jet de dés en rentrant une chaîne simple de caractères. Un lancer de dés est soumis aux règles suivantes :

- Un lancer peut être décrit par la formule suivante :
  <NombreDeLancers>[d]<ValeurDuDé>[+-]<Modificateur>\ (ex: "2d6+1")
-  Le "+ ou -" et le modificateur sont optionnels (ex : "3d8" est une formule valable)
-  Le résultat d'un lancer ne peut pas être négatif (sauf dans le cas où la formule est incorrecte), en cas de résultat négatif le résultat est 0
-  Un lancer basé sur une mauvaise formule retournera toujours la valeur -1
-  Un lancer ne peut pas avoir une valeur négative pour le nombre de lancers et pour la valeur du dé, si c'est le cas la formule est considérée incorrecte et le lancer retournera -1 (ex : "-1d8" est une formule incorrecte)
-  Il existe trois façons de faire un lancer: 
      Normal : un seul lancer est effectué
      Avec Avantage : 2 lancers sont faits et le meilleur lancer est pris (pour 3d8 on lancera deux fois 3d8 et on prendra le meilleur résultat)
      Avec Désavantage : 2 lancers sont faits et le moins bon est pris
-  les modificateurs sont appliqués après le/les lancer(s) !
