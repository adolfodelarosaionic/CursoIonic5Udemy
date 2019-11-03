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

<img src="/02QueEsIonic/app1_tab1_web.png" width="300px" /> <img src="/02QueEsIonic/app1_tab2_web.png" width="300px"/> <img src="/02QueEsIonic/app1_tab3_web.png" width="300px"/>

<img src="/02QueEsIonic/app1_tab1_movil.png" width="250px"/> <img src="/02QueEsIonic/app1_tab2_movil.png" width="250px"/> <img src="/02QueEsIonic/app1_tab3_movil.png" width="250px"/>

Podemos mostrar las herramientas de desarrollo.

Tenemos los tres tabs, puedo navegar por ellos si quiero simular un dispositivo puedo tocar este botón.

<img src="/02QueEsIonic/boton_dispositivos.png" />

Por defecto estoy simulando un iPhoneX. Si yo quisiera simular un Pixel puedo seleccionar un Pixel 2 de los que tengo y recargo entonces noten que el estilo cambia automáticamente detecta que es un Pixel 2 entonces aplica el estilo aplicando el estilo de Material Design.

<img src="/02QueEsIonic/pixel2.png" />

## Estructura de un proyecto de ionic - Parte 1                                                                  14:50

Para ver la estructura de el proyecto creado abrimos el Visual Studio Code y cargamos el proyecto `01-myApp`.

<img src="/02QueEsIonic/vsc-01-myApp.png" />


En esta clase vamos a hablar sobre cada uno de los archivos y directorios que se encuentran en un proyecto de Ionic.
Empecemos con el de Iturbi o en en una carpeta destinada a realizar pruebas de extremo a extremo para crear una aplicación en allowing ya sea para Android o iOS o bien obligó a una aplicación web esta carpeta realmente no es necesaria para crear un proyecto de Yony que es más que todo cuando nosotros queremos realizar pruebas.

Pero esta carpeta no lo vamos a utilizar en el curso así que no se preocupen por esto.

Luego tenemos los módulos de Nott en el cual se encuentran todas las dependencias de nuestro proyecto tanto las de angular como honek y todo lo que ellos necesitan para que nosotros podamos tener en nuestra aplicación lo que es el reloj que cuando yo grabo se actualicen los cambios.

En fin que todo funcione acá que cuando yo tengo un error acá me digan qué archivo es o cuál es la ayuda necesaria para que yo pueda saber en dónde está el error.

Básicamente estos módulos nosotros no los vamos a tocar manualmente todos lo hacemos mediante comandos de enemistó o RPM honesto.

Si queremos borrar algo de acá pero esto no lo tocamos manualmente la carpeta s R.-Se o sours conocida también con ese nombre la voy a dejar para el final porque esto ya es la aplicación de Angola.

Eso lo voy a dejar al final.

Luego tenemos lo que es el archivo punto ignoré para las personas que ya han trabajado con GIT o saben un poco y saben que este archivo pero para los que no. Básicamente es un archivo que me dice A mí cuáles son los directorios o archivos que yo necesito ignorar que no van a ser parte de mi repositorio entiéndase un repositorio como un proyecto que yo voy a respaldar en algún lugar como por ejemplo Kidjo o GIT Bosquet o cualquier otro lugar.

Todos estos archivos por ejemplo yo no quiero tener un respaldo de los archivos log o los archivos temporales o cualquier archivo que se llame lospuntos txt o los proyectos de su text.

Cualquiera de estas cosas inclusive los módulos no sonara como extraño que los módulos no son necesarios y están siendo ignorados.

Pero es que los módulos de Nott se puede reconstruir con un comando que está en el paquete junto Jayson eso ya lo vamos a ver en breve pero básicamente esto es lo que hace el archivo Ghitis.

Nosotros no creemos que un archivo o carpeta sea parte de nuestro proyecto a la hora de hacer un respaldo en la nube o en algún lugar.

Entonces lo podemos agregar Acá a cerrarlo.

Luego tenemos el angular puntu Jayson ese es el mismo punto Jayson de un proyecto de angular común y corriente.

Aquí ustedes van a poder observar que tenemos la definición de mis archivos de estilos.

Por ejemplo este es el archivo de estilos que a usar acá.

Luego tenemos el archivo de estilos globales otras dependencias de scripts.

