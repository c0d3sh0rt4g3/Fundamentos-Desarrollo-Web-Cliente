# Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

#### 1.- Modelos de Programación en Entornos Cliente/Servidor

1. **Aplicaciones de una sola pagina(SPA)**

   Las **SPAs** son ideales por la forma en la que previenen interrupciones en la experiencia del usuario, esto es debido a que las **SPAs** no requieren que se carguen paginas completamente nuevas cada vez que el usuario realiza una nueva accion , en su lugar se actualiza el contenido de la pagina en el que se encuentra el usuario sin necesidad de que se recargue la pagina. Las **SPAs** proporcionan la experiencia de usuario mas interactiva, son posibles gracias a **AJAX**, una forma asincrona de **JavaScript** y **XML**, sin embargo, pueden ser difíciles de optimizar para el **SEO**, un ejemplo de **SPA** seria **Gmail**
2. **Aplicaciones Web Progresivas (PWA)**

   Las **PWAs** son waplicaciones web avanzadas que combinan lo mejor de una pagina web con lo mejor de una app movil. Usan tecnologias web modernas y pueden funcionar **offline**, asegurando que el contenido incluso sin conexion a internet, las **PWAs** proporcionan una experiencia de usuario **rapida y consistente** a traves de diferentes dispositivos, a diferencia de las aplicaciopnes nativas, las **PWAs** no requieren instalacion alguna en una app store y pueden ser encontradas facilmente con **motores de busqueda**. Las **PWAs** han sido un antes y un despues para negocios y desarrolladores ofreciendo mejoras en el rendimiento y la **compatibilidad multiplataforma**, sin embargo, son dificiles de optimizar para el **SEO** un ejemplo de PWA seria **Telegram**.
3. **Renderizado del Lado del Servidor(SSR)**

   El **SSR** es la habilidad de una aplicacion para convertir archivos HTML en una pagina HTML completamente renderizada para el cliente, los motores de busqueda pueden **rastrear e indexar** contenido antes de la busqueda, lo cual es beneficioso para la optimizacion del motor. Las aplicaciones **SSR** son muy populares entre los **blogs y los sitios web de comercio electrónico**.
4. **Aplicaciones Prerenderizadas**

   También se conoce como arquitectura de generación de sitios estáticos. En esta arquitectura, las páginas web del frontend de la aplicación se **generan previamente** y se almacenan como archivos **HTML**, **CSS** y **JS** planos en el servidor. Cuando el usuario solicita una página, ésta se obtiene directamente y se le muestra. Esto hace que la aplicación web sea muy rápida, sin embargo, esta arquitectura aumenta el tiempo de construcción de la aplicación, ya que las páginas web se renderizan durante el proceso de construcción, son estupendas para cuando quieres generar contenido estático, como blogs o detalles de productos que **no cambian a menudo**.
5. **Aplicaciones Isomorficas**

   Son aplicaciones cuyo codigo puede correr tanto en el cliente como en el servidor se podria decir que son una mezcla entre **SSR** y **SPA** ya que se renderizan primero en el servidor y una vez que las recibe el cliente, la app adjunta el **DOM** virtual para un procesamiento **más rapido** por parte del cliente, ademas de su velocidad y eficiencia, son amigables para el **SEO**.
6. **Arquitectura Orientada al Sevicio(SOA)**

   **SOA** es un método de desarrollo de software que utiliza componentes de software llamados servicios para crear **aplicaciones empresariales**, estos servicios brindan una capacidad empresarial y, además, pueden comunicarse también con el resto de servicios mediante diferentes plataformas y lenguajes. Esta arquitectura añade **estabilidad** y **escalabilidad** al stack tecnológico de tu aplicación, sin embargo el mantenimiento de estas aplicaciones puede ser un problema.
7. **Arquitectura de Microservicios**

   La arquitectura de **microservicios** es un estilo de arquitectura para desarrollar aplicaciones, gracias a los microservicios, una aplicación grande puede separarse en **partes independientes** más pequeñas, cada una con su propio **dominio de responsabilidad**. Una aplicación basada en microservicios puede llamar a muchos microservicios internos con los que preparar su respuesta. La arquitectura de **microservicios** es la mejor arquitectura para construir aplicaciones que pretenden escalar algún día a miles y millones de usuarios ya que cada componente es **resistente**, **escalable** y **fácil de mantener**,, un ejemplo de una aplicacion con esta arquitectura seria **Netflix**
8. **Arquitectura Sin Servidor**

   Es una manera de **crear y ejecutar aplicaciones** y servicios sin tener que administrar infraestructura gracias a esto, los desarrolladores se pueden enfocar en el **producto principal** en lugar de preocuparse por la **administración** y el **funcionamiento** de los servidores, o los **tiempos de ejecución**, tanto en la nube como en las instalaciones, sin embargo, es difícil llevar a cabo **tareas de larga duración** utilizando estos componentes.

