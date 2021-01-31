# Pruebas
## Objetivos de las pruebas

* El objetivo principal de nuestras pruebas deberia ser:
  + Mirar que el programa haga lo que querramos hacer 
  + Probar que el codigo no haga lo que no debería hacer

## Frameworks

Para realizar estas pruebas, usaremos **Frameworks**:
  + Un framework, es un software que contiene funcionalidades genéricas que nos pueden ir bien para nuestro código, y que podemos adaptar según nuestras necesidades.
  
En este caso, usaremos frameworks que nos sirvan para hacer pruebas, (programas ya preparados para hacer pruebas). De esta forma, en un grupo de trabajo si todos usan el mismo framework y hacen las mismas pruebas, podremos unificar el proceso de desarrollo entre desarrolladores.

## Forma de pruebas

Hay dos tipos de pruebas que podremos hacer a nuestro código, uno siendo **dinámicas** y la otra **estáticas**:

  + **Pruebas dinámicas:** ejecutaremos el programa y miraremos el funcionamiento de esta, mirando si hace lo que debería de hacer sin ningún fallo
  + **Pruebas estáticas:** leemos el código y miramos que no haya ningún error.

## Estrategias de prueba

Usaremos diferentes pruebas dependiendo de que tipo de situación estemos, podremos tener una **caja negra**, en la que no podremos acceder y por lo tanto no sabremos como está escrito el código. O podremos tener una **caja blanca** con acceso ilimitado para ver como esta estructurado el código.

![image](http://jamj2000.github.io/entornosdesarrollo/3/assets/caja_blanca-caja_negra.png)

## Pruebas a programas teniendo una caja negra

Como no tenemos acceso al código, siempre haremos pruebas desde fuera para ver el comportamiento de la caja negra, por lo tanto se proporcionaran entradas a la caja negra y se estudiaran las salidas.

## Pruebas a programas con caja blanca

Se examinará el código fuente y su estructura

## Tipo de pruebas

Tendremos pruebas **funcionales** y **no funcionales**.

  + **Funcionales:** pruebas que miran que el codigo se ejecute y no de error en ninguna parte. 
  + **No funcionales:** se mira el rendimiento del programa, tiempo de ejecución, uso de variables, longitud de código, etc.

## Mecanismos de pruebas

  + **Manual**
    + Pruebas realizadas por personal de la empresa o externa
  + **Automático**
    + Software que nos ejecutara el código y nos mostrará los resultados obtenidos por nuestro código y lo resultados esperados.

## Integración
Las pruebas integrales o de integración, son aquellas que se realizan durante el desarrollo del software una vez que se han aprobado las pruebas unitarias previamente comentadas.

El **objetivo**, es comprobar el correcto ensamblaje entre los distintos componentes que se han ido probando durante la fase del desarrollo.

## Cobertura del código
+ Se usa para indicar el porcentaje de cdigo que ha sido ejecutado durante las pruebas.
+ Lo mejor esque este lo más cerca del 100%, asi no tendremos líneas de código sin usar.
+ La cobertura se puede llevar a cabo tanto desde el IDE, como desde un servicio web apropiado.

## Calidad
Para ver si nuestro código fuente está bien diseñada, tendremos que hacer un control de calidad, en esta, miraremos la **calidad en los procesos** y la **calidad de los productos**.
+ **Calidad en los procesos (QA)**: son los metodos, procesos, líneas de código que usamos, y se mira si está bien estructurado, si tiene lógica las funcionalidades que hacen, etc.
+ **Calidad de los productos (QC)**: se mira que no haya ningun defecto en el producto final producido.

## Factores de calidad
Los factores de calidad, se basan en el **Modelo de Calidad de McCall**, en la que se tiene 3 grandes grupos: **Revisión**, **Operación**, **Transición**