En fin es lo mismo y nosotros no vamos a tocar esto.

Normalmente no se toca este archivo a menos de que nosotros queramos hacer alguna instalación en específico pero realmente es muy raro que se utilice esto.

Luego tenemos el Ionic confit punto Jayson el archivo Jayson en el cual dice cuál es el nombre de la aplicación.

Qué tipo de aplicación es.

Por ejemplo aquí me dice que es una aplicación de Angola y dice Angola porque también puede ser hecha en React utilizando ONIC.

También puede ser Yamasaki plano entre otras cosas y si tiene algún tipo de integración aquí también se especifica.

Cuando nosotros hacemos la conexión con Calloni que son un par de herramientas adicionales que nos ofrece que es un par de herramientas adicionales que nos puede ofrecer algún tipo de costo aquí podríamos tener ese tipo de integraciones y también nos a decir cuál es el Heydi de la aplicación.

Entre otras cosas realmente esto tampoco se toca mucho.

Luego tenemos el paquete punto lospuntos Jayson que es un archivo que nosotros no manipulamos en pocas palabras.

El log Jayson nos dice cómo fue construido el paquete apuntó Jayson.

Y en qué orden fue el archivo pakete apuntó Jayson me dice a mí cuál es el nombre de mi aplicación cuál es la versión.

Todo esto se puede cambiar.

Estos podían poner su nombre que no hizo el homepage comandos que nos van a ayudar a nosotros a que cuando nosotros creamos alguna terminal ejecutar esos comandos rápidamente.

Luego tenemos cuáles son las dependencias de nuestro proyecto y también tenemos las dependencias de desarrollo.

La diferencia entre las dependencias normales y la de desarrollo es que las de desarrollo no forman parte del producto final de mi aplicación.

Es decir esto sí va a formar parte del Bondone que va a ser subido en el dispositivo móvil o en la aplicación web.

Las dependencias de desarrollo sólo son usadas cuando yo quiero hacer pruebas o quiero probarlo localmente en mi equipo.

Básicamente eso es todo por hoy.

El test cómo fue punto Jayson es el archivo de configuración de Tawfiq.

Tampoco lo vamos a manipular mucho pero aquí básicamente le dice a Taipe cómo quieren que sea convertido el código JavaScript como por ejemplo que el estándar sea JavaScript del 2015 pero también podríamos poner otro estándar pero realmente esto es lo que nos ayuda a nosotros es aumentar la compatibilidad el achiote ese confit como les dije son las reglas detalló.

El té es el punto Jayson.

Es un archivo bien interesante que básicamente es una gran colección de reglas.

Estas reglas nos ayudan a que escribamos un código más limpio detalló scrip y que otros usuarios también programen de la misma manera.

Realmente no he recomendado que nosotros activemos estas cosas porque esto es como un estándar es decir te va a decir que todas las funciones se tienen que definir de esta manera que tienen que tener un espacio antes de los paréntesis de las llaves.

En fin esto ustedes ya lo van a ver cuando nos empiecen a tirar errores de ese lint que realmente no son errores son sugerencias se pueden desactivar pero como les dije es importante dejarlas porque nos van a ayudar a escribir un mejor código.

Ahora si vamos con la carpeta merece esta carpeta no es diferente a un proyecto de anulares casi la misma con un par de pequeñitas cosas diferentes.

Empezamos con una carpeta app que normalmente aquí es donde vamos a pasar la mayor parte del tiempo que es donde nosotros vamos a crear las páginas los servicios directivas todo lo que queramos de nuestra aplicación va a estar acá por ejemplo aquí tenemos uno dos tres que ya sabemos que hace referencia a uno dos tres.

Sigamos el tab 2 voy a abrir el tab 2 que eso ya lo habíamos modificado rápidamente el HTML que habíamos puesto el Hola Mundo solo que yo lo RE7 pero aquí tendríamos nosotros un H2 con el Hola Mundo.

Si yo grabo los cambios aquí se va a refrescar pero lo que se encuentra en el HTML es la página básicamente que tenemos acá.

Luego obviamente vamos a crear nuestras propias páginas.

Vamos a crear moda vamos a crear de todo en este curso pero hay una pequeña diferencia que yo quiero explicarles acá.

