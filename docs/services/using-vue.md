
## **INONDATIONS**

### *Débit fluvial et données historiques associées du système européen de sensibilisation aux inondations*
![Debit fluvial entre 1991 et 2019](/images/Effas1.png)

:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données fournit des séries chronologiques hydrologiques quotidiennes modélisées en quadrillage, forcées avec des observations météorologiques. L'ensemble de données est une représentation cohérente des variables hydrologiques les plus importantes dans le domaine du système européen de sensibilisation aux inondations (EFAS). La résolution temporelle est jusqu'à 30 ans de séries chronologiques modélisées.
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/efas-historical?tab=overview)  
Accès gratuit mais besoin d’une inscription au service EFAS  
Service WMS  
Téléchargement par API
:::
::: tab Métadonnées lazy
|                            |                                                                                                                                                             |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Type**                   | Raster                                                                                                                                                      |
| **Format**                 | NetCDF                                                                                                                                                      |
| **Résolution temporelle**  | L'indicateur est dérivé de la série quotidienne et représente des statistiques sur une longue période. En tant que tel, il n'a pas de résolution temporelle |
| **Résolution spatiale**    | 50km, 10km and secteur de 215 km2 en moyenne                                                                                                   |
| **Mise à jour**            | Maximum 1 mois                                                                                                                                              |
| **Délai de disponibilité** |                                                                                                                                                             |
|                            |                                                                                                                                                             |


:::
::: tab Variables lazy
| Name                                 | Units  | Description                                                                                                                                                                                                                                                                                                                             |
|--------------------------------------|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge in the last 24 hours | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 24-hour time step.                                                                                                                          |
| River discharge in the last 6 hours  | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 6-hour time step.                                                                                                                           |
| Snow depth water equivalent          | kg.m-2 | The value represent the mass of water per square meter if all the snow in the grid box would be melted. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step.                                                                                                    |
| Soil depth                           | m      | Soil depth, positive downward for each of the three soil layers at each grid point. The value is relative from the top of the land surface to the bottom of each layer respectively.                                                                                                                                                    |
| Volumetric soil moisture             | m3.m-3 | Amount of water in a cubic meter of soil valid for the cell grid at the corresponding soil layer. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step. For more documentation on the calculation of the volumetric soil moisture we refer to the documentation. |
| Orography                            | m      | Static file - dem.nc, mean elevation above sea level for each pixel in the EFAS domain. To download, see link under Documentation                                                                                                                                                                                                       |
| Upstream area                        | m2     | Static file - upArea.nc, upstream area for the point in the river network. To download, see link under Documentation                                                                                                                                                                                                                    |


:::  

::: tab Licence lazy
[Licence Copernicus](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)

:::
::::
</br></br>  
    
### *Débit fluvial et données prévues associées par le système européen de sensibilisation aux inondations*
![Domaine d’étude de l’EFAS](/images/Effas2.png)

:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données fournit des séries temporelles hydrologiques modélisées quadrillées forcées avec des prévisions météorologiques à moyen terme. Les données sont une représentation cohérente des variables hydrologiques les plus importantes dans le domaine du système européen de sensibilisation aux inondations (EFAS). La résolution temporelle correspond à des prévisions sous-quotidiennes à haute résolution.
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/efas-forecast?tab=overview)   
Accès gratuit mais besoin d’une inscription au service EFAS  
Service WMS  
Téléchargement par API  
:::
::: tab Métadonnées lazy
|                            |                                |
|----------------------------|--------------------------------|
| **Type**                   | Raster                         |
| **Format**                 | GRIB  NetCDF-4                 |
| **Résolution temporelle**  | 0 à 24h et prévision jusqu'à 15j |
| **Résolution spatiale**    | 5x5km                          |
| **Mise à jour**            | Quotidienne à 00UTC et 12UTC   |
| **Délai de disponibilité** | Un mois                        |
|                            |                                |

:::
::: tab Variables lazy
| Name                                 | Units  | Description                                                                                                                                                                                                                                                                                                                             |
|--------------------------------------|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge in the last 24 hours | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 24-hour time step.                                                                                                                          |
| River discharge in the last 6 hours  | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 6-hour time step.                                                                                                                           |
| Snow depth water equivalent          | kg.m-2 | The value represent the mass of water per square meter if all the snow in the grid box would be melted. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step.                                                                                                    |
| Soil depth                           | m      | Soil depth, positive downward for each of the three soil layers at each grid point. The value is relative from the top of the land surface to the bottom of each layer respectively.                                                                                                                                                    |
| Volumetric soil moisture             | m3.m-3 | Amount of water in a cubic meter of soil valid for the cell grid at the corresponding soil layer. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step. For more documentation on the calculation of the volumetric soil moisture we refer to the documentation. |
| Orography                            | m      | Static file - dem.nc, mean elevation above sea level for each pixel in the EFAS domain. To download, see link under Documentation                                                                                                                                                                                                       |
| Upstream area                        | m2     | Static file - upArea.nc, upstream area for the point in the river network. To download, see link under Documentation                                                                                                                                                                                                                    |

:::  

::: tab Licence lazy
[Licence Copernicus](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)

:::
::::
</br></br> 

### *Prévisions saisonnières du débit fluvial et données associées par le système européen de sensibilisation aux inondations (actuelles - quotidiennes)*
![Prévisions du débit fluvial](/images/Effas3.png)

:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données fournit des séries chronologiques hydrologiques quotidiennes modélisées en quadrillage, forcées avec des prévisions météorologiques saisonnières. L'ensemble de données est une représentation cohérente des variables hydrologiques les plus importantes dans le domaine européen de la sensibilisation aux inondations (EFAS). La résolution temporelle est constituée de prévisions quotidiennes initialisées une fois par mois.

:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/efas-seasonal?tab=overview)  
Accès gratuit mais besoin d’une inscription au service EFAS  
Service WMS  
Téléchargement par API 
:::
::: tab Métadonnées lazy
|                            |                                |
|----------------------------|--------------------------------|
| **Type**                   | Raster                         |
| **Format**                 | GRIB  NetCDF-4                 |
| **Résolution temporelle**  | 0 à 24h  et prévision jusqu'à 215j |
| **Résolution spatiale**    | 10x10km                          |
| **Mise à jour**            | Mensuelle à 00UTC |
| **Délai de disponibilité** | Un mois                        |
|                            |                                |

:::
::: tab Variables lazy
| Name                                 | Units  | Description                                                                                                                                                                                                                                                                                                                             |
|--------------------------------------|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge in the last 24 hours | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 24-hour time step.                                                                                                                          |
| River discharge in the last 6 hours  | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 6-hour time step.                                                                                                                           |
| Snow depth water equivalent          | kg.m-2 | The value represent the mass of water per square meter if all the snow in the grid box would be melted. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step.                                                                                                    |
| Soil depth                           | m      | Soil depth, positive downward for each of the three soil layers at each grid point. The value is relative from the top of the land surface to the bottom of each layer respectively.                                                                                                                                                    |
| Volumetric soil moisture             | m3.m-3 | Amount of water in a cubic meter of soil valid for the cell grid at the corresponding soil layer. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step. For more documentation on the calculation of the volumetric soil moisture we refer to the documentation. |
| Orography                            | m      | Static file - dem.nc, mean elevation above sea level for each pixel in the EFAS domain. To download, see link under Documentation                                                                                                                                                                                                       |
| Upstream area                        | m2     | Static file - upArea.nc, upstream area for the point in the river network. To download, see link under Documentation                                                                                                                                                                                                                    |

