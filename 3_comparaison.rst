Comparaison des interventions AGER et des événements SIRIUS, en 2024
######################################################################

Les deux tables ont des tailles comparables :

* Interventions :43 386 lignes
* Evénements : 132 000 lignes pour 40 671 événements différents

Pour mettre en correspondance les éléments des 2 tables, on doit utiliser la localisation et l'horodatage.

Pour la localisation, on retrouve les notions d'axe, de sens et de PR dans les 2 tables mais :

* les axes ne sont pas toujours désignés de la même mannière.
* les notions de sens sont différentes
* la codification des PR est très différente selon l'auteur des enregistrements d'interventions.

On a créé des tables de correspondance qui permettent dans la majorités des cas de traduire les codifications dans un langage commun.  
Les correspondances ne sont cependant pas complètes et augmenter le taux de correspondance signifie alonger la table. C'est un tavail assez laborieux et qui produit des rendements décroissants.

Il en résulte qu'environ 10 % des enregistrements qui pourraient être liés par une analyse fine ne le sont pas dans les résultats produit ici.


Pour la date et l'heure, la liaison est plus simple même ne les heures saisies dans les deux tables ne sont pas de la même nature. En prenant une plage de +/- une heure ont pense établir les liens nécessaires. Le risque que 2 événements interviennent sur le même Axe à quelques heures d'interval est faible.
