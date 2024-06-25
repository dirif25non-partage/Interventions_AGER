Champs
******************************************

La liste des champs apparait ci-dessous avec des informations supplémentaires pour certains champs.

N° Inter DiRIF

N° Inter CEI 

CEI  
===
Le tableau ci-dessous indique le nombre d'enregistrements par CEI et par mois

.. csv-table::
   :header: Pc,CEI,23-07,23-08,23-09,23-10,23-11,23-12,24-01,24-02,24-03,24-04,24-05
   :width: 100%

    Est,Brie-Comte-Robert,142,94,120,136,154,128,119,131,124,111,140
    Est,Champigny,407,416,374,425,391,416,377,387,411,409,389
    Est,Rosny,128,3,2,2,0,42,143,129,206,208,331
    Est,Rozay en Brie,12,9,10,12,14,15,10,22,5,0,0
    Est,Villeparisis,158,103,149,101,146,118,153,180,168,190,195
    Nord,Eragny,263,7,240,281,272,336,250,217,244,296,263
    Nord,Saint-Denis,221,2,0,0,0,1,0,1,338,270,138
    Ouest,Fontenay,109,5,152,167,188,110,121,108,119,67,99
    Ouest,Nanterre,261,262,364,382,416,365,365,351,354,248,306
    Ouest,Orgeval,60,84,63,65,36,0,37,0,22,61,40
    Ouest,Rocquencourt-Boulogne,0,0,0,0,74,397,360,405,410,252,320
    Sud,Ablis,46,30,47,62,49,61,28,42,50,39,33
    Sud,Chevilly-Larue,365,366,335,344,363,312,336,325,345,385,351
    Sud,Jouy-en-J.,379,325,366,430,292,0,0,0,64,87,46
    Sud,Jouy-en-J. (Jouy),0,0,0,19,148,282,245,297,302,132,249
    Sud,Jouy-en-J. (Plaisir),0,0,0,0,0,108,106,55,28,191,204
    Sud,Orsay,289,296,290,268,254,273,214,207,253,245,235
    Sud,Villabé,352,315,341,328,323,310,277,290,294,279,287

On constate que des données sont manquantes pour certains mois/CEI.

En ce qui concerne le CEI de Jouy-en-Josas, les deux sites ont été distingués en 2024.


Auteur 

Date d'appel
=============
Ce champ comme le champ suivant est renseigné pour toutes les lignes de la table. 
On a considéré qu'il fournissait la date de l'intervention.

Heure d'appel 
=================
On peut s'interoger sur l'appel dont il s'agit. 

Comme l'OST est identifié comme l'origine de l'appel dans 78% des interventions (voir ci-dessous), il s'agit souvent de l'appel de l'OST au RI, car l'OST a la consigne d'appeler le RI en priorité.

Toutefois comme dans 10% des interventions, l'origine de l'appel est identifiée comme RI, force est de constater que l'appel renseigné n'est pas évident à identifier.

Origine de l'appel
====================
Le tableau ci-dessous indique le nombre d'enregistrements par CEI et par mois
En réalité le champs **Origine de l'appel** prend plus de 600 valeurs. On a donc regroupé de nombreuses valeurs dans le champs **autre**.


.. csv-table::
   :header: Pc,CEI,OST,Police,RI,Dépanneurs,Gendarmerie,Autre
   :width: 100%

      Est,Brie-Comte-Robert,1184,4,120,2,1,88
      Est,Champigny,3260,2,590,51,0,499
      Est,Rosny,1074,1,87,2,0,30
      Est,Rozay en Brie,104,0,4,0,0,1
      Est,Villeparisis,1126,5,185,1,2,342
      Nord,Eragny,1785,292,218,151,52,171
      Nord,Saint-Denis,794,19,125,15,0,18
      Ouest,Fontenay,455,13,178,278,33,288
      Ouest,Nanterre,3042,17,419,2,0,194
      Ouest,Orgeval,461,0,0,0,1,6
      Ouest,Rocquencourt-Boulogne,2103,19,47,0,0,49
      Sud,Ablis,407,0,28,1,2,49
      Sud,Chevilly-Larue,3003,2,471,17,0,334
      Sud,Jouy-en-Josas,1786,0,58,2,0,143
      Sud,Jouy-en-Josas (site de Jouy),1502,0,53,1,1,117
      Sud,Jouy-en-Josas (site de Plaisir),616,0,29,0,1,46
      Sud,Orsay,1680,245,382,18,0,499
      Sud,Villabé,2821,7,414,9,14,131