:::  

::: tab Licence lazy
[Licence Copernicus](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)

:::
::::
</br> </br> 
### *Redevisions du débit fluvial et données associées par le système européen de sensibilisation aux inondations*

![EFAS4](/images/efas4.PNG)


:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données fournit des séries chronologiques hydrologiques modélisées quadrillées, forcées avec des reponditions météorologiques de moyenne à sous-saisonnière. Les données sont une représentation cohérente des variables hydrologiques les plus importantes dans le domaine du système européen de sensibilisation aux inondations (EFAS). La résolution temporelle est de 20 ans de rediffusions sous-quotidiennes initialisées deux fois par semaine (lundi et jeudi).
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/efas-reforecast?tab=overview)   
API WMS  
Accès gratuit

:::
::: tab Métadonnées lazy

|                            |                                                                                                                            |
|----------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Type**                   | Raster                                                                                                                     |
| **Format**                 | NetCDF                                                                                                                     |
| **Résolution temporelle**  | Les rediffusions sont initialisées à 00 UTC les lundis et jeudis avec un pas de temps de 6 heures et un délai de 46 jours. Données du 3 janvier 1999 au 30 décembre 2018. |
| **Résolution spatiale**    | Europe 10km                                                                                                                |
| **Mise à jour**            |  Les révisions EFAS sont publiées à intervalles réguliers sur CDS, généralement avec chaque mise à niveau EFAS majeure.    |
| **Délai de disponibilité** |                                                                                         |


:::
::: tab Variables lazy

| Nom                   | Unité  | Description                                                                                                                                                                                                                                                                                                                             |
|-----------------------------|---------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge             | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over the given time step, which is either 6 or 24 hours.                                                                                              |
| Snow depth water equivalent | kg.m-2  | The value represents the mass of water per square meter if all the snow in the grid box would be melted. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step.                                                                                                   |
| Soil depth                  | m       | Soil depth, positive downward for each of the three soil layers at each grid point. The value is relative from the land surface to the bottom of each layer respectively.                                                                                                                                                               |
| Volumetric soil moisture    | m3.m-3  | Amount of water in a cubic meter of soil valid for the cell grid at the corresponding soil layer. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step. For more documentation on the calculation of the volumetric soil moisture we refer to the documentation. |



:::
::: tab Licence lazy
[Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/cems-floods.pdf)
:::
::::
</br> </br> 

### *Réévaluations saisonnières du débit fluvial et données associées par le système européen de sensibilisation aux inondations*

![EFAS5](/images/efas5.PNG)


:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données fournit des séries chronologiques hydrologiques journalières modélisées, forcées avec des reponditions météorologiques saisonnières. L'ensemble de données est une représentation cohérente des variables hydrologiques les plus importantes dans le domaine européen de la sensibilisation aux inondations (EFAS). La résolution temporelle est constituée de prévisions quotidiennes initialisées une fois par mois sur la période de re-prévision 1991-2020.
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/efas-seasonal-reforecast?tab=overview)   
API WMS  
Accès gratuit

:::
::: tab Métadonnées lazy
Tableau des metadata
|                            |                                                                                                                                       |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **Type**                   | Raster                                                                                                                                |
| **Format**                 | GRIB and NetCDF                                                                                                                       |
| **Résolution temporelle**  | Les prévisions sont initialisées le premier de chaque mois à 00 UTC et exécutées avec un pas de 24 heures avec un délai de 215 jours. Données du 1er janvier 1991 au 1er octobre 2020|
| **Résolution spatiale**    | 10km                                                                                                                                  |
| **Mise à jour**            | Mise à jour le premier de chaque mois.                                                                                                |
| **Délai de disponibilité** |                                                                                     |



:::
::: tab Variables lazy

| Nom                       | Unité  | Description                                                                                                                                                                                                                                                                                                                             |
|--------------------------------------|--------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge in the last 24 hours | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over each 24-hour time step.                                                                                                                          |
| Snow depth water equivalent          | kg.m-2 | The value represents the mass of water per square meter if all the snow in the grid box would be melted. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step.                                                                                                   |
| Soil depth                           | m      | Soil depth, positive downward for each of the three soil layers at each grid point. The value is relative from the top of the land surface to the bottom of each layer respectively.                                                                                                                                                    |
| Volumetric soil moisture             | m3.m-3 | Amount of water in a cubic meter of soil valid for the cell grid at the corresponding soil layer. The value is instantaneous meaning that it is valid for the last time step of the integration at the issued model time step. For more documentation on the calculation of the volumetric soil moisture we refer to the documentation. |
:::
::: tab Licence lazy
[Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/cems-floods.pdf)
:::
::::
</br> </br> 
### *Indicateurs de quantité d'eau pour l'Europe*

![EFAS6](/images/efas6.PNG)


:::: tabs type:card 
::: tab Description lazy

Cet ensemble de données contient des données modélisées pour le ruissellement de l'eau et l'humidité, le débit des rivières, l'équivalent en eau de la neige, la teneur en eau du sol et d'autres quantités liées à l'eau pour la région européenne. Ces variables ont été calculées dans le cadre d'un contrat de validation de principe destiné à accélérer le flux de travail des analyses d'impact et à simplifier l'adaptation au changement climatique des pratiques de gestion de l'eau à travers l'Europe. Ces quantités ont été modélisées à l'aide de l'Institut météorologique et hydrologique suédois E-HYPE, du modèle VIC de l'Université de Wageningen et des modèles Lisflood du Joint Research Center. Ces modèles fonctionnent à différentes résolutions, ainsi les données sont fournies à différentes résolutions. E-HYPE et Lisflood ont été mis à l'échelle afin de montrer l'ensemble modèle.
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-water-quantity-swicca?tab=overview)  
API WMS  
Accès gratuit  

:::
::: tab Métadonnées lazy
|                            |                                                                                                                                                             |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Type**                   | Raster                                                                                                                                                      |
| **Format**                 | NetCDF                                                                                                                                                      |
| **Résolution temporelle**  | L'indicateur est dérivé de la série quotidienne et représente des statistiques sur une longue période de 1971-2100. En tant que tel, il n'a pas de résolution temporelle |
| **Résolution spatiale**    | Domaine paneuropéen,  Différentes résolutions: 50km, 10km et secteurs de 215 km2 en moyenne                                         |
| **Mise à jour**            |                                                                                                                                                             |
| **Délai de disponibilité** |                                                                                                                                                    |


:::
::: tab Variables lazy

