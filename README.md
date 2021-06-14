# MappingJournals
Ce repository a été créé dans le cadre d'un travail effectué pour le séminaire TAIS de l'EHESS

===================================================================================================

# Objectifs du travail 
En travaillant sur des revues médicales en situation coloniale, les contributeurs aux revues 

Pour cela nous avons réalisé une carte 

===================================================================================================
# Organisation du repository

## 
> ``
> `data` : L'ensemble des Jupyer Notebooks et données m'ayant permis de créer la carte
> `export` : les exports `shapefile` de la carte QGIS


===================================================================================================
# Sources utilisées 


- [x ] <a href="https://github.com/medialab/GeoPolHist.git"> GeoPolHist </href> : 
- [x ] <a href="https://github.com/medialab/GeoPolHist.git"> GeoPolHist </href> : Base de données historique du médialab. 
- [x ] <a href = "https://www.geonames.org" >Geonames </href> 


| Nom                             	| Acteurs produisant la BDD       	| Intérêt<br>de la base de données                                                        	| Désavantages                                                                                	| Utilisé pour                                                    	|
|---------------------------------	|---------------------------------	|-----------------------------------------------------------------------------------------	|---------------------------------------------------------------------------------------------	|-----------------------------------------------------------------	|
| GeoPolHist<br><br>Taille : 1228 	| Médialab – Sciences Po          	| Base de<br>donnée historique <br>des statuts d'entités géopolitiques<br>au fil du temps 	| En anglais <br>(problème de désambiguisation)                                               	| Fond de<br>carte<br><br>Désambiguisation<br><br>Géolocalisation 	|
| IREL<br><br>Taille : 14570      	| Archives nationales d’Outre-mer 	| Grande<br>quantité de lieux-dit géolocalisés                                            	| Déséquilibré en fonction<br>des territoires                                                 	| Désambiguïsation<br><br>Géolocalisation                         	|
| Historical National Boundaries  	| Université du Minnesota         	| Comporte des fonds de cartes à plusieurs dates clés                                     	| Manque de précision                                                                         	| Fond de<br>carte                                                	|
| Geonames                        	| Collaboratif                    	| Contient à peu près toutes les<br>géolocalisation                                       	| L’API n’ayant pas fonctionné, nous <br>avons du rechercher les informations<br>manuellement 	| Géolocalisation                                                 	|
