Comparaison des interventions AGER et des événements SIRIUS, en 2024
######################################################################

Les deux tables ont des tailles comparables :

* Interventions :43 386 lignes
* Evénements : 132 000 lignes pour 40 671 événements différents

Conditions de liaison entre les tables
*****************************************
Pour mettre en correspondance les éléments des 2 tables, on doit utiliser la localisation et l'horodatage.

Localisation
===============
Pour la localisation, on retrouve les notions d'axe, de sens et de PR dans les 2 tables mais :

* les axes ne sont pas toujours désignés de la même manière.
* les notions de sens sont différentes (en particulier au niveau des accès et des échangeurs)
* la codification des PR est très différente selon l'auteur des enregistrements d'interventions.

On a créé des tables de correspondance qui permettent dans la majorités des cas de traduire les codifications dans un langage commun.  
Les correspondances ne sont cependant pas complètes et augmenter le taux de correspondance signifie allonger la table. C'est un travail assez laborieux et qui produit des rendements décroissants.

Il en résulte qu'environ 10 à 20 % des enregistrements qui pourraient être liés par une analyse fine ne le sont pas dans les résultats produit ici.

Le PR étant la données la moins bien renseignée sur les interventions, on fera des analyses avec ou sans cette variable.

Horodatage
================
Pour la date et l'heure, la liaison est plus simple même ne les heures saisies dans les deux tables ne sont pas de la même nature. En prenant une plage de +/- une heure ont pense établir les liens nécessaires. Le risque que 2 événements interviennent sur le même Axe à quelques heures d'interval est faible.

Résultat des liaisons
=======================
En faisant une liaison intégrant le PR, on trouve un événement SIRIUS pour 15 000 des 43 000 interventions.
Sans prendre en compte le PR, le nombre d'appariements passe à 26 000.

Enlever une dimension facilite les correspondances, mais cela entraine que l'on fait aussi apparaitre de fausses correspondances.

Déclinaison par CEI
======================
Les taux de liaisons peuvent dépendre de nombreux facteurs liés à des considérations géographiques et à la manière dont les données sont enregistrées dans la base.

On peut observer la manière dont ces taux dépendent des variables de la base. On fait ci-dessous, par exemple, une analyse par CEI.

.. csv-table::
   :header: CEI,Nbr d'interventions,Taux avec PR,Taux sans PR
   :width: 100%

  Brie-Comte-Robert,1429,41,68
  Champigny,4987,49,75
  Rosny,2747,37,68
  Rozay en Brie,37,5,27
  Villeparisis,2232,31,47
  Eragny,2946,19,44
  Saint-Denis,2929,33,63
  Fontenay,1087,1,37
  Nanterre,4308,39,74
  Orgeval,559,43,76
  Rocquencourt-Boulogne,3978,46,73
  Ablis,515,20,35
  Chevilly-Larue,4340,19,31
  Jouy-en-Josas,414,26,49
  Jouy-en-Josas (site de Jouy),2568,25,52
  Jouy-en-Josas (site de Plaisir),1714,23,49
  Orsay,2865,43,68
  Villabé,3731,46,76






