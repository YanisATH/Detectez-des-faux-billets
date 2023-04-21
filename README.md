# Detectez-des-faux-billets
L’Organisation nationale de lutte contre le faux-monnayage, ou ONCFM,
est une organisation publique ayant pour objectif de mettre en place des
méthodes d’identification des contrefaçons des billets en euros. Dans le
cadre de cette lutte, nous souhaitons mettre en place un algorithme qui
soit capable de différencier automatiquement les vrais des faux billets.

# Objectifs
Lorsqu’un billet arrive, nous avons une machine qui consigne l’ensemble
de ses caractéristiques géométriques. Au travers de nos années de lutte,
nous avons observé des différences de dimensions entre les vrais et les
faux billets. Ces différences sont difficilement notables à l’œil nu, mais une
machine devrait sans problème arriver à les différencier.
Ainsi, il faudrait construire un algorithme qui, à partir des caractéristiques
géométriques d’un billet, serait capable de définir si ce dernier est un vrai
ou un faux billet.

# Modèle de données
Dimensions géométriques
Nous disposons actuellement de six informations géométriques sur un
billet :
● length : la longueur du billet (en mm) ;
● height_left : la hauteur du billet (mesurée sur le côté gauche, en
mm) ;
● height_right : la hauteur du billet (mesurée sur le côté droit, en mm) ;
● margin_up : la marge entre le bord supérieur du billet et l'image de
celui-ci (en mm) ;
● margin_low : la marge entre le bord inférieur du billet et l'image de
celui-ci (en mm) ;
● diagonal : la diagonale du billet (en mm).
