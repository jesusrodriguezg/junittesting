# junittesting
Ejercicio de creación de una suite de testeo simultáneo de dos clases Java usando el framework JUnit. Realizado como parte de la asignatura de Entornos de Desarrollo del Ciclo Formativo de Desarrollo de Aplicaciones Web del IES Polígono Sur de Sevilla.

## Instrucciones

1. Clonamos el repositorio.

  `$ git clone https://github.com/jesusrodriguezg/junittesting`

2. Compilamos las clases. Para ello debemos ejecutar el compilador de Java (javac) desde la línea de comandos, indicándole como parámetros la ubicación de las clases .java y del archivo .JAR  de JUnit. Es preciso que la versión del framework sea la 4.8.1.

  `javac -cp /home/jesu/junit-jar/*:. *.java`

3. Ejecutamos el test. Para ello, una vez que tengamos compìladas las clases, ejecutamos en la línea de comandos la clases JunitTestED indicando como parámetro la ubicación del framework JUnit y del paquete JUnitCore, como se indica a continuación.

  `$ java -cp /home/jesu/junit-jar/*:. org.junit.runner.JUnitCore JunitTestED`

4. Comprobación de errores. Si los tests son adecuados, la línea de comandos deberá indicarnos que todas las comprobaciones han tenido éxitos. En caso contrario, indicará los correspondientes errores.