#### 2.- Mecanismos de Ejecución de Código en un Navegador Web

###### Ejecucion del codigo en JavaScript en navegador:

**JavaScript** no es compilado, en su lugar, un interprete en el navegador lee el codigo en **JavaScript**, interpreta cada linea y lo ejecuta, los navegadores mas modernos usan una tecnologia llamada compilacion **Just-In-Time (JIT)**, que compila **JavaScript** a un ejecutable en bytecode justo cuando esta a punto de ejecutarse.

###### Diferencias de compatibilidad entre navegadores:

Los diferentes navegadores web tienen **implementaciones de JavaScript diferentes** y pueden admitir características **específicas del navegador**, ademas, las versiones antiguas de navegadores pueden no ser compatibles con algunas caracteristicas de **JavaScript** y las **APIs** mas nuevas, ademas lo navegadores moviles suelen tener limitaciones de **rendimiento** y **funcionalidad**.

###### Resolucion de problemas de compatibilidad:

Alguna medida para resolver problemas de compatibilidad serian:

1. Realizar pruebas en distintos navegadores y versiones para **identificar posibles problemas**
2. Mantener actualizado tanto el navegador como las version de **JavaScript**
3. Usar herramientas como **Babel** para convertir nuestro codigo a codigo compatible con versiones mas antiguas de **JavaScript**.

#### 3.- Lenguajes de Programación en Entorno Cliente

###### JavaScript

* Caracteristicas:
  **JavaScript** es un lenguaje interpretado en tiempo de ejecucion en el navegador, ademas es de **tipado dinamico**, es decir, que las variables no tienen un **tipo de dato fijado** durante toda la ejecucion del programa, ademas **JavaScript** pese a ser **multiparadigma** se puede usar para programar **a objetos**.
* Aplicaciones:
  **JavaScript** se utiliza para crear webs interactivas, ademas de para desarrollar aplicaciones moviles hibridas utilizando frameworks como **React Native**, por ultimo, tambien puede ser usado para **desarrollar servidores** usando **Node.js**

###### TypeScript

* Caracteristicas:
  **TypeScript** es una extension de **JavaScript** que añade, entre otras caracteristicas, **tipado estatico opcional**, por tanto los tipos de datos de las variables estaran definidos, esto facilita en muchos casos la deteccion de fallos, **TypeScript** tambien tiene soporte para **programacion orientada a objetos**
* Aplicaciones:
  **TypeScript** se usa para desarrollar aplicaciones web **grandes y complejas**, asi como para desarrollar aplicaciones moviles con frameworks como **NativeScript**, por ultimo, se puede usar para **desarrollar aplicaciones de servidor** a traves de **Node.js**

###### Elm

* Caracteristicas:
  **Elm** es un lenguaje de programacion funcional puro, ademas cuenta con un sistema de tipado **fuerte y estatico** que atrapa muchos **errores durante la compilacion**, **Elm** tiene un patron de diseño propioconocido como **Elm Architecture**, que divide la aplicación en tres partes: el **modelo** (representa el estado de la aplicación), la **vista** (la interfaz de usuario) y la **actualización** (las funciones que cambian el estado), ademas la gestion de errores en **Elm** es amigable puesto que los mensajes de error en **Elm** son bastante claros y descriptivos.
* Aplicaciones:
  **Elm** se utiliza principalmente para crear webs interactivas y de alto rendimiento , asi como **SPAs y aplicaciones criticas** debido a su capacidad para gestionar el estado de la aplicacion de **manera eficiente y minimizando errores**

#### 4.- Caracteristicas de los Lenguajes de Script

###### Ventajas:

* **Facilidad de aprendizaje:**
  Los lenguajes de script suelen tener una **sintaxis mas simple** y legible en comparacion con otros **lenguajes tradicionales** como **Java**, esto los hace mas **accesibles** para gente que esta **empezando a programar**.
* **Desarrollo rapido:**
  Por lo general, los lenguajes de script requieren **menos lineas de codigo para conseguir una funcionalidad**
* **Gran comunidad:**
  Lenguajes con **Python y JavaScript** tienen grandes comunidades activas y por tanto, gran variedad de librerias y **recursos para aprender online**

###### Desventajas:

* **Rendimiento limitado:**
  En general los lenguajes de script tienden a ser **mas lentos** que los **lenguajes de programacion tradicionales** ya que la **interpretacion en tiempo real y la falta de optimizacion de compilacion** pueden llevar a un descenso en el rendimiento.
* **Dependencia de la maquina virtual::**
  Algunoss lenguajes de script como **Pyhton o JavaScript** en el navegador dependen de **maquinas virtuales o interpretes especificos**, esto puede llevar a **problemas de compatibilidad.**
* **Limitaciones en Aplicaciones de Alto Rendimiento:**
  Para aplicaciones que requieren un mantenimietno **exahustivo o un control preciso del hardware**,, los lenguajes de **script** pueden no ser la mejor opcion en **temas de optimizacion**.