| Nom                    | Unité                          | Description                                                                                                                                                                                                                                     |
|--------------------------|-----------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Aridity 1                | %                                 | Ratio   between potential evapotranspiration and precipitation. Potential   evapotranspiration is the modelled evapotranspiration when there is abundant   water. Aridity 1 values can be larger than 1.                                        |
| Aridity 2                | %                                 | Ratio   between actual evapotranspiration and precipitation. Actual   evapotranspiration is the modelled evapotranspiration computed only with   available water. Aridity 2 cannot normally exceed 1.                                           |
| River flow               | m3.s-1 for the reference period   | Volume   rate of water flow that is transported through a given cross-sectional area.   It is synonymous to river discharge or streamflow.                                                                                                      |
| Snow   water equivalent  | mm for the   reference period     | Amount of water   contained in the snow pack. It can be considered as the depth of water that   theoretically would result if the whole snow pack instantaneously melts. Snow   water equivalent is the product of snow depth and snow density. |
| Soil   water content     | % for the   reference period      | Volume fraction   of soil occupied by water, averaged over those soil layers that provide   moisture for plant transpiration. This term includes all phases of water.                                                                           |
| Unregulated   river flow | m3.s-1 for the reference period   | Volume rate of   water flow that is transported through a given cross-sectional area. It is   synonymous to river discharge or streamflow.                                                                                                      |
| Water   runoff           | mm day-1 for the reference period | Sum of surface   and subsurface runoff to streams for each grid cell or catchment.                                                                                                                                                              |
| Wetness   1              | mm day-1                          | Precipitation   minus potential evapotranspiration. Potential evapotranspiration is the   modelled evapotranspiration when there is abundant water.                                                                                             |
| Wetness 2                | mm   day-1                        | Precipitation   minus actual evapotranspiration. Actual evapotranspiration is the modelled   evapotranspiration computed only with available water.


:::
::: tab Licence lazy
[Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)
:::
::::
</br></br>
### *Indicateurs de qualité de l'eau pour les fleuves européens*

![EFAS7](/images/efas7.PNG)


:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données contient des données modélisées pour les concentrations et les charges de phosphore et d'azote. Les données proviennent du modèle E-HYPE de l'Institut météorologique et hydrologique suédois au niveau des bassins versants pour l'Europe. Ces indicateurs de qualité de l'eau ont été calculés dans le cadre d'un contrat de validation de principe conçu pour accélérer le flux de travail des analyses d'impact et pour simplifier l'adaptation au changement climatique des pratiques de gestion de l'eau à travers l'Europe.
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-water-quality-swicca?tab=overview)  
API WMS  
Accès gratuit  

:::
::: tab Métadonnées lazy
|                            |                                                                                                                                                             |
|----------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Type**                   | Raster                                                                                                                                                      |
| **Format**                 | NetCDF                                                                                                                                                      |
| **Résolution temporelle**  | L'indicateur est dérivé de la série quotidienne et représente des statistiques sur une longue période de 1971-2100. En tant que tel, il n'a pas de résolution temporelle |
| **Résolution spatiale**    | Polygone irrégulier, taille médiane de secteur: 215 km2                                                                                                  |
| **Mise à jour**            |                                                                                                                                                             |
| **Délai de disponibilité** |                                                                                                                                                    |
                                                                                                                                     
:::
::: tab Variables lazy
| Nom                      | Unité                                                            | Description                                                                                              |
|----------------------------|-------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Nitrogen concentrations    | μg/l for the reference period % of change for future periods.     | Mass of nitrogen divided by the volume of water.                                                         |
| Nitrogen loads             | kg for the reference period % of change for future periods.       | Product of the river flow volume and the nitrogen concentrations.                                        |
| Phosphorous concentrations | μg/l for the reference period % of change for the future periods. | Mass of phosphorous divided by the volume of water.                                                      |
| Phosphorous loads          | kg for the reference period % of change for future periods.       | Product of the river flow volume and the phosphorous concentrations.                                     |
| Water temperature          | °C                                                                | In-stream water temperature for the reference period In-stream change of temperature for future periods. |

:::
::: tab Licence lazy
[Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)
:::
::::
</br></br>
### *Indicateurs météorologiques et de neige du tourisme de montagne pour l'Europe de 1950 à 2100 dérivés de réanalyses et de projections climatiques*

![EFAS8](/images/efas8.PNG)


