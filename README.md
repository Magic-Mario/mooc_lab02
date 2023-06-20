# Puntos a Tener en Cuenta a la Hora de Crear Tu Propio MOOC

En este proyecto, se llevará a cabo un análisis del modelo de negocio de tres reconocidos MOOCs, como son Udemy, edX y Coursera. Se destacarán puntos clave que deben tenerse en cuenta al crear un MOOC. El repositorio consistente en:

- EDA notebook
- Imagen de Word Cloud
- Dashboard de Power BI




## Tecnologias Utilizadas

- EDA: Pandas, numpy, matplotlib y seaborn
- Word Cloud: Word Cloud
- Dashboard: Power BI




## Arquitectura del repositorio

```
--> datasets
    - edx_courses.parquet
    - full_coursera.parquet
    - udemy_courses.parquet

--> img
    - Aprendizaje.img

moocs_henry.pbix

--> notebooks
    - transforms_eda.ipynb 
```



## Desarrollo de Proyecto
A continuación, se explicará el análisis realizado a los tres conjuntos de datos disponibles y los puntos clave identificados de cada MOOC y sus KPIs.

### Udemy

Durante el análisis del dataset perteciente a Udemy nos econtramos en primera instancia que es la plataforma con menor numero de usuarios suscritos `12M`, a pesar de ser la plataforma con mas cursos disponibles con un total de `3657`, esto puede ser debido a las pocas variaciones en la tematica del contenido  de sus cursos, solo `4`, las cuales son *Desarrollo Web, Finanza de negocios, Diseño gráfico* e *Instrumentos musicales*. Udemy tambien cuenta con la particularidad de tener un 93,26% de sus cursos con un nivel introductorio y tener un 91.63%, de sus cursos totales, de caracter pago y con un precio promedio de `$66.06`.

***KPIs***

- Cantidad de Estudiantes: 12M
- Cantidad de Cursos disponibles: 3657
- tematicas Disponibles: 4
- Precio Promedio de los cursos: $66.06

### edX

Durante el análisis del dataset perteciente a la plataforma de edX podemos encontrar una cantidad de usuarios suscritos a sus cursos de `45.54M`, mas de 4 veces a Udemy ¿Razones? `31` tematicas diferentes divididas en `972` cursos disponibles; tematicas que abordan desde Ingenieria hasta humanidades; muy diferente de Udemy, ¿cierto? La plataforma de edX tambien cuenta con la ventaja de tener cursos en diferentes idiomas nativos, ademas de subtitulos. La plataforma de edX cuenta con 111 instituciones que generan contenido para la plataforma, lo mas importante para remarcar de estas plataformas es que todas son instituciones educativas o tecnologicas expertas en brindar esta clase de material educativo, a diferencia de Udemy, la cual es una plataforma que permite a cualquier usuario vender sus propios cursos en la plataforma. 

La plataforma de edX tiene todos sus cursos gratis para los usuarios, pero todas las certificaciones de finalizacion de curso son pagas; estas certificaciones cuestan en promedio `$100.47`.

***KPIs***
- Cantidad de Estudiantes: 45.54M
- tematicas de Cursos diferentes: 31
- Cantidad de Cursos Disponibles: 972
- Precio Promedio de certificaciones: $100.47

### Coursera

Coursera es la plataforma mas popular de las 3 contando con `154` instituciones educativas diferentes con `888` cursos diferentes disponibles en ella y `71.54M` usuarios inscritos a al menos un curso con 3 modalidades de certificaciones diferentes; *Cursos, Certificaciones profesionales* y *Especializaciones* para niveles iniciales, intermedios, avanzados y mixtos. Todas las certificaciones de Coursera cuentan con precio que varia segun la institucion y la duracion de la certificacion, aunque tambien existe la opcion de auditar estos cursos y aplica la misma estrategia que edX; hay que mencionar que no esta disponible para todo el contenido de los cursos esta opcion.

Coursera tiene una ventaja muy importante por sobre todas los demas MOOCs, su alto Rating Promedio por contenido `4.68`, lo cual nos lleva a la premisa de que en Coursera prima la calidad de contenido.

***KPIs***
- Organizaciones Disponibles: 154
- Rating Promedio: 4.68
- Cursos Disponibles: 888
- Usuarios inscritos: 71.54M


### Conclusiones

Los MOOCs puede llegar a ser negocio muy rentable a la hora de atraer gran cantidad de usuarios. Las recomendaciones que se harian al cliente para adentrarse en este negocio serian:

1. Crear contenido de diferentes de gran variedad de tematicas, si es posibles, debido a como podemos evidenciar en las platformas de edX y Coursera, a mayor variedad de tematicas mas publico se vera atraido por la plataforma.

2. Diferentes grados de complejidad en el contenido, el material introductorio a cualquier tematica es muy importante, pero es el mas comun, cuando quieres seguir adentrandote en una tematica o linea de estudio, es complicado encontrar material de estudio mas avanzado y ligado a este tema. Esta es una ventaja que podemos encontrar en la plataforma de Coursera con las Especializaciones y Certificaciones profesionales.

3. Organizaciones educativas, este es el principal punto, bajo opinion propia, del triunfo de los MOOCs de edX y Coursera, el nombre o prestigio de las Organizaciones o entes, que imparten contenido educativo es muy importante a la hora de permitar al usuario decantarse por un curso u otro.
