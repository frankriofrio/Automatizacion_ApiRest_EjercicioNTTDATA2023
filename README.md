# Automatizacion_ApiRest_EjercicioNTTDATA2023

Por: Francisco Geovanny Riofrio Terrazas
Ejercicio 2: PetStore
1.- Obtener los productos de su tienda y validar que uno de sus productos estrellas con un rate de 4.8, tenga un id 11, su categoria corresponda con electronics y su titulo coicida con "Silicon Power 256SSD 3D NAND ASS SLC Cache Perfomance Boost SATA III 2.5"
2.- Validar que el catalogo de productos, cuando busca por categoria electronics, venga 6 productos en total y que este el producto con id 11.


## Requisitos

Para ejecutar el proyecto es necesario tener instalado lo siguiente:

  - Maquina local con el sistema operativo Debian 11.0
  - JDK versión 1.8 (debe estar en la variable de entorno)
  - Intellij-Idea Comunity o Ultimate version 2023.1.2
  - Gradle 8.0



## Ejecucion
- Para ejecutar el proyecto
        1. Abrir el IDE IntellijIdea
        2. Ingresar en la opción File -> Open y ubicarse en el proyecto (abrir)
        3. Esperar unos minutos para que se descargen las despendencias (gradle)
        4. Opciòn 1: Ubicarse y ejecutar la clase RunnerforExercise.java (src/test/java/crudUser/RunnerforExercise.java).
            - La clase ejecutara los features de forma ordenada según el ejercicio realizado
            - ## Reporte Karate: Una vez finalizada la ejecución se crea el informe propio de Karate para visualizarlo ubicarse en la ruta target/karate-reports/karate-summary.html
        5. Opción 2: Ubicarse y ejecutar la clase ManagementTest.java (src/test/java/crudUser/ManagementTest.java).
            - La clase ejecutara los features de forma ordenada según el ejercicio realizado
            - ## Reporte Cucumber Una vez finalizada la ejecución se crea el informe realizado con Cucumber para visualizarlo ubicarse en la ruta build/cucumber-html-reports/overview-features.html

## Información adicional
Referencia karate: https://www.karatelabs.io/
Repositorio Karate: https://github.com/karatelabs/karate
Repositorio Francisco Riofrio Terrazas: https://github.com/frankriofrio/Automatizacion_ApiRest_EjercicioNTTDATA2023.git


