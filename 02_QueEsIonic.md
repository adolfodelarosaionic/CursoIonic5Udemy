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

3. **Un único canal**:
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

1. **Mayor consumo de recursos**

   * El uso de Web-View puede introducir un grado mayor de consumo en comparación de una app nativa.
   * La abundancia de Apis y el crecimiento de poder de los dispositivos hacen que este factor sea de menos consideración cada año.
   * Pero para juegos 3D o uso 3D en general o bien aplicaciones de alto performance o un performance intensivo lo híbrido no es la mejor opción.

<img src="/02QueEsIonic/13Presentaciones.png" />  

2. **Plugings de terceros**

Las aplicaciones híbridas pueden acceder a casi todas las características nativas del dispositivo, tales como la cámara o el giroscopio usando plugins.

Plugings opensource como los de Cordova son muy populares, pero eso añade un nivel adicional y complejidad a nuestra aplicación que muchos consideran problemático.

<img src="/02QueEsIonic/14Presentaciones.png" /> 

3. **Dependencias de Frameworks**

Escoger una aproximación multi-plataforma significa que pondrás tu confianza en un framework para mantener las mejores prácticas, características y patrones de desarrollo para cada aplicación.

Ionic está comprometido en mantenerse con las últimas versiones de Android e iOS, es decir que Ionic se esfuerza para que su framework luzca y se comporte lo más parecido a una interfaz de usuario nativa.

Y como mencioné anteriormente es muy difícil reconocer una aplicación hecha en Ionic de una aplicación hecha en su SDK nativo.

<img src="/02QueEsIonic/15Presentaciones.png" /> 

Ahora miremos ¿Por qué escoger nativo?

Hay tres puntos principales:

1. Performance
2. Gran librería de recursos nativos
3. Cero dependencia de terceros

<img src="/02QueEsIonic/16Presentaciones.png" /> 

Comencemos con el **Performance**.

Casi todas estas características se explican por sí solas. El código nativo sigue siendo más rápido que JavaScript y HTML. Los navegadores web hoy en día ya cortan mucho esta brecha especialmente porque son acelerados por hardware. Sin embargo lo nativo sigue siendo una ventaja aquí eso es importante cuando el desarrollador busca crear aplicaciones de alta demanda gráfica como juegos o animaciones intensivas.

<img src="/02QueEsIonic/17Presentaciones.png" /> 

Luego tenemos una Gran librería de recursos nativos, usar el SDK nativo le permite al desarrollador usar las últimas características diseñadas en estas plataformas sin la complejidad de lidiar con plugins.Sin embargo la mayor parte del tiempo existen plugins para todo lo nativo que tú quieras hacer en un híbrido pero no sabemos que saldrán mañana. Y aquí es donde lo nativo tiene la ventaja.

<img src="/02QueEsIonic/18Presentaciones.png" /> 

Y por último Cero dependencias de terceros.

Al crear aplicaciones utilizando el SDK nativo, los desarrolladores no están atados a recursos de terceros y no hay dependencia de la comunidad open-source como Cordova, quienes son los que han creado la mayor parte de los plugins, para mantenerse al día con las últimas características.

Normalmente si el dispositivo tiene una nueva característica también lanzarán su SDK que te va a permitir controlarlo mucho antes de que exista un plugin que te permita usarlo en una aplicación híbrida.

<img src="/02QueEsIonic/19Presentaciones.png" /> 

Ahora así como en las aplicaciones híbridas existen inconvenientes, también existen inconvenientes en el desarrollo de las aplicaciones nativas como por ejemplo:

1. Los ciclos de desarrollo son mucho más largos. 
   Especialmente cuando de crear aplicaciones en múltiples plataformas se trata. IOS tiene su forma de crear una lista. Android y Windows Phone también. La web también lo que implica que si nosotros ocupamos crear esto en varias plataformas el código es diferente en cada una de ellas.

   También reduce la agilidad de lanzar actualizaciones de nuestras aplicaciones.

<img src="/02QueEsIonic/20Presentaciones.png" /> 

Luego tenemos 

2. Los altos costos de desarrollo. 
   Si no lo has escuchado anteriormente desarrollar aplicaciones nativas es más caro y usualmente toma mucho más trabajo hacerlas principalmente por el tiempo que demora crear algo para cada plataforma que conlleva a contratar y mantener el talento de un desarrollador o varios que están especializados en esa tarea.

<img src="/02QueEsIonic/21Presentaciones.png" /> 

