Périmètre des installation concernées
******************************************

.. toctree::
   :hidden:
   :maxdepth: 3

   33_CosWin


* De quelles installations parle-t-on ?
* Comment peut on représenter le parc ?
* Faut-il définir plusieurs niveaux de sensibilité, 
en identifiant en particulier les installations qui entrent dans les CME des tunnels ?

CosWin comporte environ 10 000 équipements liés aux réseaux électrique et de données. 
:doc:`On consacre une page à la description des données disponibles dans CosWin<33_CosWin>`.


Réseau électrique
====================
Le plus souvent, les équipements sont alimentés directement par des points de livraison (PDL) 
du réseau ENEDIS sans interaction entre les services de la DIRIF.

Cependant, certains noeuds du RTHD et les équipements SIRIUS Ouest dépendent d'un réseau électrique propre à la DIRIF.

Les principaus outils d'identification des éléments du réseau électrique sont les schémas synoptiques.


Réseau de données
======================
Le réseau de données comporte des boucles qui assurent des redondances. On peut donc désactiver un noeud sans perdre 
la connectivité entre tous les équipements.
Néanmoins, dès qu'il y a plusieurs désactivations simultanées, il peut y avoir des pertes de communication. 
Les travaux doivent donc être coordonnés et tenir compte des défaillances existantes suite à des aléas.

