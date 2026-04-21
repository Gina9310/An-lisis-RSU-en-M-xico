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


Número de municipios con servicios de recolección se RSU
Recolección promedio diaria de RSU
Prestadores de servicios de recolección
Producto Interno Bruto (PIB)
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
-   - % de servicio de recolección de RSU.
    - Cantidad diaria de Recolección de RSU.
    - Número de prestadores de servicio de recolección de RSU
    - Gráfico que compara la recolección diaria de RSU, el % de aportación del PIB y densidad poblacional

Se determino que cantidad de RSU van a ET, PT y disposición final.

    
## Conclusiones:
- No existe información disponible acerca de la generación de RSU por Entidad.

- Existe una relación entre número de municipios de cada Estado con la cantidad de servicios de recolección, Estados con mayor número de municipios mayor número de servicios de recolección.

- Existe una relación entre la actividad economica y la cantidad promedio recolectada al día. Estados con mayor aportación al PIB presentan mayor cantidad de RSU recolectados. Los estados que más cantidad de RSU recolectan son la Ciudad de México, México, Jalisco, Nuevo León, Puebla, Veracruz, Guanajuato y coincide con los estados que más aportan al PIB, lo cual quiere decir que existe más una relación de la cantidad de recolección de RSU con las actividades economicas que con la densidad poblacional.

- No existe relación entre número de municipios y cantidad recolectada de RSU.

- En méxico más del 93% de los residuos van directo a disposición final.

- únicamente 11 Estados cuentancon estaciones de transferencia.

- 19 Estados cuentan con plantas de tratamiento de RSU.
