## 🚨Link para descargar la base de datos:🚨
https://drive.google.com/drive/folders/1FFEaad1AbKXDugr4pLr5SeIK3XO-8gkm?usp=sharing


#

# Datos y género:
### Visualizar el trabajo del hogar en MX.

 
En el marco de las actividades del Open Data Day R-Ladies Guadalajara se une a [SocialTIC](https://socialtic.org/) para presentar un taller introductorio a la visualización el trabajo del hogar en México.


![image](https://pbs.twimg.com/media/EvpyzbwVgAMfYiy?format=jpg&name=4096x4096)


#### Package requerida
```
install.packages(c("haven", "ggplot2", "viridis", "dplyr", "rgdal", "sf",
                 "plotly", "scales",  "leaflet", "proj4")


library(haven)
library(ggplot2)
library(dplyr)
library(viridis)
library(leaflet)
library(scales)
library(rgdal)
library(proj4)
library(sf) 
library(plotly)

```
Los datos que se utilizan para la visualización es a partir de la ENOE 2020, que cuenta con información sobre el trabajo del hogar (doméstico), la base de datos original se encuentra en el portal de INEGI https://www.inegi.org.mx/contenidos/programas/enoe/15ymas/microdatos/enoe_n_2020_trim4_dta.zip 

Es necesario descomprimir los archivos del zip.

Imagen ilustrativa: 

![image](https://user-images.githubusercontent.com/75498886/110187720-f31e6800-7dde-11eb-8203-12f2d2ab6620.png)

Para el taller se utiliza el formato .dta, esto para hacer uso de las variables etiquetadas (labelled).
#
