# MappingJournals
Ce repository a été créé dans le cadre d'un travail effectué pour le séminaire TAIS de l'EHESS. 

## Objectifs du travail 


Par ce rendu, nous avons souhaité considérer la répartition géographique des contributions de deux revues (Les "Annales d'hygiène et de médecine coloniale" et les "Archives de médecine navale")afin d’en saisir les territoires d’intérêt. En effet, la publication dans une revue officielle de mémoires originaux et de rapports effectués à l’administration nous renseigne sur ce que les autorités ministérielles estimaient comme pertinent pour la gouvernance des territoires.

Nous avons concentré notre étude sur les titres de contributions originales des années s’écoulant de 1898 à 1908 comme échantillon pour mettre en place une méthodologie de cartographie des contributions faites aux revues. Si cette période débute avec la création de l’une d’entre elles (les AHMC), elle se termine par la création de la Société de pathologie exotique dont nous étudions aussi le Bulletin dans le cadre de notre mémoire. Cette société a eu pour effet de capter les principaux médecins coloniaux et de la marine ainsi que de promouvoir la recherche bactériologique et en parasitologie, introduisant alors un nouveau rapport au terrain.

## Organisation du repository

* `carto` : les cartes créées grâce au projet QGIS
* `data` : L'ensemble des Jupyer Notebooks et données m'ayant permis de créer la carte
  * Les cinq jupyter notebooks du projet ainsi que le module associé
  * Les dossiers contenant les principales sources qui m'ont permises de créer la carte : `GeoPolHist-202103` ; `HistNatBoundaries` ; `IREL`
  * Les outputs de mes Notebooks (ayant majoritairement servis comme input entre Norbooks) ainsi que les dossiers contenant les input provenant d'autres sources
* `export` : les exports `shapefile` de la carte QGIS
* `LGrumbach-Rendu-TAIS.qgz` : Projet QGIS de notre rendu
* `LGrumbach-TAIS.pdf` : descriptif de l'objectif et de la démarche du présent rendu

## Sources utilisées 


| Nom                             	| Acteurs produisant la BDD       	| Intérêt<br>de la base de données                                                        	| Désavantages                                                                                	| Utilisé pour                                                    	|
|---------------------------------	|---------------------------------	|-----------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------------------------------------	|
| <a href="https://github.com/medialab/GeoPolHist.git"> GeoPolHist </a><br><br>Taille : 1228 	| Médialab – Sciences Po          	| Base de<br>donnée historique <br>des statuts d'entités géopolitiques<br>au fil du temps 	| En anglais <br>(problème de désambiguisation)                                               	| Fond de<br>carte<br><br>Désambiguisation<br><br>Géolocalisation 	|
| <a href="http://anom.archivesnationales.culture.gouv.fr/geo.php?ir=">IREL</a><br><br>Taille : 14570      	| Archives nationales d’Outre-mer 	| Grande<br>quantité de lieux-dit géolocalisés                                            	| Déséquilibré en fonction<br>des territoires                                                 	| Désambiguïsation<br><br>Géolocalisation                         	|
| <a href="https://www.arcgis.com/home/item.html?id=85e35d64d67f425c94ebca45dad6568a">Historical National Boundaries</a>  	| Université du Minnesota         	| Comporte des fonds de cartes à plusieurs dates clés                                     	| Manque de précision                                                                         	| Fond de<br>carte                                                	|
| <a href = "https://www.geonames.org" >Geonames </a>                         	| Collaboratif                    	| Contient à peu près toutes les<br>géolocalisations mais trop <br>ambigu                                       	| L’API n’ayant pas fonctionné, nous <br>avons du rechercher les informations<br>manuellement 	| Géolocalisation                                                 	|
