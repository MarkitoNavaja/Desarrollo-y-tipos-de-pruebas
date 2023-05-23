# PATRONES GOF
  El diminutivo "GOF significa "Ganf of Four" que traducido al español significa "La banda de los cuatro" que esta conformado por Ralph Jhonson, Erich
  Gamma, Richard Helm, John Vlisides, estas 4 personas escriben un libro hacerca de los patrones de diseño en 1987 y apartir de 1990 los patrones tuvieron
  muchisimo exito en el mundo de la informatica.
  
  Los patrones GOF se aplican en soluciones de diagrama de clases o de comportamiento de las clases de como vamos a realizar las clases a pensar de que pueden
  existir muchos otros patrones especificos para tecnologias.
  
  ## Clasificación:
  
  ### Patrones de creación:
  Son formas de crear instancias ya sea extraer, ocultar, como son creados y inicializados los objetos para hacerlo de una forma mas facil.
  ### Patrones estructurales:
  Trata sobre como se combinan las clases y los objetos para formar nuevas estructuras. 
  ### Patrones de comportamiento:
  Definen la comunicación e interacción de los objetos y van a reducir el acoplamiento 
  
  ## ¿Como usarlos?
  
  1. tenemos que identificar cual es el problema al cual el patron utilizado se va a ejecutar. 
  2. Conocer la solución generica que propone ese patron para la problematica
  3. Evaluar la posibilidad de si vamos a aplicar el patron a nuestro problema
  4. Adaptar esa solucion generica del patron a nuestro problema especifico (cambiar los nombres de las clases, revisar metodos e implementar los
  metodos necesarios a nuestra solución.
  
  ## Plantilla para documentar y leer un patrón.
  
  1. Nombre del patron: Algo que debemos recordar para poder comunicarnos de manera efectiva.
  2. El problema a resolver: Esto nos ayuda para saber cuando aplicar el patron, se describe el problema o el contexto en el cual nos vamos a encontrar ese problema.
  3. Solucion prevista: Escribir los elementos que conforman el diseño atravez de una descripción de ese problema y como se va a organizar las clases y objetos
  para resolver el problema en la solucion propuesta del patron.
  4. Consecuencias (Buenas o Malas): Se habla del impacto que peude tener ese patron al aplicarlo.
# Pruebas de software
   Las pruebas de software permiten controlar la calidad y funcionalidad de cualquier producto que se desarrolle; son la mejor garantía de que este no 
   presenta fallos y se comporta adecuadamente,Las pruebas de software son el mejor método para confirmar la funcionalidad del producto que se está 
  desarrollando. 
  Deben aplicarse en todas las fases del desarrollo, desde el inicio del proyecto hasta el final, de manera que puedan descubrirse fallos aislados en un 
  primer momento o detectar un comportamiento erróneo al final.
  Clasificación:
  Patrones de creación: 
  Estas pruebas sirven, por ejemplo, para descubrir fallos en el diseño y la arquitectura del software, en la seguridad o en la escalabilidad.
## Tipos de pruebas
  1. Pruebas unitarias o unit testing:
    Estas pruebas se aplican de manera individual y son las primeras que deben realizarse durante todo el proceso de desarrollo.
    Para ello, es necesario aislar esas unidades, que pueden ser fragmentos de código, para verificar su comportamiento. Al trabajar con unidades tan 
    pequeñas es posible testear el proyecto por partes, sin necesidad de que esté terminado. Son muy rápidas y facilitan la comprobación de la 
    legibilidad del código.
  2. Pruebas de integración:
    El objetivo de estas pruebas es comprobar que los diferentes componentes operan bien juntos. En ocasiones sucede que un módulo que funcionaba 
    perfectamente de manera aislada, una vez que se integra con el resto provoca algún tipo de fallo en el sistema, por lo que es necesario supervisar 
    esa integración para obtener los mejores resultados.
  3. Pruebas funcionales:
    Lo que se comprueba son las funciones del software creado para establecer la usabilidad y las características de cara al mercado. Son consideradas 
    pruebas de caja negra o black-box testing porque lo que se verifica es el comportamiento del sistema, si todo funciona tal y como está establecido en 
    el documento Software Requirement Specification (SRS).
  4. Pruebas de aceptación:
    Durante las pruebas unitarias y de integración se realizarán las pruebas de aceptación para corroborar que todo el sistema funciona según lo 
    esperado.
  5. Pruebas de estrés:
    Antes de dar por finalizado el proceso de desarrollo de una software es necesario comprobar cuánta tensión puede soportar antes de que se produzca 
    algún error. Para ello, se envía mucha más información de lo habitual para comprobar en qué punto se satura el sistema.
    Como se puede observar de acuerdo a la investigacion pasada es necesario hacer pruebas para determinar si el software es funcional y existen un sin 
    fin de pruebas para ello,se debe buscar el metodo mas adecuado para cada software que logre satisfacer la nacesidad.
    Es de vital importancia realizar estas pruebas dado que antes que salga al live el software debe tener la menor cantidad de errores para lograr 
    fixearlos en tiempos cortos.
 ## METODOLOGIA PARA IDENTIFICAR PATRONES GOF
 La metodología para identificar patrones GOF (Gang of Four) en el desarrollo de software se basa en un conjunto de actividades. Primero, se establecen criterios para seleccionar los procesos de desarrollo más representativos que cumplen con un estricto control de calidad en las fases de requerimientos, diseño, desarrollo e implantación. Estos criterios incluyen la cantidad de desarrolladores involucrados, el uso de diseños UML, la criticidad del sistema, los costos del proyecto, el modelo de requisitos utilizado y el modelo de calidad adoptado.
1. Cantidad de Desarrolladores: La cantidad de desarrolladores influye en la complejidad del proyecto, ya que un equipo numeroso requiere estrategias para optimizar el tiempo y los recursos. Se establece un mínimo de desarrolladores para cumplir con este criterio.
2. Diseños UML - Unified Modeling Language (Schach, 2005): El uso de diseños UML es importante, ya que los patrones de diseño tienen su estructura definida a partir de los diagramas de clases UML. Por lo tanto, los proyectos deben emplear UML en la etapa de diseño.
3. Criticidad de los Sistemas: La criticidad del sistema se refiere al nivel de necesidad de la aplicación para los usuarios. Se clasifica en niveles bajo, medio y alto, y los sistemas con niveles bajos se consideran irrelevantes para el análisis.
4. Costos: Los costos del proyecto no garantizan el éxito, pero un mayor costo implica destinar más recursos humanos a procesos de calidad. Se establecen categorías de costo para la selección de proyectos.
5. Modelo de Requisitos: El modelo de requisitos utilizado al inicio del proyecto es un factor importante, y se definen estándares como IEEE 830-1998 y una plantilla de requisitos de Amador Duran Toro.
6. Modelo de Calidad: El modelo de calidad adoptado asegura que el proceso y el producto satisfagan las expectativas del cliente. Algunos modelos utilizados son CMMi, ISO 9001 e ISO 9126.
### Selección de la muestra
Una vez establecidos los criterios, se selecciona una muestra de proyectos de desarrollo que cumplan con dichos criterios. Para determinar el tamaño de la muestra, se aplica una metodología estadística que considera una población infinita o desconocida.
### Aplicación de Criterios Propuestos
En la aplicación de los criterios a la muestra, se descartan los proyectos que no cumplen con los valores establecidos para cada criterio. Los criterios se aplican secuencialmente, y se analiza la cantidad de desarrolladores, el uso de diseños UML, la criticidad del sistema, los costos, el modelo de requisitos y el modelo de calidad. Cada criterio elimina proyectos que no cumplen con sus requisitos, y al final se obtiene una muestra de proyectos que continúan para el análisis de identificación de patrones GOF.

En resumen, la metodología se basa en establecer criterios para seleccionar procesos de desarrollo que cumplan con estándares de calidad en diferentes aspectos. La aplicación de estos criterios permite obtener una muestra de proyectos que serán analizados para identificar patrones GOF en el código fuente.

    
