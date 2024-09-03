# Analyse des logements sociaux dans les Hauts-de-France (au 1er janvier 2023)

*(Réalisée en Août 2024)*

![Logo Hauts-de-France](Logo_Hauts-de-France.png "Logo Hauts-de-France")

## Dataset

Lien vers le Dataset : https://dreal.statistiques.developpement-durable.gouv.fr/parc_social/2023/hauts_de_france/RPLS_2023_32_hauts_de_france_export_donnees_illustrations_2023-12-08.xlsx

## Contenu

Données RPLS : https://www.statistiques.developpement-durable.gouv.fr/catalogue?page=datafile&datafileRid=f3c2f2cb-8fb1-40fd-8733-964247744c9a (Données publiques)

Liste des colonnes : 

CONV /
NUMCONV /
DATCONV /
NEWLOGT_CODE /
NEWLOGT_LIBELLE /
CUS /
DPEDATE /
DPEENERGIE /
DPESERRE /
SRU_EXPIR /
SRU_ALINEA /
CODSEGPATRIM /
LIBSEGPATRIM /
PMR_CODE /
PMR_LIBELLE /
PLG_VOIE /
EPSG /
X /
Y /
PLG_QP /
PLG_IRIS2022_CODE /
PLG_IRIS2022_LIBELLE /
PLG_ZUS /
PLG_ZFU /
PLG_QVA /
QUALITE_VOIE /
QUALITE_NUMERO /
QUALITE_XY /
DISTANCE_PRECISION /
QUALITE_QP /
QUALITE_IRIS /
QUALITE_ZUS /
QUALITE_ZFU /
QUALITE_QVA /
COMAQP /
COMAZUS /
COMIRIS /
UU2020 /
AAV2020 /
ZE2020 /

## Overview

Le Dashboard ainsi que le Notebook (en version pdf car trop lourd à uploader sur GitHub) est une synthèse de l’état du parc social au 1er janvier 2023 en Hauts-de-France.

Les données sont comparées sur 10 ans, ce qui inclut la période Covid-19 qui a fortement impacté les différents indicateurs présentés dans cette publication.

Les données sont actualisées tous les ans, en fin d'année civile.

# Méthode d'analyse

- Récupération du fichier ;
- Nettoyage : valeurs manquantes, doublons, réparation des caractères spéciaux (accents...) qui apparaissaient mal dans le fichier (encodage UTF-8), ajout/suppression de colonnes, formatage ;
- Identification des premières informations : nombre de lignes/colonnes, moyennes, médianes, valeurs min/max, etc. ;
- Analyse par thématiques ;
- Data visualisation avec Python (Matplotlib, Seaborn), puis réalisation d'un tableau de bord avec Power BI.

## Observations après analyse

![Overview 1](Page_2.png "Overview 1_2")
![Overview 2](Page_3.png "Overview 2_2")
![Caractéristiques du Parc Social](Page_3.png "Caractéristiques du Parc Social")
![Mises en service 2022](Page_4.png "Mises en service 2022")
![Ancienneté et Etat Energétique](Page_5.png "Ancienneté et Etat Energétique")
![Catégories de Financement](Page_6.png "Catégories de Financement")
![Typologie des Logements](Page_7.png "Typologies des Logements")

📌 Près de 600 000 logements sont répertoriés dans ce fichier. Affichage du nombre de logements par département.