3. El talento nativo es difícil de encontrar.
   
   Encontrar y contratar personal para iOS y Android es difícil y consume tiempo y por lo general es caro y en muchos casos las personas especializadas en dispositivos móviles de forma nativa dominan una plataforma iOS o Android y sí lo pueden hacer en ambos es aún más caro contratarlos.

   Muchas empresas prefieren contratar un desarrollador que pueda crear aplicaciones para iOS y Android sin importar si son híbridas o nativas sus aplicaciones
   
<img src="/02QueEsIonic/22Presentaciones.png" /> 

Les voy a mostrar una tabla comparativa entre lo que es nativo y un híbrido multiplataforma. 

Empecemos con la **Habilidad necesaria** para desarrollar algo nativo. Necesitamos saber Objective-C, iOS SDK, y para Android ocupas saber Java y el Android SDK. En un híbrido multi-plataforma lo que tú tienes que saber es HTML, CSS y JavaScript más algún Framework en este caso como Ionic.

El **Método de distribución** de una aplicación nativa son las App Stores. Claro también se puede mandar por correo el IPA o la APK y se puede instalar de otras formas pero no es tan sencillo. El método tradicional de la instalación de una aplicación nativa es una AppStore. En los híbridos, tú puedes instalarlo mediante las App Store, de igual manera pero también tienes el navegador web, una aplicación de escritorio como por ejemplo Electron, usar el navegador móvil o una PWA, en fin varias formas.

La **Velocidad de desarrollo** es lenta en una aplicación nativa por lo general y más aún si es multi-plataforma en comparación de un híbrido que es bastante rápido ya que tu solo codificas una vez.

El **Costo de mantenimiento** en un nativo es medio alto, dependiendo del personal que tú contrates pero en comparación de un híbrido que es mucho más barato.

Luego tenemos el **Performance gráfico** una aplicación nativa es lo mejor que tú puedes obtener porque todo corre de manera directa en el dispositivo. En cambio en un híbrido hace una aplicación exigente 3D como mencionada anteriormente no es conveniente.

Luego tenemos el **Performance global de la aplicación** en nativo es bastante alto. Es un híbrido multi-plataforma depende del caso de uso para la mayoría de las aplicaciones está bien pero esto se aplica de la misma manera que el paso anterior depende mucho de la exigencia que tú hayas hacer en tu aplicación.

**Acceso a funcionalidad nativa** en nativo tú tienes la librería completa que te ofrezca el SDK, en pocas palabras puedes usar todo lo que el dispositivo tenga, en un híbrido multi-plataforma tú puedes acceder a casi todos los recursos nativos pero utilizando plugins.

Por último tenemos la **Consistencia entre diversas plataformas y dispositivos** en una aplicación nativa no hay de otra tú tienes que crear una nueva aplicación para la nueva plataforma. Puedes reutilizar servicios que hagas en tu Backend. Pero todo el código deberás volverlo a hacer, tanto para iOS como para Android como para la web y para todos los que tú quieres hacer. En un híbrido multi-plataforma tu solo codificas una vez y es el mismo código en todo lugar y en este caso Ionic se encargará de que tu aplicación se mire bien, no importa en donde lo estés corriendo.

Hablemos ahora un poco sobre lo que es Ionic pero en el siguiente video.

## ¿Qué es ionic framework?                                                                                      03:23

<img src="/02QueEsIonic/23Presentaciones.png" /> 

¿Qué es Ionic? 

<img src="/02QueEsIonic/24Presentaciones.png" /> 

Ionic es un framework open-source. Entiendan que la palabra **Framework** es **un marco de trabajo** es decir que si nosotros seguimos sus lineamientos nuestras aplicaciones van a lucir y van a funcionar como si fuera una aplicación nativa.

Ionic también nos ofrece un conjunto de herramientas que facilitan el desarrollo y las pruebas. 
Puedes desarrolladas para múltiples plataformas con el mismo código.
Ionic adapta su diseño dependiendo la plataforma en la cual estás corriendo.

<img src="/02QueEsIonic/25Presentaciones.png" />

Tú no te preocupas de nada de eso ahora nosotros aquí vamos a aprender Ionic utilizando Angular.

Angular es quien realiza la lógica de validación entre pantallas y la manipulación del HTML. 

También vamos a utilizar el sistema de rutas de Angular para navegar entre pantallas.

Podemos pensar que Ionic es quien nos va a dar a nosotros los controles y la forma de crear nuestras aplicaciones tomando el código de Angular y desplegarla en un dispositivo móvil y también vamos a utilizar ciertas cosas de Cordova que vamos a ver más adelante para poder desplegar nuestra aplicación en una AppStore y como mencioné anteriormente si nosotros seguimos unos lineamientos que nos da Ionic nuestra aplicación va a lucir exactamente igual a una aplicación nativa.

