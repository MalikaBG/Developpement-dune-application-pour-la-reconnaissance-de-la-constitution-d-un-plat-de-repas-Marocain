Suivant cette approche, le processus de reconnaissance passe par deux phase princpales :
	*Premièrement : la phase de segmentation implémentée à l'aide d'un algorithme basé sur les graphes et optimisée par une comparaison de textures calculées avec la matrice de co-occurence des niveaux de gris.
	*Deuxièmement : La classification "One vs All" implémentée à l'aide des réseaux de neuronnes covolutifs
Le notebook contient l'implémentation de la segmentation avec le test sur l'image d'un "tajine" ainsi que le test du classificateur de "pomme de terre".
La base de donnée compressée contient 3 dossiers contenant chacun les images du même aliments extraites des images des plats marocains.