* **Seguridad:**
  Los lenguajes de script suelen ser **mas vulnerables** por lo general a ciertos ataques como la **inyeccion de codigo** si no se toman las **suficientes precauciones**.

#### 5.- Integracion de Codigo con las Etiquetas HTML

###### Exploracion de tecnologias como CSS y HTML5

* **HTML:**
  Es el **lenguaje de marcado estandar** utilizado para crear la estructura y el contenido de una pagina web. **HTML** utiliza etiquetas para definir elementos como encabezados, parrafos, imagenes y enlaces
* **CSS:**
  Se utiliza para dar **estilo y diseño** a las paginas web, permite **controlar la apariencia** de los elementos **HTML** como el tamaño, los colores, las fuentes y los margenes.

###### Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras.

* **Ejemplo de JavaScript dentro del HTML:**

  ~~~~
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <title>Ejemplo js en el archivo</title>
  </head>
  <body>
    <script>
        alert("Hello world from inside a HTML")
    </script>
  </body>
  </html>
  ~~~~
* **Ejemplo de JavaScript en un archivo separado:**

  **Archivo de JavaScript:**

  ````
  alert("Hello world from outside a HTML")
  ````

  **Archivo HTML:**

  ````
  <!DOCTYPE html>
  <html lang="en">
  <head>
      <meta charset="UTF-8">
      <title>Ejemplo js en el archivo</title>
      <script src="./js/ejemplo.js"></script>
  </head>
  <body>
  </body>
  </html>
  ````

#### 6.- Herramientas de programación

###### Algunas de las herramientas de programacion mas populares son:

* **Visual Studio Code:**
  **VS Code** es un **IDE** desarrollado por microsoft, tiene una gran personalizacion y es de código abierto, además, ofrece soporte para gran variedad de lenguajes y tiene gran cantidad de extensiones, por último, ofrece **resaltado de sintaxis, autocompletado, depuración integrada y control de versiones**
* **Chrome Devtools:**
  **Chrome DeveTools** te permite hacer lo que su nombre indica, permite a los desarrolladores acceder al interior de sus aplicaciones web, ofreciendo variedad de herramientas para optimizar su código, mientras una **línea de tiempo** va mostrando los cambios que se realizan en cada momento.
* **GitHub:**
  Es una plataforma de **alojamiento de código** basada en **Git** que facilita el seguimiento de los proyectos y la colaboracion entre programadores.
* **IntelliJ IDEA:**
  Es un **IDE** bastante popular para programar en **Java** y **Kotlin** entre otros, ofrece características avanzadas para **refactorizar, analizar y depurar** el código, además también tiene **control de versiones** es compatible con plugins.
* **CodePen:**

  **CodePen** es una herramienta utilizada para mostrar fragmentos de código en HTML, CSS o JavaScript en una página web, debido a que el número de gente que aprende a programar no hace más que crecer,**CodePen** no hace más que ganar popularidad.

#### Bibliografia

* [Kinsta](https://kinsta.com/es/blog/arquitectura-aplicaciones-web/)
* [HubSpot](https://blog.hubspot.es/website/tipos-aplicaciones-web)
* [HeavyAI](https://www.heavy.ai/technical-glossary/server-side-rendering)
* [SolutionsHub](https://solutionshub.epam.com/blog/post/what-is-server-side-rendering)
* [Jullabot](https://www.lullabot.com/articles/what-is-an-isomorphic-application)
* [AWS](https://aws.amazon.com/es/what-is/service-oriented-architecture/#:~:text=you%20implement%20microservices%3F-,What%20is%20service-oriented%20architecture%3F,other%20across%20platforms%20and%20languages.)
* [GoogleCloud](https://cloud.google.com/learn/what-is-microservices-architecture?hl=es#:~:text=on%20Google%20Cloud.-,Microservices%20architecture%20defined,architecture%20diagrams%20and%20services%20independently.)
* [OpenWebinar](https://openwebinars.net/blog/microservicios-que-son/)
* [Lawebera](https://www.lawebera.es/xhtml-css/compatibilidad-web-navegadores.php)
* [Babel](https://ingenieriadesoftware.es/babel-transpilador-compatibilidad-javascript/)
* [Back4app](https://blog.back4app.com/client-side-development-languages/)
* [Aulab](https://aulab.es/noticia/202/que-es-un-lenguaje-de-scripting#:~:text=Ventajas%20y%20desventajas%20de%20los%20lenguajes%20de%20scripting&text=Generalmente%20tienen%20una%20sintaxis%20más,te%20permiten%20crear%20páginas%20atractivas.)
* [5 herramientas de desarrollo web que debes usar](https://www.linkedin.com/pulse/5-herramientas-de-desarrollo-web-que-debes-usar-mohamed-rifi/?originalSubdomain=es)
* [CfBlog](https://careerfoundry.com/en/blog/web-development/7-essential-tools-for-front-end-development/)