<img src="/02QueEsIonic/26Presentaciones.png" />

Solo para darles un ejemplo de lo que es hoy Ionic.

Déjenme mostrarles la [documentación oficial](https://ionicframework.com/) de ellos, ee el material adjunto yo les dejo a ustedes el URL [https://ionicframework.com/docs](https://ionicframework.com/docs) para que puedan llegar a esa documentación rápidamente, pero lo que les quiero explicar se encuentra aquí en la [pestaña de componentes](https://ionicframework.com/docs/components) al lado izquierdo tenemos todos los componentes prefabricados de Ionic para ayudarles a ustedes a crear rápidamente las aplicaciones y cómo se hace eso.

Bueno, ustedes no van a tener que perder el tiempo creando alertas, creando tarjetas, creando infinitas scroll, creando lo que es el pulso refresh, todo eso ya exist en Ionic y simplemente lo usamos.

Por ejemplo si quiero implementar un **Action Sheet** toco un botón y así se mira un Action Sheet en iOS.

<img src="/02QueEsIonic/action_sheet_ios.png" />

Si quiero verlo en Android toco el botón MD (Material Design) y así se mira.

<img src="/02QueEsIonic/action_sheet_md.png" />

Ionic se va a encargar de aplicar el estilo correspondiente dependiendo de la plataforma donde estamos corriendo, pero no quiere decir que si ustedes quieren utilizar algo que se mire en iOS, en Material Design ustedes perfectamente lo pueden hacer y viceversa. Por ejemplo si me voy aquí, en **ion-alert** y tocó la alerta, así se mire una alerta en Material Design (MD).

<img src="/02QueEsIonic/alert_md.png" />

pero si selección iOS y tocó el botón, así se mira la misma alerta pero en un dispositivo corriendo iOS.

<img src="/02QueEsIonic/alert_ios.png" />

Implementarlo y trabajar con esto es sumamente sencillo y muy agradable.

Por ejemplo si ustedes quisieran utilizar **DateTime** tenemos los ejemplos, así se mira un DateTime en iOS.

<img src="/02QueEsIonic/date_time_ios.png" />

Inclusive cuando lo están corriendo ya en el dispositivo físico vibra y cuando estamos en el Material Design, así se míra 

<img src="/02QueEsIonic/date_time_md.png" />

Nosotros en este curso explicaremos el 90 por ciento de cada uno de los elementos que se encuentran acá sino por decir el 99 por ciento ya tendremos una sección donde hablo de cada uno de estos elementos con ejemplos y formas de utilizarlo de manera detallada por los momentos lo que quiero invitarlos a ustedes es que vengan a esta página y se ponga a jugar con todas las opciones que hay.

Hay unos que no tienen un emulador pero nosotros sí haremos el ejercicio y hay otros que como ustedes están viendo si pueden probarlo aquí en el emulador que tienen al lado derecho lleguen a esta página empiecen a jugar con cada uno de los controles y los veo en el siguiente video.

## Nuestra primera aplicación de ionic                                                                           07:55

Es momento de comenzar con nuestra primera aplicación Ionic.

1. Crear una carpeta llamada `Ionic` en el lugar deseado.
2. En la consola cambiarse a la carpeta creada.
3. Escribir el siguiente comando `ionic start myApp tabs` para crear un proyecto Ionic

Esto va a descargarnos todo el temple de taps y dejarlo listo para que nosotros podamos probar nuestra aplicación. Nos pregunta si la app será de Angular o React. Seleccionamos Angular y esperemos que esto termine.

Una vez que finalice tendremos la carpeta `myApp` la cual vamos a renombrar a `01-myApp`. 
Ok entonces de regreso en el terminal nos metemos a esa carpeta con `cd 01-myApp`.
Dentro de la carpeta del proyecto vamos a pulsar el comando:

`ionic serve`

lo que hace ese comando es levantar la aplicación para que yo pueda ver los cambios en tiempo real es decir que cuando yo grabe en el Visual Studio Code automáticamente se refresquen en el navegador web y con eso me va a ayudar a saber cómo se va a ver mi aplicación en ese momento.

Para ver la aplicación en el navegador web escribimos:

`http://localhost:8100/`

Nos carga una aplicación con tres tabs, como se ve en las siguientes imagenes:

<img src="/02QueEsIonic/app1_tab1_web.png" width="250px" /><img src="/02QueEsIonic/app1_tab2_web.png" width="250px"/><img src="/02QueEsIonic/app1_tab3_web.png" width="250px"/>

<img src="/02QueEsIonic/app1_tab1_movil.png" width="250px"/><img src="/02QueEsIonic/app1_tab2_movil.png" width="250px"/><img src="/02QueEsIonic/app1_tab3_movil.png" width="250px"/>


En fin muchas cosas propias para la depuración y probar nuestra aplicación.

Noten que aquí ya lo levanta voy a mostrar las herramientas de desarrollo de la siguiente manera.

Luego lo voy a hacer con el shortcuts pero por momentos voy a tocar aquí los tres puntos muertos developer

Tux está acá por defecto se encuentra así.

Bueno aquí no tenemos el toque.

Yo por lo general estamos aquí en la consola no se preocupen por esos warnings ya los voy a explicar

en breve pero esta es mi aplicación.

Tengo los taps puedo navegar por ellos si quiero simular un dispositivo puedo tocar este botón.

Por defecto voy a hacer un poco más grande por defecto estoy simulando un pixel 2.

Si yo quisiera simular un iPhone puedo seleccionar un iPhone de los que tengo.

Por ejemplo quiero un iPhone 6 y recargo entonces noten que el estilo cambia automáticamente detecta

que es un y2 entonces aplica al estilo de ellos pero si regreso a un pixel por ejemplo un pixel XBL

y recargo aplica al estilo de material design.

Excelente.

Una vez estando en este punto antes de terminar el vídeo vamos a hacer un pequeño cambio para ver qué

fácil es trabajar con Calloni en la carpeta que nosotros acabamos de crear.

0 1 malla la vamos a abrir en el editor de código que ustedes quieran yo en este curso les estoy recomendando

que usen Visual Studio coat pero pueden usar cualquiera.

Entonces yo ya tengo Visual Studio aquí abierto entonces voy a tomar la carpeta y la dejaré caer aquí

perfecto.

Ahora vamos a trabajar en el Tab 2.

Vamos a poner un poco de contenido acá.

Regresemos a nuestro proyecto en la carpeta espérese a Pepe y aquí dice Taub 2 luego Tab 2 Ph.D HTML

que es el código HTML que es el que está renderizado acá.

Aquí hay varios componentes extraños que es la primera vez que ustedes trabajan con ONIC podrían sentirse

un poco intimidados pero mentalizarse que no son más que componentes normales de angular.

Por ejemplo este es un componente que maneja el título un componente que maneja el turbar un componente

que maneja el jede que no necesariamente esto siempre va.

Todo depende de lo que ustedes quieran crear.

En mi caso en el hay un content yo voy a poner un HD2 que diga Hola Mundo y grabo los cambios al grabar

los cambios.

El avión Exide se va a dar cuenta de que hubo cambios y Barré compilar la aplicación y la va a volver

a mostrar en pantalla.

Esto puede ser que cada vez lo haga más rápido conforme vaya actualizándose el framework ONIC pero ahorita

demora un par de segundos porque aquí ya tenemos nuestro Hola mundo en el top 2.

Noten que aquí aparece muy pegado al borde y eso puede ser que es lo que ustedes necesiten para esta

página o puede ser que no nos ofrece un atributo bastante conveniente llamado pan con doble de grave

los cambios.

Más adelante les voy a explicar donde obtengo estos atributos donde están dónde está listado completo

ya lo vamos a ver pero con solo poner Padín ahí y cuando esto recopile aparece una separación aquí en

el lado izquierdo y también en la parte de arriba.

Básicamente eso es todo lo que quería cubrir en este video.

Noten que eso pareciera una aplicación completa y está utilizando lo que es el material design de Android.

Si ustedes quisieran verlo como se trabajarían ellos entonces en esta opción de acá van a seleccionar

cualquier dispositivo iPhone por ejemplo seleccionar un iPhone 6.

Aquí también simular el borde pero puede ser que esto no les aparezca.

Por lo general si esta y una vez hecho esto tienen que recargar la aplicación noten que la aplicación

cambia ya no hace el efecto pero así se ve en ellos ok lo vamos a dejar así.

Por lo general voy a estar trabajando en un pixel XBL.

Una vez hecho ese cambio tienen que recargar el navegador web y estamos listos en el siguiente video.

Yo les voy a explicar cada uno de los directorios y cada uno de los archivos que tiene un proyecto de

Nic actualmente.

## Estructura de un proyecto de ionic - Parte 1                                                                  14:50
## Estructura de un proyecto de ionic - Parte 2                                                                  05:04
## Ionic lab                                                                                                     02:45
## Depurar una aplicación de ionic - debugger                                                                    05:26
## Código fuente de la sección                                                                                   00:18

