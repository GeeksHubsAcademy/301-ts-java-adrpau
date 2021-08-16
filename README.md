<p align="center">
    <img src="https://github.com/GeeksHubsAcademy/2020-geekshubs-media/blob/master/image/logo.png" >	
</p>


	Considere el siguiente problema:

	Dada un número entero que actúa como el límite máximo del tamaño de la secuencia, se desea calcular una 
    montaña de números.
    
	Cada escalón se genera a través del empareamiento de dos de ellos en cada fila excepto la primera fila.
    En este caso base, ésta siempre empezará en 1. Por otro lado, el primer elemento y el último siempre será 1.
    La suma del elemento se hace a través de parejas de dos números consecutivos.

	Montaña :     2              3                   4

	Ejemplo:

	              1              1                   1 
                1   1          1   1               1   1
                             1   2   1           1   2   1
                                               1   3   3   1
   
    Notas:
    
    Tenga en cuenta los espacios entre elementos.
    El algoritmo debe de ser óptimo.

    En la carpeta 'src/main/java/es/geekshubs/academy/Monta.java' se encuentra el fichero con la definición 
    de nuestro método vacío.
    En la carpeta 'src/test/java/es/geekshubs/academy/MontaTest.java' se encuentra el fichero con la suite de test.

    El modus operandi de trabajo es el siguiente:
    
    Debes 'forkear' el proyecto a tu cuenta.
    Puedes hacer PR's ilimitadas e ir validando poco a poco la solución contra nuestro respositorio con CI.
    Puedes trabajar en local y subir la solución haciendo un PR a nuestro repositorio.
    Cuando se envíe la PR final, debes indicar el tiempo de dedicación y los intentos que has hecho.
    También puedes añadir un comentario para dar cualquier tipo de feedback.
    
    En caso de duda, revisa en el apartado de 'Referencias'.

    [INFO] -------------------------------------------------------
    [INFO]  T E S T S
    [INFO] -------------------------------------------------------
    [INFO] Running es.geekshubs.academy.MontaTest
    [INFO] Tests run: 8, Failures: 0, Errors: 0, Skipped: 0, Time elapsed: 0.118 s - in es.geekshubs.academy.MontaTest
    [INFO]
    [INFO] Results:
    [INFO]
    [INFO] Tests run: 8, Failures: 0, Errors: 0, Skipped: 0
    [INFO]
    [INFO] ------------------------------------------------------------------------
    [INFO] BUILD SUCCESS
    [INFO] ------------------------------------------------------------------------
    [INFO] Total time:  3.763 s
    [INFO] Finished at: 2021-05-21T10:09:45+02:00
    [INFO] ------------------------------------------------------------------------

    Process finished with exit code 0 

## Referencias

* [Tutorial - Testing Automatizado](https://github.com/GeeksHubsAcademy/2020-js-vanilla-testing-FFFF/blob/master/README.md)
