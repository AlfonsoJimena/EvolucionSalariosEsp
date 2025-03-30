# Proyecto de asignatura PBDA (Programación para Big Data)

Este proyecto trata sobre la explotación de los datasets de la evolución de los salarios en España. Los datos han sido tomados del INE.  
La práctica está dividida en dos partes:  

- **Obligatoria**: El alumno debe responder a las cuestiones planteadas por el profesor.  
- **Libre**: El alumno podrá realizar las modificaciones y análisis que considere interesantes para extraer información y conclusiones.  

## Archivos que contiene el proyecto

- **MicroDatos_INE** (Datos tomados del INE sobre salarios).  
- **Práctica PBDA** (Contiene los archivos usados para realizar el análisis de los datos):  
    - **NUTS1** (Imagen de España dividida en regiones NUTS1).  
    - **main.ipynb** (Archivo que contiene el análisis de los datos).  
    - **pbda.h5**.  
    - **ResultadosINE2024.html**.  

## Importante

Esta es una práctica curricular de la asignatura PBDA de la UPM. Como se puede observar, la última sección  
se dejó libre para que el alumno realizara el análisis que considerase necesario.  

En mi caso, decidí realizar los siguientes análisis:  

- Show a heatmap of salary per region.  
- Visualize the relationship between gender equality and region.
- Display of population growth rate by region.  
- Wage gap analysis. 
- Analysis of salary differences between men and women by type of work.  
- Average base salary by education level and by region. *(Aquí se tuvo que reestructurar los datos, ya que su toma fue cambiando con el paso del tiempo. Más detalles en el código).*
