# **<center>Análisis De Datos Empresariales </center>**

### Datos Academicos
  - **Institucion:** Universidad Nacional De San Antonio Abad Del Cusco
  - **Facultad:** Facultad De Ingenieria Eléctrica, Electrónica, Informática y Mecánica
  - **Escuela Profecional:** Ingenieria Informatica Y De Sistemas
  - **Actividad: Impacto Covid-19 en las Empresas**


  #### Autores:
  #### - Docente :
  - **_GARCIA ZANABRIA GERMAIN_** - _Docente_ - [Concytec](https://ctivitae.concytec.gob.pe/appDirectorioCTI/VerDatosInvestigador.do?id_investigador=34979).
  #### - Estudiantes:
  - **_INCA CRUZ CARLOS EDUARDO_** - _GitHub Account_ - [CarlosEdu322](https://github.com/CarlosEdu322)
  - **_QUISPE CHAMBILLA CARLOS ENRIQUE_** - _GitHub Account_ - [Carlinpe](https://github.com/Carlinpe)
  - **_QUISPE PALOMINO LUIYI ANTONY_** - _GitHub Account_ - [luiyiAntony](https://github.com/luiyiAntony)


## Tabla de Contenido
- [Introducción: Descripción del problema]
- [FUENTE DE LOS DATOS]
- [DESCRIPCIÓN DEL DATASET]
- [ANALITICAL TASKS]
- [GRÁFICAS DE ANÁLISIS]
- [INSIGHTS]

## Introducción
### Problema
Uno de los problemas que trajo consigo el Covid 19 fue que muchas empresas tuvieron que dejar de operar para evitar más contagios, con ello se redujeron las ventas y se generó mucho desempleo.
El objetivo es analizar cuál fue el impacto del Covid 19 en las empresas del Perú.

## Fuente de los datos
Los datos fueron extraidos de la base de datos de la [INEI](http://iinei.inei.gob.pe/microdatos/). La consulta que se realizó fue:
![image](https://user-images.githubusercontent.com/111087121/186062413-a5b363cd-871c-4544-bb1b-f7bb5e9a7d38.png)

## Descripción del dataset
Las dimensiones del data set son:
- 929 registros
- 107 campos

La información según los campos se agrupan en:
- Localización de la empresa
- Datos del/de la informante
- Características de la empresa
- Impacto del COVID 19 en las empresas con respecto a:
  - Ventas
  - Empleo
  - Finanzas
  - Apreciación y expectativa (estimación de tiempo de recuperación y reactivación económica respectivamente)
  - Acceso a programas del gobierno
- Empresa inoperativa

[Diccionario Encuesta de impacto COVID 19.pdf](https://github.com/Carlinpe/Impacto_Covid19_Empresas/files/9399170/Diccionario.Encuesta.de.impacto.COVID.19.pdf)

## Analitical tasks
TASK 1:
Problemas que tuvieron las empresas con respecto a sus ventas, empleo y finanzas

TASK 2:
- ¿Cuán accesible y efectivo son los programa del gobierno? 
- ¿Que efecto tuvieron en las empresas?

TASK 3:
Que tipos de ayuda (financiamiento, reducción de restricciones, etc) se requiren para activar la mayoria de las empresas

## Gráficas de análisis
TASK 1:
Se requiere conocer cuales fueron los problemas que las empresas tuvieron con sus VENTAS.
Para ello se utilizó el sub-conjunto de datos "Ventas" dentro del conjunto de datos "Impacto del COVID 19 en las empresas", dentro de este sub-conjunto de datos tenemos un grupo de preguntas cuyas respuestas pueden ser 1 (afirmando) y 0 (negando):
<br>
PREGUNTA GENERAL: 
<br>
¿Cuáles son los principales problemas que enfrentó la empresa por causa del COVID 19 en el segundo trimestre 2020?
<br>
![problemas_con_respecto_a_las_ventas](https://user-images.githubusercontent.com/111087121/186069658-a0d3ffef-c208-47cb-83c6-9f99ee0fe274.jpeg)
<br>
Tambien se requiere conocer cuales fueron los problemas con respecto a sus FINANZAS
<br>
![problemas_con_respecto_a_las_finanzas](https://user-images.githubusercontent.com/111087121/186069747-58ad777c-d595-4ea5-a9c8-6702ac90377f.jpeg)
<br>
Y como afecto todos esos problemas a los empleados
<br>
[porcentaje de trabajadores](https://public.tableau.com/app/profile/luiyi.antony3599/viz/ImpactodelCovid19enlasempresasperuanas/Porcentajedetrabajadores)
<br>
![Porcentaje de trabajadores](https://user-images.githubusercontent.com/111087121/186076427-f7a70ea3-6090-416d-8069-7f493c29da9e.png)
<br>
¿Cuales fueron las medidas que tomaron las empresas con sus empleados? y ¿Por cual modalidad de ventas optaron?.
<br>
![medidas_que_optaron_las_empresas](https://user-images.githubusercontent.com/111087121/186069687-8343874b-96f5-4b14-b2f4-2daf54c60610.jpeg)
<br>
[modalidad de ventas](https://public.tableau.com/app/profile/luiyi.antony3599/viz/ImpactodelCovid19enlasempresasperuanas/Modalidaddeventas)
<br>
![Modalidad de ventas](https://user-images.githubusercontent.com/111087121/186076571-aca3b41d-c494-4a1b-8334-81f59dfdb56d.png)
<br>
Como resultado las empresas no pueden operar a toda su capacidad
<br>
[capacidad instalada operativa](https://public.tableau.com/app/profile/luiyi.antony3599/viz/ImpactodelCovid19enlasempresasperuanas/Capacidadinstaladaoperativa)
<br>
![Capacidad instalada operativa](https://user-images.githubusercontent.com/111087121/186076656-142ed84f-8475-4a1d-82e3-e09f13d9de30.png)

TASK 2:
<br>
![programas_de_gobierno_mas_accesibles](https://user-images.githubusercontent.com/111087121/186069875-ad1b3dce-fcde-4e18-a4cf-e281b6a8935e.jpeg)
![por_que_no_accedio_a_programas_del_gobierno](https://user-images.githubusercontent.com/111087121/186069903-030aa04d-6990-475c-8435-e589d52f524a.jpeg)
![porque_se_encuentra_inoperativa](https://user-images.githubusercontent.com/111087121/186069924-74ce1866-bbfd-4171-accb-f20bbe98c7fd.jpeg)

TASK 3:
<br>

- [Estimación de número de meses para que la empresa vuelva a los niveles de ventas antes de la pandemias](https://public.tableau.com/app/profile/luiyi.antony3599/viz/ImpactodelCovid19enlasempresasperuanas/volveralosnivelesdeventasantesdelapandemia)
- [Estimación de tiempo para la reactivación económica](https://public.tableau.com/app/profile/luiyi.antony3599/viz/ImpactodelCovid19enlasempresasperuanas/Estimaciónreactivacióneconómica)

## Insights




![Resultado](./SistemadeTutoria_Images/Cronograma.png)
