##  ELECTRÓNICA DIGITAL 2 2019 -2 UNIVERSIDAD NACIONAL DE COLOMBIA 

## ENTREGAS DEL PROYECTO  

GRUPO  | Entrega WP01  | Entrega WP02  |  Entrega Final 
--     | --            | --            |  --            
G01    |  [documento](https://github.com/unal-edigital2-2019-2/work01-camara-grupo_1/tree/master/docs/README.md) [repositorio](https://github.com/unal-edigital2-2019-2/work01-camara-grupo_1) | [documento](https://github.com/unal-edigital2-2019-2/work02-simulation-grupo_1/tree/master/docs/README.md) [repositorio](https://github.com/unal-edigital2-2019-2/work02-simulation-grupo_1) | [documento](https://github.com/unal-edigital2-2019-2/work03-lm32-grupo-1/tree/master/docs/README.md) [repositorio](https://github.com/unal-edigital2-2019-2/work03-lm32-grupo-1) 
G02    |  [documento](https://github.com/unal-edigital2-2019-2/work01-camara-grupo-2/tree/master/docs/README.md) [repositorio](https://github.com/unal-edigital2-2019-2/work01-camara-grupo-2) | [documento](https://github.com/unal-edigital2-2019-2/work02-simulation-grupo-2/tree/master/docs/README.md) [repositorio](https://github.com/unal-edigital2-2019-2/work02-simulation-grupo-2) | [documento](https://github.com/unal-edigital2-2019-2/work03-lm32-grupo-2-1/tree/master/docs/README.md) [repositorio](https://github.com/unal-edigital2-2019-2/work03-lm32-grupo-2-1) 

## Proyecto

El trabajo presentado a continuación  tiene como objetivo diseñar  un sistema autónmo capaz  de navegar  y trazar un laberinto al mismo tiempo que  procesar imagenes de objetos por color. 

En las próximas 5 semanas se estará trabajando en la adquisición, procesamiento y visualización de  imágenes. Para ello se hará uso de los siguientes componentes:

* Cámara OV7970 sin FIFO con las siguientes características:
* Tarjeta STM o Arduino, usado para la navegación del  robot autonomo
* Tarjeta de desarrollo FPGA, Nexys4, quacho-basic  para ka adquisición y  procesamiento de imagen
* Sistema de visualización.
* Sensores y actuadores según seleccione el grupo.

![Diagrama](./docs/figs/escenario.png)


## Metodología de trabajo 

Para cada paquete de trabajo se debe clonar la plantilla dada, y los resultados del trabajo de cada grupo deben ser subidos antes de la fecha estipulada. Se recomienda  leer la ayuda de github classroom en este [link](https://education.github.com/) y ver los videos de github de su canal de YouTube de este [link]( https://www.youtube.com/githubguides) o pueden descargar un libro de git del siguiente [link]( https://git-scm.com/book/en/v2)
Antes de empezar  si no ha tenido ningún acercamiento con los repositorios de git  debe realizar los siguientes pasos:
* Crear una cuenta de github. Ver este [video](https://www.youtube.com/watch?v=ezxRcdJ8glM&feature=youtu.be)
* Para crear repositorios  revise este [link](https://help.github.com/en/github/getting-started-with-github/create-a-repo)

Antes de comenzar con cada paquete de trabajo se debe leer las instrucciones  y tener todos los archivos. Para acceder a cada paquete de trabajo debe:
* Aceptar la asignación de cada link dado. 
* La aplicación les pregunta si desean crear un grupo nuevo o unirse a uno existente:
	* Para crear un grupo nuevo coloque "Grupo-xx", donde xx es el número del grupo.
	* Para unirse a un grupo existente, busque el nombre  y pulse el botón ´join´.
	
***Nota: Todos los estudiantes debes unirse al grupo correspondiente  y tener cuidado de no equivocarse de grupo***

Luego de unirse a cada grupo de trabajo debe clonar su  repositorio en su computador, para lo cual: 
* Si usted  no tiene ningún conocimiento de cómo hacer esto, recomiendo  usar ***github Desktop*** el cual se puede descargar de este [link]( https://desktop.github.com), y la documentación  de uso la encuentra en este [link](https://help.github.com/en/desktop/getting-started-with-github-desktop) ***Recuerde lo que debe hacer es clonar el repositorio creado de forma automática por git classroom y NO crear uno nuevo***
* Para los estudiantes que usen el sistema operativo Linux  les recomiendo usar la siguiente guía para clonar el repositorio e iniciar en  el mundo de  control de versiones [link]( https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository)

***RECUERDEN:*** Todos los integrantes del grupo deben  trabajar en el respectivo repositorio y participar en los respectivos commit y push, tanto de la documentación

## Documentación
Para todos los paquetes de trabajo se debe  realizar  la documentación respectiva, que evidencie el progreso del trabajo. Puede hacer uso de fotos, videos, comentar el código HDL, y todo lo que el grupo considere necesario  para explicar los avances que va teniendo. 
Recuerde el trabajo que ustedes documenten, será el que leerán sus compañeros de los próximos semestres. En este contexto, la evaluación de la documentación será  tenida en cuenta la minuciosidad y claridad de la misma.

La documentación se debe  diligenciar en el archivo README.md, que se encuentra en cada repositorio dentro de la carpeta docs, en el cual deben colocar el nombre3 de los integrantes  y el  número de identificación.
El archivo README.md, se debe escribir en formato Markdown. Para aprender cual es el formato de este documento se recomienda revisar el siguiente [link](https://guides.github.com/features/mastering-markdown/) que les da una visión rápida de formato usado para hacer la documentación. 
Las imágenes, fotos y soportes gráficos deben ser alojados en la carpeta ‘figs’ y deben ser vinculadas en documento README.md.

## Descripción de Hardware
El código HDL está alojado en la carpeta ***hw***. Allí  están los archivos fuentes dados en clase  y allí deben alojar todo los archivos  diseñados  y desarrollados por los integrantes de grupo y según sea solicitado en la  guía de cada paquete de trabajo.

## Descripción del firmware
El código del firmare debe se alojado en la carpeta ***sw***. Allí  están los archivos fuentes dados en clase  y allí deben alojar todo los archivos  diseñados  y desarrollados por los integrantes de grupo y según sea solicitado en la  guía de cada paquete de trabajo.

## Entrega
Recuerde tener presente el deadline  de cada paquete de trabajo, a las 8 de la noche del día indicado  se cierra  el sistema  y los grupos no podrán actualizar el repositorio.
Para actualizar el repositorio deben realizar  el respectivo commit y push, según sea la plataforma que estén utilizando y como se explicó en clase.
Recuerda también revisar que en la página de github se refleja las actualizaciones realizadas por el grupo de trabajo 
  

## Desarrollo 
A continuación se presenta cada actividad a realizar, el plan de trabajo del proyecto de cada semana se encuentra en el link de documentación y el link de trabajo se encuentra en la columna  repositorio.



WP  | semana | deadline  | Tema | Documentación| Repositorio 
--  | --     | --        | --   | --          | --  
01| semana 1 | 15 Nov | Captura de datos de la Cámara | [link](./docs/WP01.md) | [WP01](https://classroom.github.com/g/sHf0ZmsW) 
02 | semana 2 | 22 Nov | simulación | [link](./docs/WP02.md) | [WP02](https://classroom.github.com/g/uuy_pxdA)  
03| semana 3 | 13 febrero | Envió de Información | [link](./docs/WP03.md) | [WP03](https://classroom.github.com/gvxvPzoJs)

