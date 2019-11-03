# 02 ¿Qué es Ionic?                                                                                 11 clases    53:25
 
## Introducción a la sección                                                                                     01:25

## Temas puntuales de la sección                                                                                 00:29

Esta sección introductoria está enfocada en lo siguiente:

* Aprender ¿qué es ionic?
* ¿Cómo funciona?
* Diferencias entre una aplicación híbrida vs una nativa
* ¿Cuándo usar ionic y cuando pensar en nativo?
* Pro y contras de ionic
* Pro y contras del código nativo
* Estructura de un proyecto de ionic
* Depurar nuestra aplicación de varias formas
* Ionic Lab - instalación y uso

## ¿Qué son las aplicaciones híbridas?                                                                           02:57

<img src="/02QueEsIonic/01Presentaciones.png" />

Vamos a comenzar hablando sobre qué son las aplicaciones nativas.

<img src="/02QueEsIonic/02Presentaciones.png" />

En sus inicios si nosotros queríamos trabajar y crear aplicaciones para iOS Android o Windows Phone. Tendríamos que usar el **Software Development Kit** más conocido como **SDK** propio de cada una de esas plataformas. En pocas palabras para programar en **iOS** ocupamos saber **Swift** o bien **Objective-C**, para desarrollar en **Android** ocupamos saber **Java** o **Kotlin** y para **Windows Phone** ocupamos saber **C#**.

<img src="/02QueEsIonic/03Presentaciones.png" />

Esto conlleva a ciertos problemas, crear una aplicación móvil implica por lo menos desarrollar en **iOS** y **Android** lo que significa que nosotros vamos a tener que manejar dos o tres bases de código, es decir el código de Swift y el código de Java.

