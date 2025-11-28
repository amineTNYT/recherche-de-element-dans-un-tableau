
🔍 Recherche Dichotomique - Explication Simple
📖 C'est quoi ?

La recherche dichotomique, c'est comme chercher un mot dans le dictionnaire :

📖 On ouvre le dictionnaire au milieu

⬅️ Si le mot cherché est avant, on cherche dans la première moitié

➡️ Si le mot cherché est après, on cherche dans la deuxième moitié

🔁 On répète jusqu'à trouver

⚠️ La Règle Importante
Le tableau DOIT être trié (croissant ou décroissant)

✅ Bon exemple (tableau trié) :



### python
T = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100]
✅ Bon exemple (tableau trié) : la recherche **marche**

T = [50, 10, 90, 20, 70, 30, 100, 40, 80, 60]


→❌ Les nombres sont dans le désordre(tableau mélangé), la recherche **ne marche pas**

🎯 Comment ça marche ?
Cherchons le nombre 70 dans :
[10, 20, 30, 40, 50, 60, 70, 80, 90, 100]

Étape 1 :
 On regarde au milieu → 50

➡️ 50 < 70 → on cherche dans la partie droite

Étape 2 :
 Nouveau milieu → 80
⬅️ 80 > 70 → on cherche dans la partie gauche
Étape 3 :
✅ On trouve 70 ! Succès


[_recherche dichotomique_algo.docx](https://github.com/user-attachments/files/23421580/_recherche.dichotomique_algo.docx)