Este HTML algunas veces donde no va a tener un contenido o hay otras veces donde no hay un Gelber o también va a haber ocasiones donde no tiene ni contenido ni Jaider pero eso ya lo van a ver y les voy a explicar cuando si se ocupa cuando nos ocupa y ustedes mismos van a poder decidir cómo quieren que se miren sus páginas ahora cada una de las páginas tiene una estructura parecida a ésta por ejemplo tiene un módulo tiene un código HTML tiene un código de.

No se preocupen si ustedes no conocen básicamente pueden escribir código de CSS normal y todo ese código es válido en ese seises no se preocupen por eso el archivo de pruebas es opcional que es utilizado cuando ustedes quieren correr o ejecutar pruebas y también tenemos el componente que nos ayuda a nosotros a poner nuestra lógica de cada pantalla.

Cuál es la idea de que cada una de las páginas tenga un módulo y también si se fijan aquí tiene un router Mogul apuntó.

Es tan raro y también observar que algunas páginas tienen como un módulo un router por ejemplo este de acá ya vamos a llegar a eso pero ustedes van a observar que tiene paz de esto como este código como extraño si es la primera vez que ustedes trabajan con rutas guiadas en angular.

Puede ser que ustedes sientan esto un poco extraño pero la idea de una aplicación de Yony así como se encuentra en estos momentos es que todo lo haga mediante carga perezosa o lasitud.

Esto ayuda a que la aplicación de ONIC cargue sumamente rápido cuando es lanzada en un dispositivo.

Vamos a ver esto en detalle un poco más adelante.

También les voy a dar un reforzamiento de angular para que ustedes sepan cómo crear y de dónde viene todo esto qué vamos a ver del tabs que tal vez es un poquito diferente.

La pantalla del taps prácticamente es esto que tenemos aquí abajo y luego tiene una pantalla o un contenedor que nos permite mostrar las páginas.

Si nosotros vemos lo que es el taps punto HTML este código tal vez es raro la primera vez pero entiendan que cada uno de estos es una opción del menú.

Si ustedes crearan otro por ejemplo copian todo este tapón lo copian y lo volví a pegar acá grabo los cambios aunque diga top3 y tengo un clon.

Van a ver que aquí ahora va a aparecer otra opción.

Esperemos que esto recopile y ahí tenemos la cuarta opción que también hace lo mismo.

Más adelante ustedes van a ver cómo funciona esto.

No se preocupen que queden Haswell.

Pero es que en teoría ese mismo Tapp eso ya lo vamos a ver más adelante también.

Ok voy a cerrarlo.

Aquí tenemos un Tappsi router y este archivo el router es intimidante la primera vez que se ve uno dice pero qué es este montón de código.

Yo nunca lo voy a prender realmente.

Cuando ustedes ya conocen la teoría y ya lo han hecho manualmente es más fácil dominar eso.

Posteriormente nosotros vamos a crear nuestros propios taps de forma manual que nos va ayudar a comprenderlo mucho mejor.

Luego tenemos lo que es el rating punto módulo punto 13.

Básicamente ese es el archivo que le dice angular cómo va a manejar las rutas es decir cuál es la página principal cuál es la segunda página cuál es la tercera página y en fin cómo navegar entre pantallas.

Ya vamos a utilizar esto cierro pero tenemos el componente que es lo mismo.

Aquí teníamos un router outlet que es muy parecido al router outlet de Angola pero este es el de aviones que nos ayuda a que la aplicación se mire así.

Luego tenemos otro chip de pruebas todos los que sean puntos Speck su archivo de pruebas no lo vamos a usar en este curso.

Luego tenemos la component que esto es importante más adelante.

Aquí nosotros podemos ejecutar código cuando la aplicación ya está lista.

En este caso Platform Bravi quiere decir que la aplicación ya cargó le aplicamos un color a la barra de estado y quitamos el explayo screen.

Más adelante vamos a utilizar esto para saber cuándo la aplicación entra en suspensión cuándo se reactiva entre otras cosas.

Luego tenemos el PP punto módulo punto TC que si ustedes ya conocen un poco de angular ese mismo archivo en el cual tienen cuáles son los importes cuáles son los providers los módulos que se especifican los componentes entre componentes que ya casi no se usa.

Pero a menos de que ustedes necesiten crear algo en tiempo real o renderizar algo en tiempo real aquí sería la misma lógica angular de los componentes.

