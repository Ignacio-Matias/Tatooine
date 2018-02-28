# FLUJO DE TRABAJO CON GIT

![ramas-de-mantenimiento](https://etrivinos.files.wordpress.com/2016/01/ramas-de-mantenimiento.png)

### FLUJO DE TRABAJO GIT
El flujo de trabajo Git define un modelo de ramas estricto diseñado para las entregas de los proyectos, de tal forma que provee un área de trabajo robusta para la administración de proyectos empresariales.

Este flujo de trabajo asigna roles específicos a cada rama y define cómo y cuándo deben interactuar, utilizando un repositorio central como la vía de comunicación con los desarrolladores.

Gitflow maneja 4 tipos de ramas:

#### a. Ramas históricas.
Se utilizan dos ramas para contener el histórico del proyecto. La rama master quien actúa como la rama de entregas oficiales y la rama desarrollo que sirve como rama de integración a las ramas características.

![ramas-historicas](https://etrivinos.files.wordpress.com/2016/01/ramas-historicas.png)

#### b. Ramas características.
Cada nueva característica debe estar integrada en una rama independiente que deriva de la rama desarrollo. Cuando la rama característica se completa está se integra a la rama desarrollo.

![ramas-caracteristicas](https://etrivinos.files.wordpress.com/2016/01/ramas-caracteristicas.png)

#### c. Ramas de entregas.
Una vez la rama desarrollo ha adquirido suficientes características para catalogarla como una entrega, se crea una rama de entrega a partir de la rama desarrollo. En la rama de entrega creada se realizan correcciones menores, se anexa documentación entre otras cosas, sin anexar nuevas funcionalidades. Cuando la rama de entrega se encuentra lista se integra a la rama desarrollo y a la rama master.

![ramas-de-entrega](https://etrivinos.files.wordpress.com/2016/01/ramas-de-entrega.png)

#### d. Ramas de mantenimiento.
Estas ramas son usadas para corregir rapidamente una entrega en producción. Está rama se desprende de la rama master, tan pronto como el error se encuentre corregido la rama de mantenimiento es integrada en la rama master y la rama desarrollo.

![ramas-de-mantenimiento](https://etrivinos.files.wordpress.com/2016/01/ramas-de-mantenimiento.png)
