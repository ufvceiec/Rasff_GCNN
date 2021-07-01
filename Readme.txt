---------------------------------------------------------
Derechos reservados de esta investigación por el CEIEC.
---------------------------------------------------------

Esta jerarquía de carpetas corresponde a la línea de investigación de predicción 
de amenazas de las rutas en el Portal RASFF.

---------------------------------------------------------

La jerarquía de las carpetas y su funcionalidad es la siguiente:

"Scrapeo Web" :	Se obtienen los nuevos datos del portal RASFF y se unen 
		con otro dataset de RASFF antiguo ya existente.
        - 1º) RASFFportal_scraping.
        - 2º) new+old_Datasets_join.

"Análisis" : 	Analiza los datos obtenidos, creando un clustering jerárquico 
		y varias tablas para indicar las amenazas, productos y países 
		existentes en los datos.
        - 1º) Análisis_full_RASFF_Data.
        - 2º) Clustering.

"GCNNs" : Experimentos empleando Stellargraph sobre los datos del portal RASFF. Se divide en GCNN simple y compuesto.
        - 1º) Preprocessing.
        - 2º) Training.

"CNNs" : Experimentos empleando CNNs sobre los datos del portal RASFF. Se divide en:   
    + "CNN - matrices", donde se crean matrices en base a las conexiones de las rutas y se introducen directamente:
        - 1º) Preprocessin  & Training.
    + "CNN - Images", donde se emplean CNNs sobre imágenes generadas a partir de los datos del portal RASFF.
        - 1º) Preprocessing .
        - 2º) Training.     

"Datasets" : Carpeta donde se guardan los datasets genéricos y empleados en todos los demás experimentos.

---------------------------------------------------------

Autores : Ignacio Moll Amorós.