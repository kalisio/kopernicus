
## *Service Urgences*

### <img src="/images/logourgence.png" width="30"/> **Rapid Mapping** - *catastrophes naturelles et humaines*

  Quatres produits pour la **gestion en temps réel** des événements:
 
| Nom du produit | Description                                    | Type             | Délai |
|----------------|------------------------------------------------|------------------|-------|
| Reference      | Etat des lieux avant événement                 | Vecteur          | 10h   |
| First estimate | Première estimation, rapide des dommages       | Vecteur          | 2h    |
| Delineation    | Estimation avancée des dommages                | Vecteur(contour) | 7h    |
| Grading        | Estimation détaillée et gradation des dommages | Vecteur          | 10h   |
  
![Carte de contour d’impact d’une inondation](/images/rapid_mapping_inondation.jpg)
<div align="center"> Delineation: Inondation de la rivière Ebro, Espagne, produite  le 03/03/2015 © Union Européenne </div>
  
::: danger Contraintes:
 
- Un unique organisme français habilité à activer ce service : le Centre opérationnel de gestion interministérielle des crises (C.O.G.I.C)
- Etre utilisateur associé dans la gestion de crises (non précisé)
:::
 
 [Vue d’ensemble](https://emergency.copernicus.eu/mapping/ems/service-overview)

 </br>
 
### <img src="/images/logoclimate.png" width="30"/>**EFAS** (European Flood Awareness System) - *Inondations*

Le site de l’[EFAS](https://www.efas.eu/) permet d'accéder à des **datasets** et **flux WMS-T** comportant des données sur les flux hydrologiques. Ce site est conçu pour fournir des aperçus des inondations en cours et prévues en Europe jusqu’à 10 jours à l’avance.

 ![Carte pour télécharger les flux WMS ](/images/wms_efas.PNG)


L’accès aux données est différent selon le fait d'être partenaire ou non :
- *Partenaire* : Accès au temps réel, prévisions, notifications, interface web…
- *Non partenaire* : Pas d’accès au temps réel, archive et perspectives saisonnières

::: tip  Note 
Le [GLOFASS](https://www.globalfloods.eu/) est l’équivalent mondial.
::::

Toutes les données disponibles pour ces deux instances sont répertoriées sur le site [CDS](https://cds.climate.copernicus.eu/#!/home) (climate data store). Leur accés est soumis à une inscription préalable.


 ![CDS](/images/CDS.PNG)

Cette bibliothèque est rattachée à **Copernicus** et l’**ECMWF** (Centre européen des prévisions météorologiques à moyen terme).

Sur le site de [ECMWF](https://www.ecmwf.int/), les données accessibles au public sont les mêmes que sur l’EFAS, mais il est possible d'acheter une licence commerciale pour avoir accès aux données suivantes :

- Catalogue des produits temps réel ECMWF
- Catalogue des produits d'archive ECMWF
- Liste des produits graphiques de prévision à moyen terme ECMWF

Le téléchargement des données sur ces différentes plateformes s’effectue en direct ou avec des requêtes API, en format GRIB, NetCDF-4, ou par flux WMS-T, en passant sur une plateforme web, ou sur un logiciel de SIG.

 </br>
 
### <img src="/images/logourgence.png" width="30"/> EFFIS - *incendies*

Le système européen d’information sur les incendies de forêt (EFFIS: European Forest Fire Information System) soutient les services chargés de la protection des forêts contre les incendies dans les pays de l’UE et fournit des informations actualisées et fiables sur les incendies de forêt en Europe.

Un certain nombre d’informations sont disponibles via EFFIS [Situation actuelle](https://effis.jrc.ec.europa.eu/static/effis_current_situation/public/index.html) :

- **Prévision du danger:** informations à jour sur la saison des incendies actuelle en Europe et dans la région méditerranéenne. Cela comprend aujourd’hui des cartes météorologiques des dangers d’incendie et des prévisions jusqu’à 9 jours, des cartes quotidiennes mises à jour des points chauds et des périmètres d’incendie.

![Prevision](/images/prevision.PNG)



- **Evaluation rapide des dommages:** Les incendies actifs sont situés sur la base des anomalies thermiques. Les algorithmes comparent la température d’un feu potentiel avec la température de la couverture terrestre qui l’en est; si la différence de température est supérieure à un seuil donné, l’incendie potentiel est confirmé comme un feu actif ou un « point chaud ». EFFIS utilise la détection active des incendies fournie par les FIRMS (Fire Information for Resource Management System) de la NASA .

::: tip MODIS:
Le capteur MODIS, à bord des satellites TERRA et ACQUA, identifie les zones au sol nettement plus chaudes que leur environnement et les signale comme des feux actifs. La résolution spatiale du pixel actif de détection d’incendie de MODIS est de 1 km.
::::
::: tip VIIRS:
à bord du Nasa/NOAA Suomi National Polar-orbiting Partnership (SNPP) utilise des algorithmes similaires à ceux utilisés par MODIS pour détecter les incendies actifs. Les produits d’incendie actifs VIIRS complètent la détection des incendies MODIS et offrent une meilleure résolution spatiale. La résolution spatiale du pixel actif de détection d’incendie pour VIIRS est de 375 m. De plus, VIIRS est capable de détecter les petits incendies et peut aider à délimité les périmètres des grands incendies en cours.
::::
![FeuActif](/images/feu_actif.PNG)

## <img src="/images/atmosphere.svg" width="30"/> *Service atmosphère*

Le service atmosphère surveille en permanence la qualité de l'air en Europe et dans le monde en utilisant les observations satellites et au sol ainsi que des modèles numériques avancés. Les données sont mises à jour **quotidiennement** et **prévisionnelle** sur 96h via des modèles numériques. 
[Qualité de l’air](https://atmosphere.copernicus.eu/air-quality)

<div align="center"><b>Carte mondiale de la concentration en ozone</b></div> <img src="/images/ozone2.png"/> 
<img align="left" src="/images/legende_ozone2.png"/> Concentration en ozone(DU) de la colonne d'air  
</br></br>


<div align="center"> Copernicus Atmosphere Monitoring Service (CAMS)©</div>

Le téléchargement des données s’effectue en direct ou avec des requêtes API, au format GRIB ou NetCDF-4.

## <img src="/images/logosentinel.png" width="30"/>*Données Satellites*
Deux portails permettent d’accéder aux images satellites depuis le site de Copernicus.

![ESA ](/images/esa_logo2.png)
- Le portail de l’**ESA (Agence Spatiale Européenne)** : [SCI Hub](https://scihub.copernicus.eu/)   
Il donne accès aux images capturées par les satellites Sentinel-1, Sentinel-2, Sentinel-3 *(uniquement la partie étude terrestre)*.  
L’ESA gère également le Copernicus Space Component Data Access (CSCDA), ce portail permet d’accéder aux missions contributives fournies au programme Copernicus selon des conditions commerciales. Les droits d’accès et le téléchargement sont réservés aux autorités publiques, aux projets européens et aux services Copernicus.
*Plus d’informations sur les [Catégories d’utilisateurs](https://spacedata.copernicus.eu/web/cscda/copernicus-users/user-categories) et les [Droits d’accès](https://spacedata.copernicus.eu/web/cscda/copernicus-users/access-rights)*  


![EUMETSAT ](/images/eumetsat_logo.png)
- Le portail de **EUMETSAT (Organisation Européenne pour l’Exploitation des Satellites météorologiques)** : [CODA](https://coda.eumetsat.int/#/home)    
Il permet d’obtenir les images issues du satellite Sentinel-3 *(partie étude marine uniquement)*, et prochainement celles des Sentinels-4, 5 et 6 lorsque ceux-ci seront opérationnels. 
Les données produites à partir des autres satellites de EUMETSAT, notamment Metop et Meteosat sont également accessibles à partir de l’**EUMETSAT Data Store**. 

![interface ](/images/Capture.png)

L’ensemble de ces données sont disponibles **gratuitement** à condition d’avoir préalablement **créer un compte** sur chacune de ces plateformes. Ces données sont ensuite visualisables ou téléchargeables librement (via la plateforme ou une [API](https://scihub.copernicus.eu/userguide/APIsOverview?TWIKISID=aed5ac444ba4a7049ae59fc68c4a522a)).   
::: tip Disponibilité des données
- Au maximum 3 heures après acquisition : **Near Real Time** (NRT)
- 2 à 3 jours après acquisition : **Short Time Critical** (STC)
- Environ 1 mois après acquisition : **Non Time Critical** (NTC)
::::

## *Autres portails d’accès aux données*  
Les données du programme Copernicus sont également accessibles via diverses autres plateformes de diffusion proposant le plus souvent des services supplémentaires, tels que les DIAS ou PEPS.

### **Data and Information Access Services (DIAS)**  

Cinq consortiums ont été mandatés par l’Europe pour organiser les données copernicus.
![Schéma récapitulatif des DIAS](/images/DIAS.jpg)  

Ils offrent les services de Copernicus Core ainsi que les accès aux images satellites sentinel dans le cadre du programme Copernicus. Ils ont également des accès à d’autres programmes tels que ceux de la NASA (landsat), du CNRS (pléiades), de GeoSud (spot 6/7) dont des données payantes.



### <img src="/images/peps.png" width="60"/> **Plateforme d’Exploitation des Produits Sentinel (PEPS)**


Plateforme française de distribution des données Sentinel du programme Copernicus, PEPS est opérée par le **CNES (Centre National d’Etudes Spatiales)**. <img src="/images/cnes_logo.png" width="50"/>  
Les images satellites issues des Sentinel-1, 2, et 3 y sont disponibles et peuvent être visualisées librement.  
  
![peps_interface](/images/Capture_peps.png)  

La **création d’un compte** donne accès au téléchargement (direct ou via API) ainsi qu'à un centre de traitement. *Informations supplémentaires [Rubrique Web Services & Scripts](https://peps.cnes.fr/rocket/plus/plus.htm)*  

Le **Centre de Traitements** permet d’accéder à une galerie de traitements réalisables **en ligne**. Les images traitées sont ensuite téléchargeables ou accessibles via un **service WPS**.   
::: details Liste des traitements    
- Ortho-rectification S1 sur la grille S2
- Corrections atmosphérique
- Compositions colorées
- NDVI et LAI
- Extractions de bandes, de bursts, de métadonnées, de la polarisation
- Medicis
:::
*Une description des Traitements disponibles ainsi que des informations supplémentaires concernant le service WPS sont disponibles [Rubrique Traitements PEPS](https://peps.cnes.fr/rocket/plus/plus.htm)*