Pero antes se usaba mucho en otras versiones de Yony que era bastante común que tuviéramos todo entre componentes ahora no hace falta.

De hecho casi ni sus cierro.

Luego tenemos los assets que aquí es donde vienen recursos estáticos como por ejemplo imágenes que tenemos un Aiken y tenemos un archivo ese BG o s VG como ustedes digan EEBI que básicamente es esta imagen que ustedes tienen acá.

Cuál es la gracia de que un SVG.

Pues es es simplemente no se píxels que ustedes hagan Aganzo siempre se mantiene de la manera correcta porque son vectores y no píxeles.

Básicamente eso es lo mismo pero nada del otro mundo.

Cierro la parte de los environments es utilizada para declarar variables de entorno globales por decir algo.

Vamos a ver en más adelante nosotros vamos a utilizar este archivo cuando definamos cuál es el VfL de mis servicios es decir aquí tendremos unos environments de desarrollo el que no tiene ese desarrollo y el de Propp.

El punto es el de producción.

Cuál es la diferencia de ambos.

Pues cuando nosotros hagamos un ONIC o ya lo generemos para producción va a utilizar estos archivos de configuración y cuando estamos en desarrollo va a utilizar eso de acá no se preocupen si todavía no comprenden mucho la idea de estos dos archivos vamos a usar más adelante.

Luego tenemos el Zim aquí adentro del cine tenemos un archivo de zás llamado variables punto CSS.

Aquí hay una configuración de los colores primarios o los colores básicos de mi aplicación de ONIC o el tema que ustedes están viendo acá como por ejemplo por qué eso sale azul porque aquí está el azul.

Si ustedes le pusieran otro color como por ejemplo rojo esto si quieren no lo harán.

Pero ustedes pusieron aquí un rojo y graban los cambios.

Esto va a recargar y ahora todo lo que tuviera este problema ahí va a pasar a ser rojo.

Hay una que ofrece en su página también un generador de estilos que vamos a utilizar después.

Este cambio no lo hagan voy a dejarlo como estaba originalmente.

Básicamente aquí nosotros podemos definir variables y hacer cambios para los colores y otras formas como se quieren que se presente la aplicación en el dispositivo móvil o ya cuando esté corriendo en la aplicación.

Luego tenemos el Global punto ese CSS que es otro chivó parecido al CIM pero a quién le va su configuración de clases o estilos personalizados.

El CIM sólo va para usar cambios o para aplicar cambios de la aplicación de ONIC.

Este global es el CS6 para definir sus estilos personalizados el índex junto a HTML es el lugar donde está lanzándose mi aplicación por primera vez.

Aquí tenemos nuestro robot.

Aquí es donde se renderiza mi aplicación completa.

Aquí tenemos ya lo que es una página común corriente HTML y si ustedes ya conocen angular pues es el mismo archivo tengo luego el Karama puntocom apuntó JS Que es el archivo de configuración de karma que son también pruebas.

El mail que le dice cuál es el modulo principal en este caso LPP punto módulo y también me verifica o bien producción o no.

El archivo polifenol es un archivo que se utiliza cuando ustedes necesitan incrementar la compatibilidad con otros navegadores web por ejemplo pudiera ser que tienen la aplicación esté corriendo en Internet Explorer 9 y necesitan usar promesas pues las promesas no existían ahí entonces ustedes pueden colocar acá ya sea un scrip o lo que quieren que haga.

Cuando se detecta que es una promesa en fin los polifilético son utilizados para incrementar la compatibilidad de su aplicación.

El test es otro archivo de pruebas no lo vamos a utilizar.

Luego tenemos el PP punto Jayson.

Este ya es una configuración de tipo propia para la aplicación como por ejemplo los tips en caso de que importábamos en nuestro proyecto Llewelyn podríamos importar aquí el tipado de Hitachi ya nos daría las ayudas de todo el código QR tres puntos Peixoto Jayson sería el archivo de configuración de Tawfiq.

Si ustedes están trabajando sus pruebas contactes ok.

Básicamente eso es todo.

Con esta estructura pero todavía hay otros directorios adicionales pero eso se los mostraré en el siguiente video.

## Estructura de un proyecto de ionic - Parte 2                                                                  05:04
## Ionic lab                                                                                                     02:45
## Depurar una aplicación de ionic - debugger                                                                    05:26
## Código fuente de la sección                                                                                   00:18