:::: tabs type:card 
::: tab Description lazy
Cet ensemble de données fournit des indicateurs météorologiques et de neige pour l'Europe, caractérisant les conditions d'exploitation des stations de ski d'hiver dans les scénarios climatiques passés et futurs. L'ensemble de données se compose de 39 indicateurs de conditions atmosphériques et de neige calculés de manière similaire pour toutes les régions de montagne en Europe à l'échelle des régions NUTS-3 (Nomenclature des Unités Territoriales pour les Statistiques) et par pas de 100 m d'altitude. Les indicateurs de neige sont générés à l'aide du modèle de manteau neigeux Crocus, un modèle de manteau neigeux multicouche intégré dans le modèle de surface terrestre SURFEX (Surface Externalisée). Afin d'évaluer l'impact du changement climatique, le modèle est exécuté pour quatre scénarios climatiques différents: le climat actuel (appelé "historique") et trois scénarios de trajectoire de concentration représentative (RCP) qui correspondent à un scénario d'émission optimiste où les émissions commencent à diminuer. au-delà de 2020 (RCP2.6), un autre scénario d'émission optimiste où les émissions commencent à baisser au-delà de 2040 (RCP4.5) et un scénario pessimiste où les émissions continuent d'augmenter tout au long du siècle, souvent appelé scénario d'émissions élevées (RCP8.5). Afin de simuler ces scénarios climatiques, le modèle SURFEX est forcé avec des champs atmosphériques fournis par des projections climatiques d'ensemble EURO-CORDEX ajustées (branche européenne de l'expérience de downscaling coordonné). Des modèles climatiques régionaux à échelle réduite par rapport aux modèles climatiques mondiaux sont utilisés pour fournir les indicateurs paneuropéens à haute résolution nécessaires pour évaluer la fiabilité de la neige pour toutes les régions montagneuses d'Europe. En plus des scénarios climatiques, un jeu de données de réanalyse est calculé à l'aide de la réanalyse UERRA.
:::
::: tab Accès lazy
Climate (C3S) : [URL](https://cds.climate.copernicus.eu/cdsapp#!/dataset/sis-tourism-snow-indicators?tab=overview)  
API WMS  
Accès gratuit  

:::
::: tab Métadonnées lazy

|                            |                                                         |
|----------------------------|---------------------------------------------------------|
| **Type**                   | Time series                                             |
| **Format**                 | NetCDF4                                                 |
| **Résolution temporelle**  | données de 1950 à 2100                                                   |
| **Résolution spatiale**    | Unités Territoriales pour les Statistiques(NUTS-3) et pas de 100 m                             |
| **Mise à jour**            | Annuelle, agrégats de 20 à 30 ans|
| **Délai de disponibilité** |                                    |
|                            |                                                         |


:::
::: tab Variables lazy
| Nom                                                                                        | Unité  | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------------------------------------------|--------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Annual amount of machine made snow produced                                                 | kg.m-2 | The total amount of machine made snow for the period August 1st of year N-1 to July 31st of year N, where N is the selected year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| End of the longest period with groomed snow                                                 | day    | Identified longest continuous period from August 1st of year N-1 to July 31st of year N where the snow depth is continuously above 30 cm using a groomed snow simulation. The first date, within this continuous period, meeting the condition "Snow depth >= 30 cm" is the beginning of the season. The last date within this continuous period, meeting this condition, is the end of the season. In case only one date meets the condition, then beginning of season and end of season are attributed this value. In case no date meets the condition (i.e., Snow depth is lower than 30 cm for the entire year), no date is attributed (value of 0). The value assigned is interpreted as the number of days after August 1st of year N-1.                            |
| End of the longest period with managed snow                                                 | day    | Identified longest continuous period from August 1st of year N-1 to July 31st of year N where the snow depth is continuously above 30 cm using a managed (groomed and machine made) snow simulation. The first date, within this continuous period, meeting the condition "Snow depth >= 30 cm" is the beginning of the season. The last date within this continuous period, meeting this condition, is the end of the season. In case only one date meets the condition, then beginning of season and end of season are attributed this value. In case no date meets the condition (i.e., Snow depth is lower than 30 cm for the entire year), no date is attributed (value of 0). The value assigned is interpreted as the number of days after August 1st of year N-1. |
| End of the longest period with natural snow                                                 | day    | Identified longest continuous period from August 1st of year N-1 to July 31st of year N where the snow depth is continuously above 30 cm using a natural snow simulation. The first date, within this continuous period, meeting the condition "Snow depth >= 30 cm" is the beginning of the season. The last date within this continuous period, meeting this condition, is the end of the season. In case only one date meets the condition, then beginning of season and end of season are attributed this value. In case no date meets the condition (i.e., Snow depth is lower than 30 cm for the entire year), no date is attributed (value of 0). The value assigned is interpreted as the number of days after August 1st of year N-1.                            |
| Mean winter air temperature                                                                 | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in November year N-1 to April of year N (inclusive).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Monthly mean air temperature for April                                                      | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in April of year N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Monthly mean air temperature for December                                                   | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in December of year N-1.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Monthly mean air temperature for February                                                   | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in February of year N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| Monthly mean air temperature for January                                                    | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in January of year N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Monthly mean air temperature for March                                                      | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in March of year N.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Monthly mean air temperature for November                                                   | K      | Average of 6-hourly temperature of air at 2 m above the surface of land, sea or in-land waters for all dates in November of year N-1.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Period with high amount of groomed snow                                                     | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow water equivalent >= 120 kg m-2" using a groomed snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with high amount of managed snow                                                     | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow water equivalent >= 120 kg m-2" using a managed (groomed and machine made) snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Period with high amount of natural snow                                                     | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow water equivalent >= 120 kg m-2" using a natural snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with high height of groomed snow                                                     | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 50 cm" using a groomed snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with high height of managed snow                                                     | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 50 cm" using a managed (groomed and machine made) snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Period with high height of natural snow                                                     | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 50 cm" using a natural snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with low height of groomed snow                                                      | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 5 cm" using a groomed snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Period with low height of managed snow                                                      | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 5 cm" using a managed (groomed and machine made) snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Period with low height of natural snow                                                      | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 5 cm" using a natural snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Period with medium amount of groomed snow                                                   | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow water equivalent >= 100 kg m-2" using a groomed snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with medium amount of managed snow                                                   | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow water equivalent >= 100 kg m-2" using a managed (groomed and machine made) snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Period with medium amount of natural snow                                                   | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow water equivalent >= 100 kg m-2" using a natural snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with medium height of groomed snow                                                   | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 30 cm" using a groomed snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with medium height of groomed snow between the fourth and tenth December             | day    | The number of days from December 4 of year N to December 10 of year N (included) fulfilling the condition "Snow depth >= 30 cm" using a groomed snow simulation. Maximum value is 7.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Period with medium height of groomed snow between twenty second December and fourth January | day    | The number of days from December 22 of year N-1 to January 4 of year N (included) fulfilling the condition "Snow depth >= 30 cm" using a groomed snow simulation. Maximum value is 14.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with medium height of managed snow                                                   | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 30 cm" using a managed (groomed and machine made) snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Period with medium height of managed snow between the fourth and tenth December             | day    | The number of days from December 4 of year N to December 10 of year N (included) fulfilling the condition "Snow depth >= 30 cm" using a managed (groomed and machine made) snow simulation. Maximum value is 7.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| Period with medium height of managed snow between twenty second December and fourth January | day    | The number of days from December 22 of year N-1 to January 4 of year N (included) fulfilling the condition "Snow depth >= 30 cm" using a managed (groomed and machine made) snow simulation. Maximum value is 14.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Period with medium height of natural snow                                                   | day    | The number of days from August 1st of year N-1 to July 31st of year N fulfilling the conditions "Snow depth >= 30 cm" using a natural snow simulation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Period with medium height of natural snow between the fourth and tenth December             | day    | The number of days from December 4 of year N to December 10 of year N (included) fulfilling the condition "Snow depth >= 30 cm" using a natural snow simulation. Maximum value is 7.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| Period with medium height of natural snow between twenty second December and fourth January | day    | The number of days from December 22 of year N-1 to January 4 of year N (included) fulfilling the condition "Snow depth >= 30 cm" using a natural snow simulation. Maximum value is 14.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Snow making hours for WBT lower than -2°C                                                   | hour   | Computed wet bulb temperature (WBT) from temperature and relative humidity every 6 hours and interpolated linearly to an hourly time resolution. Expressed as the number of hours, from November 1st of year N-1 to December 31st of year N-1, for which wet buld temperature is less than -2°C.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Snow making hours for WBT lower than -5°C                                                   | hour   | Computed wet bulb temperature (WBT) from temperature and relative humidity every 6 hours and interpolated linearly to an hourly time resolution. Expressed as the number of hours, from November 1st of year N-1 to December 31st of year N-1, for which wet buld temperature is less than -5°C.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| Start of the longest period with groomed snow                                               | day    | Identified longest continuous period from August 1st of year N-1 to July 31st of year N where the snow depth is continuously above 30 cm using a groomed snow simulation. The first date, within this continuous period, meeting the condition "Snow depth >= 30 cm" is the beginning of the season. The last date within this continuous period, meeting this condition, is the end of the season. In case only one date meets the condition, then beginning of season and end of season are attributed this value. In case no date meets the condition (i.e., Snow depth is lower than 30 cm for the entire year), no date is attributed (value of 0). The value assigned is interpreted as the number of days after August 1st of year N-1.                            |
| Start of the longest period with managed snow                                               | day    | Identified longest continuous period from August 1st of year N-1 to July 31st of year N where the snow depth is continuously above 30 cm using a managed (groomed and machine made) snow simulation. The first date, within this continuous period, meeting the condition "Snow depth >= 30 cm" is the beginning of the season. The last date within this continuous period, meeting this condition, is the end of the season. In case only one date meets the condition, then beginning of season and end of season are attributed this value. In case no date meets the condition (i.e., Snow depth is lower than 30 cm for the entire year), no date is attributed (value of 0). The value assigned is interpreted as the number of days after August 1st of year N-1. |
| Start of the longest period with natural snow                                               | day    | Identified longest continuous period from August 1st of year N-1 to July 31st of year N where the snow depth is continuously above 30 cm using a natural snow simulation. The first date, within this continuous period, meeting the condition "Snow depth >= 30 cm" is the beginning of the season. The last date within this continuous period, meeting this condition, is the end of the season. In case only one date meets the condition, then beginning of season and end of season are attributed this value. In case no date meets the condition (i.e., Snow depth is lower than 30 cm for the entire year), no date is attributed (value of 0). The value assigned is interpreted as the number of days after August 1st of year N-1.                            |
| Total precipitation from November to April                                                  | kg.m-2 | Cumulative value of snowfall and rain precipitation over the winter sports season (November year N-1 to April year N).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| Total snow precipitation from November to April                                             | kg.m-2 | Cumulative value of snowfall precipitation over the winter sports season (November year N-1 to April year N).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |


:::
::: tab Licence lazy
[Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)
:::
::::
<br/> <br/>
### *Débit fluvial et prévisions associées*  
![glofas_debit_prevision](/images/glofas_debit_prevision.png)  
:::: tabs type:card 
::: tab Description lazy
Données journalières mondiales modélisées du débit fluvial, forcées avec des prévisions méteorologiques. *Le débit fluvial correspondant au volume d'eau s'ecoulant sur une portion de cours d'eau pour un temps donné.*  
Les données sont simulées en utilisant le modèle de tracé hydrologique LISFLOOD (avec une résolution de 10km par 10km) et les données quadrillées d'écoulement produites par le modèle de prévisions HTESSEL de l'ECWF.   
Ces données ont été produites par le Global Flood Awareness System (GloFas).
:::
::: tab Accès lazy
Climate (C3S) : [Accès aux données](https://cds.climate.copernicus.eu/cdsapp#!/dataset/cems-glofas-forecast?tab=overview)  

Les données sont accessibles librement après **inscription** sur la plateforme climat.    
Elles sont ensuite disponibles au téléchargement direct ou via API ainsi que par un service WMS.
:::
::: tab Métadonnées lazy
|     |     |
|------------------------|-------------------------------------------------------------------|
| **Type**                  | Raster                                                            |
| **Format**                 | GRIB et NetCDF                                                    |
| **Résolution temporelle**  | 5/11/2019 au Quasi Temps Réel (~3h) - prévisions jusqu'à 30 jours |
| **Résolution spatiale**   | 10km                                                              |
| **Mise à jour**            | Quotidienne                                                       |
| **Délai de Disponibilité** | Inconnu                                                           |
|     |     |
:::
::: tab Variables lazy
| Variables            | Unités  | Description                                                                                                                                                                                              |
|-----------------|--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over a 24-hour period. |
| Upstream area   | m2     | Static file - upArea.nc, Upstream area for the point in the river network                                                                                                                                |
:::
::: tab Licence lazy
Lien vers les détails de la [Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/cems-floods.pdf)
:::
::::    
<br/> <br/>
### *Débit fluvial et données historiques associées*  
![glofas_debit_prevision](/images/glofas_debit_hist.png)  
:::: tabs type:card 
::: tab Description lazy
Données journalières mondiales modélisées du débit fluvial, forcées avec des prévisions méteorologiques. *Le débit fluvial correspondant au volume d'eau s'ecoulant sur une portion de cours d'eau pour un temps donné.*   
Les données sont simulées en utilisant le modèle de tracé hydrologique LISFLOOD (avec une résolution 10km x 10km) avec les données quadrillées d'écoulement issue d'une réanalyse globale.
Les données d'écoulement sont produites par le modèle de prévision HTESSEL.  
Ces données ont été produites par le Global Flood Awareness System (GloFas).

:::
::: tab Accès lazy
Climate (C3S) : [Accès aux données](https://cds.climate.copernicus.eu/cdsapp#!/dataset/cems-glofas-historical?tab=overview)  

Les données sont accessibles librement après **inscription** sur la plateforme climat.    
Elles sont ensuite disponibles au téléchargement direct ou via API ainsi que par un service WMS.

:::
::: tab Métadonnées lazy
|     |     |
|------------------------|-------------------------------------------------------------------|
| **Type**                  | Raster                                                            |
| **Format**                 | NetCDF                                                    |
| **Résolution temporelle**  | 1/01/1979 au Quasi Temps Réel (~3h)   |
| **Résolution spatiale**   | 10km                                                              |
| **Mise à jour**            | à chaque mise à jour importante du système GLOFAS                                                       |
| **Délai de Disponibilité** | Inconnu                                                           |
|     |     |
:::
::: tab Variables lazy
| Variables            | Unités  | Description                                                                                                                                                                                              |
|-----------------|--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| River discharge | m3.s-1 | Volume rate of water flow, including sediments, chemical and biological material, in the river channel averaged over a time step through a cross-section. The value is an average over a 24-hour period. |
| Upstream area   | m2     | Static file - upArea.nc, Upstream area for the point in the river network                                                                                                                                |
:::
::: tab Licence lazy
Lien vers les détails de la [Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/cems-floods.pdf)
:::
::::
</br></br>

### *Flux WMS-T*
![EFAS9](/images/efas9.PNG)


:::: tabs type:card 
::: tab Description lazy
Les flux WMS-T permettent de récupérer différentes données gratuites ainsi que des données payantes ou partenaires avec accès au temps réel.

:::
::: tab Accès lazy
Service : Climate
[URL](https://www.efas.eu/efas_frontend/#/home)
Flux WMS
Accès gratuit pour les données suivantes

:::
::: tab Variables lazy
| Flux WMS                                       |
|------------------------------------------------|
| **RÉSUMÉ DES   INONDATIONS**                   |
| Probabilité   d'inondation <48h                |
| Probabilité   d'inondation> 48h                |
| Cartographie rapide   des crues                |
| Analyse d'impact   rapide                      |
| Points de rapport                              |
| Dépassement du   seuil de 1 à 2 jours          |
| Dépassement du   niveau de seuil 3-5 jours     |
| Dépassement du   niveau de seuil> 5 jours      |
| Dépassement du   seuil en cours                |
| **HYDROLOGIE**                                 |
| COSMO> 20 ans de   RP                          |
| COSMO> RP 5 ans                                |
| Det. DWD                                       |
| Det. ECMWF                                     |
| ECMWF-ENS> 20   ans de RP                      |
| ECMWF-ENS> RP 5   ans                          |
| Perspectives   saisonnières                    |
| Perspectives   sous-saisonnières               |
| **INIT.   CONDITIONS**                         |
| Anomalie de neige   10d                        |
| Obs. Temp moyenne.                             |
| Obs. Précipitation                             |
| Satellite Snow   Water Eq.                     |
| Humidité du sol   satellite                    |
| Équivalent eau de   neige                      |
| L'humidité du sol                              |
| Anomalie d'humidité   du sol                   |
| Synop 24 heures de   précipitations            |
| **CRUE SUBITE**                                |
| ERIC Affected Area                             |
| ERIC Reporting   Points                        |
| **STATIQUE**                                   |
| Régions   administratives                      |
| Bassins versants                               |
| Régions partenaires   EFAS                     |
| Niveaux de   protection contre les inondations |
| Réseau de drainage   LISFLOOD                  |
| LISFLOOD Points de   reporting fixes           |
| Réservoirs et lacs   LISFLOOD                  |
| Sensibilité aux   glissements de terrain       |
| Grands fleuves                                 |
| Liens nationaux   sur les inondations          |
| **EVALUATION**                                 |
| Compétence de   prévision à moyen terme        |
| Performance du   modèle - Bassins versants     |
| Performance du   modèle - Points               |
| **MÉTÉOROLOGIQUE**                             |
| Acc. Précip. Det.   DWD                        |
| Acc. Précip. Det.   ECMWF                      |
| COSMO Prob. Pr>   150 mm                       |
| COSMO Prob. Pr>   50 mm                        |
| ECMWF-ENS Prob.   Pr> 150 mm                   |
| ECMWF-ENS Prob.   Pr> 50 mm                    |  
::: 
::: tab Licence lazy
Lien vers les détails de la [Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/cems-floods.pdf)
:::
::::
 </br> </br>
 
## INCENDIES
### *Prévisions des risques d'incendies*
![Prevision](/images/prevision.PNG)

:::: tabs type:card 
::: tab Description lazy
3 modeles: ECMWF deterministic model, MeteoFrance deterministic model, ECMWF probabilistic model
:::
::: tab Accès lazy
Emergency Management Service (EMS) : [Service](https://ies-ows.jrc.ec.europa.eu/effis)  
WMS  
Accès gratuit

:::
::: tab Métadonnées lazy


|                            |                                                                                                                 |
|----------------------------|-----------------------------------------------------------------------------------------------------------------|
| **Type**                   | Raster                                                                                                          |
| **Format**                 | Inconnu                                                                                                         |
| **Résolution temporelle**  | prévision 1 à 9 jours pour le modèle ECMWF deterministe et 1-3 jours pour celui de MeteoFrance                   |
| **Résolution spatiale**    | 8km pour le modèle ECMWF deterministe, 10km pour celui de MeteoFrance et 18 km pour le modèle probabiliste ECMWF |
| **Mise à jour**            | Inconnu                                                                                                         |
| **Délai de disponibilité** |  |
|                            |                                                                                                                 |                                                                                                                 




:::
::: tab Variables lazy


| Variables                            |
|--------------------------------------|
| Fire Weather Index (FWI)             |
| Initial Spread Index (ISI)           |
| Build Up Index (BUI)                 |
| Fine Fuel Moisture Code (FFMC)       |
| Duff Moisture Code (DMC)             |
| Drought Code (DC)                    |
| Anomaly                              |
| Ranking                              |
| Keetch-Byron Drought Index           |
| Drought Factor (MARK-5 DF)           |
| Rate of Spread (MARK-5 ROS)          |
| Fire Danger Index (MARK-5 FDI)       |
| Rate of Spread (NFDRS ROS)           |
| Spread Component (NFDRS SC)          |
| Energy Release Component (NFDRS ERC) |
| Burning Index (NFDRS BI)             |
| Ignition Probability (NFDRS IC)      |

:::
::: tab Licence lazy
[Licence](https://effis.jrc.ec.europa.eu/about-effis/data-license/)
:::
::::
</br></br>

### *Evaluation rapide des dommages*
![FeuActif](/images/feu_actif.PNG)

:::: tabs type:card 
::: tab Description lazy
2 modules: MODIS et VIIRS
:::
::: tab Accès lazy
Emergency Management Service (EMS) : [Service](https://ies-ows.jrc.ec.europa.eu/effis)  
WMS  
Accès gratuit

:::
::: tab Métadonnées lazy


|                            |                                |
|----------------------------|--------------------------------|
| **Type**                   | Raster                         |
| **Format**                 | Inconnu                        |
| **Résolution temporelle**  | Temps réel                     |
| **Résolution spatiale**    | 1km pour MODIS et 375m VIIRS   |
| **Mise à jour**            | Inconnu                        |
| **Délai de disponibilité** | environ 2-3h après acquisition |
|                            |                                |



:::
::: tab Variables lazy


| Variable    |
|-------------|
| Active Fire |
| Burnt Area  |


:::
::: tab Licence lazy
[Licence](https://effis.jrc.ec.europa.eu/about-effis/data-license/)
:::
::::

</br></br>

### *Fire danger indicators for Europe from 1970 to 2098 derived from climate projections*
![Firedanger](/images/firedanger1970.PNG)

:::: tabs type:card 
::: tab Description lazy
Les données représentent les prévisions pour les indicateurs de risque d'incendie basé sur le Canadian Fire Weather Index System (FWI) pour les futures conditions climatiques. Le FWI est un index méteorologiques utilisé mondialement pour estimer le risque d'incendie et fait partie du modèle global de prédiction d'incendie (GEFF) de ECMWF. Les valeurs quotidiennes, saisonnières et autres valeurs dérivées du FWI ont été modelisées à partir du model GEFF pour estimer le risque d'incendie pour des scénarios de climat futurs. Ces indicateurs inclus le nombre de jours avec des risques d'incendies moyens, haut, voire très hauts, durant la "saison des incendies" (Juin-Septembre) de l'hémisphere nord, comme décrits par le Systeme d'Information Européen sur les Feux de Foret (EFFIS).
:::
::: tab Accès lazy
Emergency Management Service (EMS) : [Service](https://cds.climate.copernicus.eu/cdsapp#!/dataset/10.24381/cds.ca755de7?tab=overview)  
API  
Accès gratuit

:::
::: tab Métadonnées lazy

|                            |           |
|----------------------------|-----------|
| **Type**                   | Raster    |
| **Format**                 | NetCDF    |
| **Résolution temporelle**  | Prévision |
| **Résolution spatiale**    | Inconnu   |
| **Mise à jour**            | Inconnu   |
| **Délai de disponibilité** | 1970-2098 |
|                            |           |


:::
::: tab Variables lazy
| Name                                      | Units         | Description                                                                                                                                                                                                                                                                                                                                       |
|-------------------------------------------|---------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Daily fire weather index                  | Dimensionless | The fire weather index values at a daily temporal resolution for the selected year. The higher the index value, the more favorable the meteorological conditions to trigger a wildfire are.                                                                                                                                                       |
| Number of days with high fire danger      | Count         | Number of days per year with a fire weather index greater than 30 based upon the European Forest Fire Information System (EFFIS) classification.                                                                                                                                                                                                  |
| Number of days with moderate fire danger  | Count         | The number of days per year with a daily fire weather index greater than 15 based upon the European Forest Fire Information System (EFFIS) classification.                                                                                                                                                                                        |
| Number of days with very high fire danger | Count         | Number of days per year with a fire weather index greater than 45 based upon the European Forest Fire Information System (EFFIS) classification.                                                                                                                                                                                                  |
| Seasonal fire weather index               | Dimensionless | The mean fire weather index value over the European fire season (June-September). This is calculated as the sum of the daily fire weather index over the European fire season divided by the total number of days within this date range. The higher the index value, the more favorable the meteorological conditions to trigger a wildfire are. |
:::
::: tab Licence lazy
[Licence](https://cds.climate.copernicus.eu/api/v2/terms/static/licence-to-use-copernicus-products.pdf)
:::
::::
</br></br>

## ATMOSPHERE

### *Qualité de l’air en Europe*
![Monoxyde de carbone, prévision à T+96h, vendredi 23 novembre 2018 00UTC](/images/image_donnee_CAMS.png)

:::: tabs type:card 
::: tab Description lazy
Le service atmosphère de Copernicus propose des analyses et prévisions journalières de la qualité de l'air en Europe. 8 modèles européens sont utilisés ou compilés dans un ensemble pour créer des données prévisionnelles concernant différents paramètres de l’air.
Les prévisions sont mises à jour quotidiennement pour les 4 jours suivants, les prévisions sont disponibles pour chaque heure  à 7 différentes altitudes (Surface, 50m, 250m, 500m, 1000m, 2000m, 3000m, 5000m).

[Documentation additionnelle](https://confluence.ecmwf.int/display/CKB/CAMS+Regional%3A+European+air+quality+analysis+and+forecast+data+documentation)
:::
::: tab Accès lazy
Atmosphère (CAMS) : [URL](https://ads.atmosphere.copernicus.eu/cdsapp#!/dataset/cams-europe-air-quality-forecasts?tab=form)  
Pas de WMS  
Accès gratuit mais besoin d’une inscription au service CAMS (différent des autres)

::: details Téléchargement par API : exemple de l’ammoniac dans la colonne d'air complète sur une prévision de 24h, heure par heure
``` py
import cdsapi

c = cdsapi.Client()

c.retrieve(
    'cams-europe-air-quality-forecasts',
    {
        'variable': 'ammonia',
        'model': [
            'chimere', 'dehm', 'emep',
            'ensemble', 'euradim', 'gemaq',
            'lotos', 'match', 'mocage',
            'silam',
        ],
        'level': [
            '0', '1000', '2000',
            '250', '3000', '50',
            '500', '5000',
        ],
        'date': '2020-12-01/2020-12-01',
        'type': 'forecast',
        'time': '00:00',
        'leadtime_hour': [
            '0', '1', '11',
            '12', '13', '14',
            '15', '16', '17',
            '18', '19', '2',
            '20', '21', '22',
            '23', '24', '3',
            '4', '5', '6',
            '7', '8', '9',
        ],
        'area': [
            52.74, -7.12, 38.6,
            12.57,
        ],
        'format': 'netcdf',
    },
    'download.nc')
```
:::
::: tab Métadonnées lazy
|                            |                 |
|----------------------------|-----------------|
| **Type**                   | Raster modélisé |
| **Format**                 | GRIB NetCDF     |
| **Résolution temporelle**  | 0 à 96h         |
| **Résolution spatiale**    | 10km x 10km     |
| **Mise à jour**            | quotidienne     |
| **Délai de disponibilité** |  inconnu        |
|                            |                 |


:::
::: tab Variables lazy
| nom de la variable                                                     | Unité                       |
|------------------------------------------------------------------------|-----------------------------|
| Ammonia                                                                | GRIB: kg m-3 netCDF: µg.m-3 |
| Birch pollen                                                           | Grains.m-3                  |
| Carbon monoxide                                                        | GRIB: kg m-3 netCDF: µg.m-3 |
| Dust                                                                   | GRIB: kg m-3 netCDF: µg.m-3 |
| Grass pollen                                                           | Grains.m-3                  |
| Nitrogen dioxide                                                       | GRIB: kg m-3 netCDF: µg.m-3 |
| Nitrogen monoxide                                                      | GRIB: kg m-3 netCDF: µg.m-3 |
| Non-methane VOCs                                                       | GRIB: kg m-3 netCDF: µg.m-3 |
| Olive pollen                                                           | Grains.m-3                  |
| Ozone                                                                  | GRIB: kg m-3 netCDF: µg.m-3 |
| Particulate matter d < 10 µm (PM10)                                    | GRIB: kg m-3 netCDF: µg.m-3 |
| Particulate matter d < 10 µm - wildfires only                          | GRIB: kg m-3 netCDF: µg.m-3 |
| Particulate matter d < 2.5 µm (PM2.5)                                  | GRIB: kg m-3 netCDF: µg.m-3 |
| Particulate matter d < 2.5 µm - anthropogenic fossil fuel carbon only  | GRIB: kg m-3 netCDF: µg.m-3 |
| Particulate matter d < 2.5 µm - anthropogenic wood burning carbon only | GRIB: kg m-3 netCDF: µg.m-3 |
| Peroxyacyl nitrates                                                    | GRIB: kg m-3 netCDF: µg.m-3 |
| Ragweed pollen                                                         | Grains.m-3                  |
| Secondary inorganic aerosol                                            | GRIB: kg m-3 netCDF: µg.m-3 |
| Sulphur dioxide                                                        | GRIB: kg m-3 netCDF: µg.m-3 |

::: tip A noter
Les concentrations de monoxyde d'azote, le dioxyde d'azote, le dioxyde de soufre, l'ozone, les particules <2.5 micromètres, les particules <10 micromètres et la poussière sont régulièrement vérifiées avec les mesures in-situ. 
Les autres variables ne sont pas confirmées, donc à considérer comme expérimentales. 
:::  

::: tab Licence lazy
[Licence Copernicus](https://www.copernicus.eu/en/access-data/copyright-and-licenses)
:::
::::
</br></br>  

## DONNEES SATELLITES SENTINEL

### *Sentinel-1 A et B*  
![sentinel_1](/images/sentinel_1.jpg)  
:::: tabs type:card
::: tab Description lazy
Satellites radar SAR (Synthetic Aperture Radar) à bande C. Ils permettent une observation de la Terre de jour comme de nuit, quelles que soient les conditions météorologiques ou environnementales (la prise de vue n’est pas impactée par les nuages ou le manque d’illumination).  

Missions principales : 
- surveillance des mers glacées et de l’arctique
- surveillance de l’environnement maritime
- surveillance des surfaces terrestres pour la gestion des risques
- surveillance des surfaces terrestres, forêt, agriculture et eau
- support lors des crises humanitaires et désastres naturels  

*Détails supplémentaires concernant le Sentinel-1 :  [[1]](https://sentinel.esa.int/web/sentinel/user-guides/sentinel-1-sar), [[2]](https://sentinels.copernicus.eu/web/sentinel/technical-guides/sentinel-1-sar)*


:::
::: tab Accès lazy
Portail ESA (SCI Hub) : [Accès aux données](https://scihub.copernicus.eu/dhus/#/home)  

Les données sont accessibles librement après **inscription** sur la plateforme.    
Elles sont ensuite disponibles au téléchargement direct ou via API (OData ou OpenSearch), *[plus d’informations](https://scihub.copernicus.eu/userguide/APIsOverview)*

:::
::: tab Métadonnées lazy
| 	| 	|
|------------------------|-------------------------------------------------------------------|
| **Type**              	| Raster                                                        	|
| **Format**             	| NetCDF                                                	|
| **Résolution spatiale**   | variable selon le produit                                                          	|
| **Délai de Disponibilité**  | Near Real Time (~3h), Short Time Critical (2-3 jrs), Non Time Critical (~1 mois)  |
| 	| 	|
:::
::: tab Types de produits lazy
Les produits sont disponibles selon **trois niveaux de traitements** (Level-0, 1 et 2) et **quatre modes de prise de vue**, chacune avec des résolutions et des polarisations différentes:
- Stripmap (SM)
- Interferometric Wide (IW)
- Extra-Wide (EW)
- Wave (WV)

| Types de produits        	 | Description      |                                                                                                                                                                        
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| SAR_L1_SLC  | Single Look Complex  | 
| SAR_L1_GRD   | Ground Range Detected  	| 
| SAR_L2_OCN   | Ocean 	|   

::: details Résolution disponibles pour chaque produit
![sent_1_resol](/images/sentinel-1_resol_produits.png)


:::
::: tab Licence lazy
Lien vers les détails de la [Licence](https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice)
:::
::::
</br></br>

### *Sentinel-2 A et B* 
![sentinel_2](/images/sentinel_2.jpg)  
:::: tabs type:card
::: tab Description lazy
Satellites optiques MSI (Multi-Spectral Instrument), permettant des captures d’images haute résolution de la surface terrestre.

Missions principales : 
- acquisition globale à haute résolution
- continuité SPOT et LANDSAT
- observation de toutes les terres émergées et zones côtières
- support pour les crises humanitaires et désastres naturels
- sécurité  

*Détails supplémentaires concernant le Sentinel-2 :  [[1]](https://sentinel.esa.int/web/sentinel/missions/sentinel-2), [[2]](https://sentinels.copernicus.eu/web/sentinel/technical-guides/sentinel-2-msi)*

:::
::: tab Accès lazy
Portail ESA (SCI Hub) : [Accès aux données](https://scihub.copernicus.eu/dhus/#/home)  

Les données sont accessibles librement après **inscription** sur la plateforme.    
Elles sont ensuite disponibles au téléchargement direct ou via API (OData ou OpenSearch), *[plus d’informations](https://scihub.copernicus.eu/userguide/APIsOverview)*

:::
::: tab Métadonnées lazy
| 	| 	|
|------------------------|-------------------------------------------------------------------|
| **Type**              	| Raster                                                        	|
| **Format**             	| NetCDF                                                	|
| **Résolution spatiale**   | tuiles de 100 x 100 km2                                                          	|
| **Délai de Disponibilité**  | Near Real Time (~3h), Short Time Critical (2-3 jrs), Non Time Critical (~1 mois)  |
| 	| 	|
:::
::: tab Types de produits lazy
Ce satellite permet d’acquérir des images dans 13 bandes spectrales avec une fauchée de 290 km. Les produits sont disponibles selon **deux niveaux de traitements** (Level-1 et 2). 

| Types de produits        	 | Description      |                                                                                                                                                                        
|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Level-1C  | Top-of-Atmosphere reflectance in cartographic geometry  | 
| Level-2A   | Bottom-of-Atmosphere reflectance in cartographic geometry  	|   

:::details Résolution disponibles pour chaque bande spectrale
![sent_2_resol](/images/sentinel-2_produits.png)
:::
::: tab Licence lazy
Lien vers les détails de la [Licence](https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice)
:::
::::
</br></br>
### *Sentinel-3 A et B* 
![sentinel_3](/images/sentinel_3.jpg)  
:::: tabs type:card
::: tab Description lazy
Satellites multi-instruments fournissant une grande diversité de mesures sur les océans et les continents comprenant notamment: 
- la “couleur” des océans et des terres, indicatrice par exemple de la composition des eaux survolées
- la température à la surface de la Terre
- la topographie de surface des océans et des glaces terrestres, et l’altimétrie
- la topographie des zones côtières, des “eaux continentales” 

*Détails supplémentaires concernant le Sentinel-3 :  [[1]](https://sentinel.esa.int/web/sentinel/missions/sentinel-3), [[2]](https://sentinels.copernicus.eu/web/sentinel/technical-guides/sentinel-3-olci)*

:::
::: tab Accès lazy
Portail ESA (SCI Hub) : [Accès aux données](https://scihub.copernicus.eu/dhus/#/home)   
Portail EUMETSAT (CODA) : [Accès aux données](https://coda.eumetsat.int/#/home)  

Les données sont accessibles librement après **inscription** sur la plateforme.    
Elles sont ensuite disponibles au téléchargement direct ou via API (OData ou OpenSearch), *[plus d’informations](https://scihub.copernicus.eu/userguide/APIsOverview)*

:::
::: tab Métadonnées lazy
| 	| 	|
|------------------------|-------------------------------------------------------------------|
| **Type**              	| Raster                                                        	|
| **Format**             	| NetCDF                                                	|
| **Résolution spatiale**   | variable selon le produit                                                          	|
| **Délai de Disponibilité**  | Near Real Time (~3h), Short Time Critical (2-3 jrs), Non Time Critical (~1 mois)  |
| 	| 	|
:::
::: tab Types de produits lazy
Les produits sont disponibles selon ** deux niveaux de traitements** (Level-1 et 2) pour les instruments suivant : 
- **SAR Radar Altimeter (SRAL)** 
- **Sea and Land Surface Temperature Radiometer (SLSTR)** avec 9 bandes spectrales : températures à la surface de la Terre
- **Ocean and Land Colour Instrument (OLCI)** avec 21 bandes spectrales   
Les produits Synergy (SYN) sont issus de la combinaison des produits de OLCI et SLSTR.

| Instrument       	| Types de produits       	 | Description      |                                                                                                                                                                        
|-----------------|-----------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| OLCI      | OL_1_EFR, OL_1_ERR | Top-of-Atmosphere radiance at Full and Reduced Resolution  |
| OLCI      | OL_2_LFR,OL_2_LRR | Land/Water and atmospheric geophysical parameters at Full and Reduced resolution  |  
| SLSTR      | Level-1B_RBT  | Radiance and Brightness temperature  | 
| SLSTR      | Level-2_WST  | Water Single Temperature ie. Sea Surface Temperature  | 
| SLSTR      | Level-2_LST  | Land Surface Temperature  | 
| SLSTR      | Level-2_FRP  | Fire Radiative Power  | 
| SLSTR      | Level-2_AOD  | Global Aerosol Optical Depth  |  
| SYN      | Level-2_SYN  | Surface reflectance and aerosol parameters over land  |
| SYN      | Level-2_VGP  | Top-of-Atmosphere reflectances  | 
| SYN      | Level-2_VG1&V10  | Vegetation-like products  |
| SRAL      | Level-1A | Geo-located bursts of echoes  with all calibrations applied  |
| SRAL      | Level-1B | Geo-located and fully calibrated multi-looked High Resolution power echoes  |
| SRAL      | Level-1B-S | SAR-processed and calibrated High Resolution complex echoes arranged in stacks after slant range correction and prior to echo multi-look  |
| SRAL      | Level-2 : SR_2_WAT, SR_2_LAN | Water and Land products |   
:::details Résolution disponibles pour les différents instruments
![sent_3_resol](/images/sentinel-3_produits.png)
:::
::: tab Licence lazy
Lien vers les détails de la [Licence](https://sentinels.copernicus.eu/documents/247904/690755/Sentinel_Data_Legal_Notice)
:::
::::
</br></br>



