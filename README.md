# Correlaciones y regresiones entre el Censo y la Casen

![title](linear_regresssion.jpeg)
https://towardsdatascience.com/linear-regression-explained-1b36f97b7572

1. Correlaciones: corre_ing_exp-censo_casen 
2. Regresiones lineales a nivel urbano: reg_ce_ca_2017/urbano
3. Compendio de regresiones urbanas: reg_ce_ca_2017/urbano/reg_lin_censo_casen_compendio.Rmd 
4. Compendio de correlaciones: corre_ing_exp-censo_casen/corr_censo_casen_compendio.html

<hr style="height:3px;border-width:1;color:Gray;background-color:Gray">
<br>

5. Primeras Regresiones lineales: ds_correlaciones_censo_casen/reg_ce_ca_2017

**Primeras regresiones lineales con las más altas correlaciones:**\
6. ds_correlaciones_censo_casen/reg_ce_ca_2017/urbano/analisis_a_nivel_nacional_urbano.Rmd/(producción)
   
**Generación de tablas de correlaciones:**\
7. ds_correlaciones_censo_casen/corre_censo_casen_2017/
8. 

************************************************************
******************* Regiones urbanas ***********************
************************************************************
El siguiente Rmd calcula las **frecuencias** de respuestas 1 (¿Trabajó por un pago o especie?) a P17 que unimos a los ingresos promedios comunales, y construimos el campo **multipob**, con el que lanzamos varios modelos de regresión eligiendo el mejor. Ésto lo hacemos por el momento en forma "manual".

1. ds_correlaciones_censo_casen/reg_ce_ca_2017/urbano/region_01_P17_u
************************************************************
Lo que debe quedar meridianamente claro son las tablas **rurales** y **urbanas** de los ingresos extraídos de la Casen promediados por comuna, que están aquí:\
ds_correlaciones_censo_casen\reg_ce_ca_2017\urbano\ingresos_expandidos_Casen_u_y_r.Rmd
    
ingresos_expandidos_casen_2017_totales.rds       
ingresos_expandidos_casen_2017_totales_r.rds\
ingresos_expandidos_casen_2017_totales_u.rds