Contratar desarrolladores especializados en el código nativo es mucho más caro según **[Gartner]**(https://www.gartner.com/en) que es una página especializada en información estadística dice que para el 2022 el 70 por ciento de las interacciones que se van a realizar en la web serán a través de dispositivos móviles.

<img src="/02QueEsIonic/04Presentaciones.png" />

Ahora los tiempos han cambiado desde entonces y ahora también tenemos la opción de las aplicaciones híbridas. Qué en resumen, esto es lo que hacen, tanto como Swift, Java y C#, tienen un componente llamado Web-View, en el cual nosotros podríamos correr ahí nuestra aplicación que básicamente es HTML, CSS y JS.

El Web-View está creado en C#, Java y ObjectiveC, que **Ionic** junto a **Cordova** lo crean de forma automática para que nosotros nos enfoquemos en la creación directa de nuestra aplicación.

<img src="/02QueEsIonic/05Presentaciones.png" />

La pregunta más común es, ¿Por qué seleccionar aplicaciones híbridas? ¿Qué beneficio tengo?. 

1. **velocidad**:

   Codificar una aplicación en una única base de código hace que puedas entregar las aplicaciones en múltiples plataformas entre 2 a 3 veces más rápido que el código nativo.

2. **Mejor soporte**:

   Una aplicación híbrida tiende a ser más fácil de dar soporte sin contar que no necesitas personal especializado en el código nativo.

3. **Un ínico canal**:
   Las aplicaciones híbridas pueden correr en donde sea que la web corra. En un desktop, un móvil, una PWA, en un carro que tenga un navegador web que use GPS, cualquier cosa.
   
<img src="/02QueEsIonic/06Presentaciones.png" />
   
Pero ¿Qué es una aplicación híbrida?

Las aplicaciones híbridas son esencialmente aplicaciones nativas. Que inclusive se pueden descargar e instalar a través de las respectivas AppStore.

Una aplicación Ionic en su mayoría son irreconocibles de una aplicación nativa y la mayoría de los usuarios nunca sabrá la diferencia.

Las aplicaciones híbridas pueden acceder a los mismos recursos nativos y tienen un performance acelerado por hardware como si fuera creada con su SDK nativo pero está corriendo en el fondo código de HTML JS y CSS para comprender un poco mejor la diferencia de lo que es el híbrido versus un código nativo. Lo vamos a detallar a continuación en el siguiente video.

## Híbrido vs Nativo                                                                                             08:52

<img src="/02QueEsIonic/07Presentaciones.png" />

Es momento de aclarar las diferencias entre híbrido y nativo.

<img src="/02QueEsIonic/08Presentaciones.png" />

Muy importante es imprescindible tener en mente que la decisión de escoger entre híbrido o nativo debe de ser basada en los objetivos de tu organización.
Ionic por su lado le apuesta al gran poder que tiene la web y su potencial de ser multiplataforma en un ambiente híbrido de desarrollo.
Espero que lo que les voy a mostrar a continuación te ayude a escoger la mejor aproximación para tu siguiente proyecto.

<img src="/02QueEsIonic/09Presentaciones.png" />

Empecemos con las aplicaciones híbridas. Por qué seleccionar híbrido. Primero que nada. Usa el talento que ya tienes muchos equipos de desarrollo ya tienen programadores que entienden HTML, CSS y JavaScript lo que hace que aprender Ionic sea más fácil y natural para ellos en lugar de aprender nuevamente un lenguaje de programación como Swift, ObjectiveC, C# o Java.

Los equipos pueden crear aplicaciones de alto rendimiento y correrlas directamente en cualquier dispositivo usando la tecnología que ellos ya conocen.

La comunidad de desarrolladores web es 30 veces más grande que la comunidad de desarrolladores de aplicaciones nativas. Esto ayuda muchísimo a la hora de enfrentar algún inconveniente o problema que nosotros tengamos. Ahora esto es más fácil que buscar entrenar y contratar especialistas. Sin contar que no centraliza el conocimiento en una única persona.

<img src="/02QueEsIonic/10Presentaciones.png" />


La mejor interfaz de usuario entre plataformas. 

Una consistente experiencia de usuario entre plataformas, dispositivos móviles y otros modos de interacción incluyendo los navegadores web, sólo es posible mediante aplicaciones híbridas.

Así como las aplicaciones nativas, las aplicaciones híbridas hechas en Ionic también son aceleradas por hardware. Lo que hace que las animaciones y las transiciones sean muy elegantes y llamativas.

<img src="/02QueEsIonic/11Presentaciones.png" />

Construyendo para el futuro

Las aplicaciones del futuro deberán correr en un creciente número y diversidad de plataformas ya sea relojes celulares, carros, aplicaciones médicas o equipos médicos en fin una gran cantidad de dispositivos.

Afortunadamente la web es la forma más usada de correr aplicaciones en el mundo.

Lástima que no todo sea perfecto.

<img src="/02QueEsIonic/12Presentaciones.png" />

Hay inconvenientes de las aplicaciones híbridas que ustedes deben de conocer.

1. **Mayor consumo de recursos**:

   * El uso de Web-View puede introducir un grado mayor de consumo en comparación de una app nativa.
   * La abundancia de Apis y el crecimiento de poder de los dispositivos hacen que este factor sea de menos consideración cada año.
   * Pero para juegos 3D o uso 3D en general o bien aplicaciones de alto performance o un performance intensivo lo híbrido no es la mejor opción.

Si bien plugins de terceros las aplicaciones híbridas pueden acceder a casi todas las características

nativas del dispositivo tales como la cámara o el giroscopio usando plugins plugins opensource como

los de Córdoba son muy populares pero eso añade un nivel adicional y complejidad a nuestra aplicación

que muchos consideran problemático.

Número 3 dependencias de Frank guards escoger una aproximación multiplataforma significa que pondrás

tu confianza en un framework para mantener las mejores prácticas características y patrones de desarrollo

para cada aplicación.

Hoy unique está comprometido en mantenerse con las últimas versiones de Android e iOS es decir que se

esfuerza para que sufren luzca y se comporte lo más parecido a una interfaz de usuario nativa.

Y como mencioné anteriormente es muy difícil reconocer una aplicación hecha en ONIC que una aplicación

hecha en su país nativo.

Ahora miremos por qué escoger nativo.

Hay tres puntos principales 1 formas 2 gran librería de recursos nativos y 3 0 dependencia de terceros.

Comencemos con el performance.

Casi todas estas características se explican por sí solas el código nativo sigue siendo más rápido que

JavaScript y HTML.

Los navegadores web hoy en día ya cortan mucho esta brecha especialmente porque son acelerados por hardware.

Sin embargo lo nativo sigue siendo una ventaja aquí eso es importante cuando el desarrollador busca

crear aplicaciones de alta demanda gráfica como juegos o animaciones intensivas.

Luego tenemos una gran librería de recursos nativos usar el SDK nativo le permite al desarrollador usar

las últimas características diseñadas en estas plataformas sin la complejidad de lidiar con plugins.

Sin embargo la mayor parte del tiempo existen plugins para todo lo nativo que tú quieras hacer en un

híbrido pero no sabemos que saldrán mañana.

Y aquí es donde lo nativo tiene la ventaja.

Y por último cero dependencias de terceros a crear aplicaciones utilizando el Dickey nativo.

Los desarrolladores no están atados a recursos de terceros y no dependen a la comunidad open source

como cordobas quienes son los que han creado la mayor parte de los plugins para mantenerse al día con

las últimas características.

Normalmente si el dispositivo tiene una nueva característica también lanzarán su estic que te va a permitir

controlarlo mucho antes de que exista un plugin que te permita usarlo en una aplicación híbrida.

Ahora así como las aplicaciones híbridas inconvenientes en el desarrollo de las aplicaciones nativas

como por ejemplo los ciclos de desarrollo son mucho más largos especialmente cuando de crear aplicaciones

en múltiples plataformas se trata.

IOS tiene su forma de crear una lista.

Android y Windows Phone también.

La web también lo que implica que si nosotros ocupamos crear esto en varias plataformas el código es

diferente en cada una de ellas.

También reduce la agilidad de lanzar actualizaciones de nuestras aplicaciones.

Luego tenemos los altos costos de desarrollo si no lo has escuchado anteriormente desarrollar aplicaciones

nativas es más caro y usualmente toma mucho más trabajo hacerlas principalmente por el tiempo que demora

crear algo para cada plataforma que conlleva a contratar y mantener el talento de un desarrollador o

varios que están especializados en esa tarea.

Número 3.

El talento nativo es difícil de encontrar encontrar y contratar personal para iOS y Android es difícil

y consume tiempo y por lo general es caro y en muchos casos las personas especializadas en dispositivos

móviles de forma nativa dominan una plataforma iOS o Android y sí lo pueden hacer en ambos es aún más

caro contratarlos.

Muchas empresas prefieren contratar un desarrollador que pueda crear aplicaciones para iOS y Android

sin importar si son híbridas o nativas sus aplicaciones les voy a mostrar una tabla comparativa entre

lo que es nativo y un híbrido multiplataforma.

Empecemos con la habilidad necesaria para desarrollar algo nativo.

A saber o Yep si el iOS es Dickey y para Android ocupas saber Java y el Android es Dickey en un híbrido

multiplataforma lo que tú tienes que saber es HTML CSS y JavaScript más algún Framework en este caso

como ONIC.

El método de distribución de una aplicación nativa es las appstore.

Claro también se puede mandar por correo el iPad o a la pesca y se puede instalar de otras formas pero

no es tan sencillo.

El método tradicional de la instalación de una aplicación nativa es una AppStore en los híbridos.

Tú puedes instalarlo mediante las App Store.

De igual manera pero también tienes el navegador web una aplicación de escritorio como por ejemplo Electron

usar el navegador móvil o una Lewa en fin varias formas la velocidad de desarrollo es lenta en una aplicación

nativa por lo general y más aún si es multiplataforma en comparación de un híbrido que es bastante rápido

ya que tu solo codifica una vez el costo de mantenimiento en un nativo es medio alto dependiendo del

personal que tú contrates pero en comparación de un híbrido es mucho más barato.

Luego tenemos el performance gráfico una aplicación nativa es lo mejor que tú puedes obtener porque

todo corre de manera directa en el dispositivo.

En cambio en un híbrido hace una aplicación exigente 3D como mencionada anteriormente no es conveniente.

Luego tenemos el performance global de la aplicación en nativo es bastante alto.

Es un híbrido multiplataforma depende del caso de uso para la mayoría de las aplicaciones está bien

pero esto se aplica de la misma manera que el paso anterior depende mucho de la exigencia que tú hayas

hacer en tu aplicación.

Acceso a funcionalidad nativa en nativo tú tienes la librería completa que te ofrezca el dique.

En pocas palabras puedes usar todo lo que el dispositivo tenga en un híbrido multiplataforma tú puedes

acceder a casi todos los recursos nativos pero utilizando plugins.

Por último tenemos la consistencia entre diversas plataformas y dispositivos en una aplicación nativa.

No hay de otra tú tienes que crear una nueva aplicación para la nueva plataforma.

Puedes reutilizar servicios que hagas en tu Bakken.

Pero todo el código deberás volverlo a hacer.

Tanto para ellos como para Android como para la web y para todos los que tú quieres hacer en un híbrido

multiplataforma tu solo codificados.

Una vez y es el mismo código en todo lugar y en este caso hay Onix se encargará de que tu aplicación

se mire bien.

No importa en donde estés corriendo.

Hablemos ahora un poco sobre lo que es hoy ONIC pero en el siguiente video.

## ¿Qué es ionic framework?                                                                                      03:23
## Nuestra primera aplicación de ionic                                                                           07:55
## Estructura de un proyecto de ionic - Parte 1                                                                  14:50
## Estructura de un proyecto de ionic - Parte 2                                                                  05:04
## Ionic lab                                                                                                     02:45
## Depurar una aplicación de ionic - debugger                                                                    05:26
## Código fuente de la sección                                                                                   00:18