Dans certains CEI, aucun appel n'a pour origine la police alors qu'ailleurs, le taux peut atteindre 20%.

Les appels des dépaneurs se concentrent sur 3 CEI ce qui parait improbable si tout les CEI code les données selon les mêmes règles.

Il y a donc des marges de progrès sur la compréhension de ce champ par les agents qui saisissent les données.

Axe 
=======
Le champ Axe ne prend que 57 valeurs. Elles sont ci-dessous classée par ordre décroissant d'occurences.  

'A86', 'N104', 'A13', 'A4', 'N12', 'A6', 'A15', 'N118', 'A6b', 'A12',
       'A10', 'A104', 'A6a', 'A3', 'N184', 'A14', 'A1', 'N10', 'N385', 'N2',
       'A115', 'N3', 'N4', 'N13', 'N14', 'N406', 'N315', 'A126', 'N19', 'N186',
       'A140', 'N7', 'N6', 'A106', 'N449', 'A103', 'N330', 'N1104', 'N441',
       'N440', 'N36', 'N486', 'A16', 'N306', 'N20', 'N191', 'N1013', 'N188',
       'N192', 'N37', 'N105', 'N1', 'N446', 'N337', 'RD310', 'RD31', 'N1014'

Le codage n'est pas le même que dans SIRIUS qui distingue un plus grand nombre d'axes. La liaison entre les deux tables demandera donc un transformation de ce champ, d'un coté, de l'autre ou des deux cotés.

Sens
===========
Le champ Sens prend 22 valeurs :

'Y', 'W', 'INT', 'EXT', 'W,Y', 'INT,EXT', 'Y,W', 'EXT,INT', 'W,EXT',
       'INT,W', 'W,Y,INT,EXT', 'Y,EXT', 'W,INT', 'INT,Y', 'EXT,W', 'Y,INT',
       'EXT,Y', 'Y,W,INT,EXT', 'INT,EXT,W,Y', 'Y,INT,W', 'EXT,INT,Y,W',
       'W,INT,EXT,Y'

Les 4 premières valeurs qui sont des *Sens simpes* représentent 95% des interventions.

Dans SIRIUS, le codage des *Sens multiples* est très diférent. Il y a au maximum 2 sens dans la table des événements SIRIUS.

On considère que le travail sur ces cas minoritaire n'est pas prioritaire.

Localisation 
===============
Dans de nombreux cas, la localisation nous renseigne sur le PR et l'Abscisse mais ce n'est malheureusement pas toujours le cas.

On a considéré que les notations suivantes sont équivalentes :

* 3+500
* 3.500
* 3,500
* 3-500
* 30500
* PR 3+500
* pr 3.500
* Pr 3,500
* TUNNEL DE NNN 3.500
...



Voies                                           2
Heure de début                                  2
Heure de fin                                    2
Type d'intervention                             2
Précision niveau 1                              2
Précision niveau 2                              2
Observations                                    2
Présence du RI                                  2
DDP                                             2
Commune                                         2
Horaire d'arrivée sur le lieu d'intervention    2
Horaire du départ du lieu d'intervention        2
Moyens humains                                  2
Moyens matériels                                2
État de la chaussée                             2
Conditions météo                                2
Intervenants                                    2
Circonstances                                   2
Actions réalisées                               2
Présence du tiers responsable                   2
Véhicules impliqués                             2
Agents                                          2








