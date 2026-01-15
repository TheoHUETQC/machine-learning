programation : on donne des intructions a la machine et elle donne une output
machine learning : la machine s entraine pour quelle reponde mieux

nettoyer un data set :

si on a des Nan (manque d'info) il faut le nettoyer.
on a des methodes :
- medianne, moyenne pour les int
- prendre le resultat au dessus ou en dessous pour les booleans

si on a un chiffre qui est de forme str (ex 2000€) :
- on retire les symbole bizarre et on le transforme en chiffre
- on peut egalement le laisser si c'est pour du tri...

si on a des lignes qui sont dubliqué il faut les enlever

si on a des lignes dubliquées il faut les enlever


on va utiliser kaggle pour trouver des datas set.

csv = separer avec virgules
df = data frame 

df.info() donne :
"dtypes:" liste de quel types sont nos colonnes 


deux type de machine learning (supervised et unsupervised learning)

supervised = on donne le data set et on attend une reponse qu on comparera a l'etiquette

(
unsupervised = il connait pas la reponse 
clustering : on a des données et on veut que la machine les lies entre elle sans forcement qu'il y est detiquette
dimensionality reduction : il doit virer les infos pas importante et garder les importantes
)

pour le supervised 2 types de problèmes :
- regression (on cherche un nombre)
- classification (si on cherche a classer, oui ou non)

features et target 
y a des collonnes inutiles mais on les utiliseras quand meme
- les collones en input c'est les features X
- les collonnes en output c'est les targets Y

