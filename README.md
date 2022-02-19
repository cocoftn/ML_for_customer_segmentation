# ML_for_customer_segmentation

## Objectif
Ce projet est divisé en deux partie :
La première partie consiste, à partir de données d'achats d'un site internet, à identifier des segments de clientèle selon le comportement d'achat global des clients. 
La seconde partie consiste à classifier les clients selon la/les classes correspondantes. Pour cela, nous avons recours aux algorithmes Xgboost, arbres de décision, forêt aléatoire et régression logistique. Nous effectuons une comparaisons des ces 5 classifieurs.

## Data
### Source
Le fichier data_orders_2017.csv qui se trouove à la racine de ce répertoire. 
### Description
Les données contiennent les variables suiantes :
* "customer" : la colonne représentant le numéro client 
* "order" : la colonne indiquant le numéro de commande, unique 
* "total_items" : la colonne indiquant le nombre d'articles achetés lors d'une commande 
* "discount%" : la colonne indiquant la remise globale affectée à cette commande
* "weekday" : la colonne indiquant le jour (en numéro) de la commande. 1 étant le lundi et 7 étant le dimanche
* "hour" : la colonne indiquant l'heure de la commande 
* "Food%" : la colonne indiquant la part d'articles de la section nourriture parmi les articles de la commande 
* "Fresh%" : la colonne indiquant la part d'articles de la section frais (nourriture fraîche incluant viande, poissons, fruits et légumes) parmi les articles de la commande 
* "Drinks%" : la colonne indiquant la part d'articles de la section boissons parmi les articles de la commande 
* "Home%" : la colonne indiquant la part d'articles de la section maison parmi les articles de la commande 
* "Beauty%" : la colonne indiquant la part d'articles de la section beauté et soins parmi les articles de la commande 
* "Pets%" : la colonne indiquant la part d'articles de la section animaux parmi les articles de la commande 


