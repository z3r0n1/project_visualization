# **PROYECTO**
## *Análisis sobre base de datos de muestra con visualizaciones en Tableau*

# **ESTRUCTURA DEL REPOSITORIO**
* ## ***data***:
    - Contiene:
        * 'employees.csv', archivo de muestra utilizado.
        * 'Employees Analitics.twb', archivo de Tableau.
        * 'employees.hyper', archivo de extracción de datos de Tableau.
----  
#
# **CONTEXTO**
### Se ha utilizado un archivo .csv con varios datos de muestra sobre empleados de una empresa para crear ejemplos de visualizaciones y hacer un análisis sobre ellos.
### En todo momento se establece un filtro visual de color por Sexo y otro filtro explícito por Departamento. Los datos numéricos son mostrados en promedios.
### En la mayoría de gráficos se establecen otros dos filtros por Puesto Laboral y por Campo Educativo.
#
----
https://public.tableau.com/views/EmployeesAnaliticsDashboard1/AvgMonthlyIncomeandSatisfactionbyJobRoleandEducationField?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link

----
### En la **primera visualización** podemos observar, en primer lugar,un *Gráfico de Barras* con la media de edad, los años en la compañía y los años en un mismo Puesto Laboral.
### En segundo lugar dos *Gráficos de Tarta* contiguos con la media de horas estándard trabajadas y el total de horas estándard trabajadas respectivamente.
### Y en tercer lugar un *Gráfico de Barras* que muestra la media mensual de ingresos, con su rango de medidas situado a la izquierda, junto a unas *marcas con formas circulares* que muestran la media de satisfacción por cada Puesto Laboral, con su rango de medidas situado a la derecha. Arriba podemos ver los distintos Departamentos y Puestos Laborales por cada Departamento, mientras que abajo podemos ver los distintos Campos Educativos por cada Puesto Laboral.
#
----
https://public.tableau.com/views/EmployeesAnaliticsDashboard2/AvgJobPerformanceInvolvementSatisfaction?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link

----
### En la **segunda visualización** podemos observar, en primer lugar, un *Gráfico de Barras* con la media de Evaluación de Rendimiento, con su rango de valores situado a la izquierda, y el Grado de Satisfacción en el Entorno Laboral, con su rango de valores situado a la derecha. Arriba podemos ver los distintos Departamentos y Puestos Laborales por cada Departamento, mientras que abajo podemos ver los distintos Campos Educativos por cada Puesto Laboral.
### En segundo lugar un *Gráfico de Tarta* con la media de Grado de Satisfacción en el Entorno Laboral por Departamento.
### En tercer lugar podemos ver un *Gráfico de marcas con formas circulares* mostrando la media de Grado de Involucración, con sus rangos de valores a la izquierda. Arriba podemos ver los distintos Departamentos y Puestos Laborales por cada Departamento, mientras que abajo podemos ver los distintos Campos Educativos por cada Puesto Laboral.
#
#
# **ANÁLISIS**
## *Primera visualización*
### En primer lugar podemos ver como la media de edad, tanto de hobres como de mujeres, por departamento está sobre los 36-37 años.
### La media de años en la compañía varía notablemente entre hombres y mujeres en el departamento de Recursos Humanos, siendo la de mujeres 5,3 y la de hombres 8,1. Mientras en Investigación y Desarrollo sólo se llevan 8 décimas y la media de situaría en 6,9. En el departamento de Ventas la media es claramente de un 7,2.
### En cuanto a la media de años en el mismo Puesto Laboral las medias varían en el departamento de Recursos Humanos, siendo menor la de mujeres y mayor la de hombres, con un 2,7 y 3,9 respectivamente. En el departamento de Investigación y Desarrollo la media en mujeres es mayor que la de hombres, siendo estas 4,4 y 3,9 respectivamente. Mientras la media en el departamento de ventas se mantiene igual para ambos, siendo esta de 4,4.
### En segundo lugar podemos ver como la **media** de horas trabajadas por ambos sexos es la misma: 80. También observamos como el **total** de horas trabajadas por hombres es mayor que el de mujeres en cada departamento, por lo que implícitamente sabemos que en este caso hay más hombres contratados que mujeres en todos los departamentos.
### En tercer lugar y lo que este gráfico de barras con marcas nos muestra es que pese a grandes diferencias salariales entre Puestos Laborales la satisfacción general ronda entre el 2 y el 3. A destacar como en el departamento de Investigación y Desarrollo en los Puestos de *Manager* y *Research Director* para aquellas personas con campo educativo en *Grado Técnico* los hombres tienen una satisfacción notablemente mayor que las mujeres siendo esta de 4 para los hombres en cada uno de los Puestos y de 2 y 2,2 para las mujeres respectivamente. En el departamento de Ventas para el puesto de *Manager* también hay una satisfacción de 4 para hombres y de 2 para mujeres.
#
## *Segunda visualización*
### En primer lugar podemos ver como la media de Evaluación de Rendimiento se mueve en un corto rango de 3 a 3,5 sin destacar ninguno de los dos sexos en ninguno de los filtros. Mientras el grado de satisfacción con el entorno oscila entre el 1 y el 4, siendo las mujeres con Grado Técnico trabajando en un puesto de Recursos Humanos en el Departamento de Recursos Humanos las que tienen la menor valoración y, a su vez, siendo también las mujeres del departamento de Recursos Humanos, tanto en el puesto de Recursos Humanos, pero con estudios médicos, como en el puesto de Manager con estudios científicos las que tienen la mayor valoración.
### En segundo lugar, en el *Gráfico de Tarta* podemos observar como la media por Departamento de grado de satisfacción es del 2,7.
### Y finalmente, en tercer y último lugar, podemos ver cómo las personas tanto mayor como menormente involucradas en su Puesto son mujeres en ambos casos. Siendo las menormente involucradas aquellas que tienen un Grado Técnico y ocupan un puesto de Manager en el departamento de Ventas, siendo esta valoración de 1, mientras que por otro lado las mayormente involucradas son aquellas con estudios médicos ocupando un Puesto de Recursos Humanos en el Departamento de Recursos Humanos, siendo esta valoración de 3,5.
#
# **CONCLUSIÓN**
### Generalmente no hay grandes diferencias entre sexos excepto por los datos de ingresos mensuales en los que, con mismos estudios, en mismo puesto y mismo departamento, sí aparecen algunas diferencias notables tanto en beneficio de hombres como en beneficio de mujeres. Habría que estudiar las causas de estas diferencias de forma más individualizada para encontrar respuesta.
