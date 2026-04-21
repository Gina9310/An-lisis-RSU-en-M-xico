# Análisis-RSU-en-México
Trazabilidad de RSU de acuerdo a información disponible 

El proyecto tienen como objetivo analizar la información disponible acerca del manejo y trazabilidad de los RSU en México

---

## 📂 Contenido del repositorio
- `análsiis RSU México GIT` → Notebook principal con el análisis paso a paso.
- `Dataset con información de RSU`.
- `README.md` → Documentación del proyecto.

---

## ⚙️ Requisitos

- Jupyter Notebook
- Librerías:
  - pandas
  - matplotlib
    
## Objetivo
Explorar la relación entre la recolección y manejo de RSU con variables como:


Número de municipios con servicios de recolección se RSU,
Recolección promedio diaria de RSU,
Prestadores de servicios de recolección,
Producto Interno Bruto (PIB) y
Densidad poblacional



## Datos
Fuente principal: Censo Nacional de Gobiernos Municipales y Demarcaciones Territoriales de la Ciudad de México (CNGMD), específicamente su módulo de Residuos Sólidos Urbanos 

Variables clave:

Servicios de Recolección de RSU por Estado

Promedio diario de RSU recolectados por Estado

Prestadores de servicio de Recolección de RSU por Estado

Densidad poblacional 2020

PIB 2021

Existencia de Programas en materia de Gestión de Residuos por Estado

Estaciones de transferencia (cantidad de RSU que van a ET por Estado)

Plantas de tratamiento (cantidad de RSU que van a PT por Estado)

Sitios de disposición final (cantidad de RSU que van a SDP por Estado)


 
## Metodología
Exportación de base de datos, dado que por año vienen cierta información se seleccionó aquella información relevante a analizar: cantidad recolectada, número de prestadores de servicio, cantidad o porcentaje de RSU que llegan a estaciones de transferencias y a plantas de tratamiento. Se analizó y se depuró la información de manera seccionada.

Limpieza de datos
  - Tratamiento de nulos

Selección de variables
  -Cantidad promedio de rSU recolectados
  -Número de prestadores de servicios de recoleccion de RSU
  -%de cobertura de recoleccion de RSU
  
Tratamiento de valores faltantes

Análisis exploratorio

Comparación entre estados
- Elaboración de gaficos que presentan por estado:
    - % de servicio de recolección de RSU: 93 % de los estados tienen cobertura de mas de 95% de servicios de recolección de RSU en sus municipios.
    - Cantidad diaria de Recolección de RSU: Aún cuanto Oaxaca y Chiapas sean los Estados con mayor numero de servicios de recolección, no son precisamente los Estados con mayor cantidad de RSU recolectados diariamente, esta tendencia podría estar   marcada tanto por la población en cada Estado como por su actividad Económica. Los Estados con mayor recolección diaria son la Ciudad de México (16,000 ton), México (12,000 Ton), Jalisco(9,000 Ton), Nuevo León, Puebla, Veracruz, Guanajuato.
    - Número de prestadores de servicio de recolección de RSU: Oaxaca y Puebla tienen cerca de 400 y 250 prestadores de servicio. 
    - Gráfico que compara la recolección diaria de RSU, el % de aportación del PIB y densidad poblacional, mismo que presenta la relación que hay entre cantidad recolectada y aportación al PIB.

Se determino que cantidad de RSU van a ET, PT y disposición final: En méxico más del 93% de los residuos van directo a disposición final

    
## Conclusiones:
- No existe información disponible acerca de la generación de RSU por Entidad.

- Existe una relación entre número de municipios de cada Estado con la cantidad de servicios de recolección, Estados con mayor número de municipios mayor número de servicios de recolección.
  ![Municipios con servicio RSU](https://github.com/Gina9310/An-lisis-RSU-en-M-xico/blob/main/figura.png)

  El gráfico muestra la cantidad de servicios de recolección por Estado. Estados con mayor número de municipios encabezan la lista, tales como Oaxaca, Puebla, Veracruz, Chiapas.

- 93 % de los estados tienen cobertura de mas de 95% de servicios de recolección de RSU en sus municipios
  ![Cobertura con servicio RSU](https://github.com/Gina9310/An-lisis-RSU-en-M-xico/blob/main/figura_2.png)
El gráfico anterior presenta el número de servicios registrados que, puede no coicidir exactamente con el número total de municipios, por ejemplo aún cuando Oaxaca presente un total de 442 servicios de recolección, la realidad es que 128 municipios no cuentan con este servicio. Por ello el presente gráfico muestra el % de cobertura de servicios de recolección por Estado considerando el número de municipios. 93 % de los estados tienen cobertura de mas de 95% de servicios de recolección de RSU en sus municipios, menos Oaxaca y Guerrero.
  
- Número de prestadores de servicio de recolección de RSU
 ![Cobertura con servicio RSU](https://github.com/Gina9310/An-lisis-RSU-en-M-xico/blob/main/figura_4.png)

El gráico muestra el numero de prestadores de servicio de Recolección, con comportamiento similar al gráfico de número de servicios de recolección.

- No existe relación entre número de municipios y cantidad recolectada de RSU.
  ![Recolección promedio diaria RSU](https://github.com/Gina9310/An-lisis-RSU-en-M-xico/blob/main/figura_3.png)
El gráfico muestra la cantidad de RSU recolectados (ojo!, no generados). Podría pensarse que Oaxaca al tener mayores número de municipios y servicios de recolección sería el estado que más recolecta al día, pero esto no es así. Los Estados con mayor recolección diaria son la Ciudad de México (16,000 ton), México (12,000 Ton), Jalisco(9,000 Ton), Nuevo León, Puebla, Veracruz, Guanajuato. entonces, ¿A qué podría estar relacionada la cantidad de recolección?

  
![Relación entre indicadores](https://github.com/Gina9310/An-lisis-RSU-en-M-xico/blob/main/figura_5.png)

- Existe una relación entre la actividad economica y la cantidad promedio recolectada al día. Estados con mayor aportación al PIB presentan mayor cantidad de RSU recolectados. Los estados que más cantidad de RSU recolectan son la Ciudad de México, México, Jalisco, Nuevo León, Puebla, Veracruz, Guanajuato y coincide con los estados que más aportan al PIB, lo cual quiere decir que existe más una relación de la cantidad de recolección de RSU con las actividades economicas que con la densidad poblacional.

- únicamente 11 Estados cuentan con estaciones de transferencia.

- 19 Estados cuentan con plantas de tratamiento de RSU.

- En méxico más del 93% de los residuos van directo a disposición final.
  ![Distribución de los RSU a estaciones, plantas tratamiento y sitios de disposición final](https://github.com/Gina9310/An-lisis-RSU-en-M-xico/blob/main/figura_6.png)

  ¿Qué pasa con los RSU después de ser recolectados?
Una porción va a Estaciones de transferencia(ET). Una ET es un lugar donde se traspasan de las unidades de recolección a vehículos de mayor capacidad, para su traslado a las plantas de tratamiento o a los sitios de disposición final.Algunos residuos suelen ser separados para reciclaje. En méxico, en 2022 se recolectaron un promedio diario de 108,146 Ton, del cual un promedio diario de 1,254 Ton de RSU se separon en ET para ser reciclados y 5,661 (promedio diario) se enviaron a Plantas de tratamiento. por lo que se concluye que en méxico más del 93% de los residuos van directo a disposición final. El gráfico muestra por Estado la distribución de lso RSU recolectados.

  
