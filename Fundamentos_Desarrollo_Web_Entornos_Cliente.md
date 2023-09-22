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

   La arquitectura de **microservicios** es un estilo de arquitectura para desarrollar aplicaciones, gracias a los microservicios, una aplicación grande puede separarse en **partes independientes** más pequeñas, cada una con su propio **dominio de responsabilidad**. Una aplicación basada en microservicios puede llamar a muchos microservicios internos con los que preparar su respuesta. La arquitectura de **microservicios** es la mejor arquitectura para construir aplicaciones que pretenden escalar algún día a miles y millones de usuarios ya que cada componente es **resistente**, **escalable** y **fácil de mantener**,, un ejemplo de una aplicacion con esta arquitectura seria **Netflix**.
8. **Arquitectura Sin Servidor**

   Es una manera de **crear y ejecutar aplicaciones** y servicios sin tener que administrar infraestructura gracias a esto, los desarrolladores se pueden enfocar en el **producto principal** en lugar de preocuparse por la **administración** y el **funcionamiento** de los servidores, o los **tiempos de ejecución**, tanto en la nube como en las instalaciones, sin embargo, es difícil llevar a cabo **tareas de larga duración** utilizando estos componentes.

#### 2.- Mecanismos de Ejecución de Código en un Navegador Web

##### Ejecucion del codigo en JavaScript en navegador:

**JavaScript** no es compilado, en su lugar, un interprete en el navegador lee el codigo en **JavaScript**, interpreta cada linea y lo ejecuta, los navegadores mas modernos usan una tecnologia llamada compilacion **Just-In-Time (JIT)**, que compila **JavaScript** a un ejecutable en bytecode justo cuando esta a punto de ejecutarse.

##### Diferencias de compatibilidad entre navegadores

#### Bibliografia

* [Kinsta](https://kinsta.com/es/blog/arquitectura-aplicaciones-web/)
* [HubSpot](https://blog.hubspot.es/website/tipos-aplicaciones-web)
* [HeavyAI](https://www.heavy.ai/technical-glossary/server-side-rendering)
* [SolutionsHub](https://solutionshub.epam.com/blog/post/what-is-server-side-rendering)
* [Jullabot](https://www.lullabot.com/articles/what-is-an-isomorphic-application)
* [AWS](https://aws.amazon.com/es/what-is/service-oriented-architecture/#:~:text=you%20implement%20microservices%3F-,What%20is%20service-oriented%20architecture%3F,other%20across%20platforms%20and%20languages.)
* [GoogleCloud](https://cloud.google.com/learn/what-is-microservices-architecture?hl=es#:~:text=on%20Google%20Cloud.-,Microservices%20architecture%20defined,architecture%20diagrams%20and%20services%20independently.)
* [OpenWebinar](https://openwebinars.net/blog/microservicios-que-son/)
