---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
---
<style>
h1{
    text-align:center;
    color: red
}
h4{
    color:red
}
{
    font-size: 25px
}
.image-centered{
    text-align: center;
}
</style>

# Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

![imagen_portada](./img/portada.jpg)

---

<h1>Índice</h1>

![bg right height:300px](./img/imagen_indice.jpg)
**1. Modelos de Programación en Entornos Cliente/Servidor**

**2. Mecanismos de Ejecución de Código en un Navegador Web**

**3. Lenguajes de Programación en Entorno Cliente**

**4. Caracteristicas de los Lenguajes de Script**

**5. Integracion de Codigo con las Etiquetas HTML**

**6. Herramientas de programación**

---
#### 1.- Modelos de Programación en Entornos Cliente/Servidor

* **SPA (Aplicaciones de una sola página)**
    * Actualizan el contenido **sin recargar la página**.
* **PWA (Aplicaciones Web Progresivas)**
    * Combinan lo mejor de una **página web y una app móvil**.
* **SSR (Renderizado del Lado del Servidor)**
    * Convierten archivos HTML en páginas **renderizadas**.
* **Aplicaciones Prerrenderizadas**
    * Generación de **sitios estáticos** con páginas HTML, CSS y JS planos.
---

#### 1.- Modelos de Programación en Entornos Cliente/Servidor

* **Aplicaciones Isomórficas**
    * Combina SSR y SPA.
* **Arquitectura SOA (Arquitectura Orientada al Servicio)**
    * Utiliza servicios para **crear aplicaciones empresariales**.
* **Arquitectura de Microservicios**
    * Divide aplicaciones **grandes** en partes **independientes**.
* **Arquitectura Sin Servidor**
    * Permite crear aplicaciones **sin administrar infraestructura**.

---

#### 2.- Mecanismos de Ejecución de Código en un Navegador Web

##### Ejecucion del codigo en JavaScript en navegador:

**JavaScript** es interpretado en el navegador, los navegadores más modernos usan una tecnología llamada compilación **Just-In-Time (JIT)**.

##### Diferencias de compatibilidad entre navegadores:

Los diferentes navegadores web tienen **implementaciones de JavaScript diferentes** y pueden admitir características **específicas del navegador**.

##### Resolucion de problemas de compatibilidad:

Algunas medidas para resolver problemas de compatibilidad serían:

* Realizar pruebas en distintos navegadores y versiones
* Mantener actualizado tanto el navegador como las version de **JavaScript**
* Usar herramientas como **Babel**

---

#### 3.- Lenguajes de Programación en Entorno Cliente

##### JavaScript

![bg right height:300px](./img/logo_js.png)

* **Características:**
    * Lenguaje interpretado
    * Tipado dinámico
    * Multiparadigma

* **Aplicaciones:**
    * Webs **interactivas**
    * Desarrollo de servidores

---

##### TypeScript

* **Características:**
    * Tipado estático opcional
    * Soporte para programación **orientada a objetos**.

* **Aplicaciones:**
    * Desarrollo de aplicaciones web **grandes y complejas**
    * Desarrollo de aplicaciones de servidor

##### Elm

* **Características:**
    * Funcional puro
    * Tipado fuerte y estático

* **Aplicaciones:**
    * Desarrollo de SPAs y aplicaciones críticas.

---

#### 4.- Caracteristicas de los Lenguajes de Script

##### Ventajas

* Facilidad de aprendizaje
* Desarrollo rapido
* Gran comunidad

##### Desventajas

* Rendimiento Limitado

* Dependencia de la Máquina Virtual

* Limitaciones en Aplicaciones de Alto Rendimiento

* Seguridad

---

#### 5.- Integracion de Codigo con las Etiquetas HTML
##### Exploracion de tecnologias como CSS y HTML5

* **HTML:**
  Es el **lenguaje de marcado estandar** utilizado para crear la estructura y el contenido de una pagina web. 
* **CSS:**
  Se utiliza para dar **estilo y diseño** a las paginas web.

![bg right height:300px](./img/html_y_css.jpg)

---

##### Creación de una pequeña aplicación web integrando código JavaScript de diferentes maneras

* **Ejemplo de JavaScript dentro del HTML:**

  ~~~~html
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

---

#### 6.- Herramientas de programación



* **Visual Studio Code (VS Code):**
    * IDE de **código abierto**

* **Chrome Devtools:**
    * Acceso al interior de aplicaciones web.

* **GitHub:**
    * Plataforma de alojamiento de código **basada en Git**

* **IntelliJ IDEA:**
    * IDE popular para **Java** y **Kotlin**.
    * Refactorización, **análisis y depuración avanzados**

* **CodePen:**
    * Muestra fragmentos de código **HTML, CSS y JavaScript** en una página web

---

<h1 >Bibliografia</h1>

* [Kinsta](https://kinsta.com/es/blog/arquitectura-aplicaciones-web/)
* [HubSpot](https://blog.hubspot.es/website/tipos-aplicaciones-web)
* [HeavyAI](https://www.heavy.ai/technical-glossary/server-side-rendering)
* [SolutionsHub](https://solutionshub.epam.com/blog/post/what-is-server-side-rendering)
* [Jullabot](https://www.lullabot.com/articles/what-is-an-isomorphic-application)
* [AWS](https://aws.amazon.com/es/what-is/service-oriented-architecture/#:~:text=you%20implement%20microservices%3F-,What%20is%20service-oriented%20architecture%3F,other%20across%20platforms%20and%20languages.)
* [GoogleCloud](https://cloud.google.com/learn/what-is-microservices-architecture?hl=es#:~:text=on%20Google%20Cloud.-,Microservices%20architecture%20defined,architecture%20diagrams%20and%20services%20independently.)
* [OpenWebinars](https://openwebinars.net/blog/microservicios-que-son/)
* [Lawebera](https://www.lawebera.es/xhtml-css/compatibilidad-web-navegadores.php)
* [Babel](https://ingenieriadesoftware.es/babel-transpilador-compatibilidad-javascript/)
* [Back4app](https://blog.back4app.com/client-side-development-languages/)
* [Aulab](https://aulab.es/noticia/202/que-es-un-lenguaje-de-scripting#:~:text=Ventajas%20y%20desventajas%20de%20los%20lenguajes%20de%20scripting&text=Generalmente%20tienen%20una%20sintaxis%20más,te%20permiten%20crear%20páginas%20atractivas.)
* [5 herramientas de desarrollo web que debes usar](https://www.linkedin.com/pulse/5-herramientas-de-desarrollo-web-que-debes-usar-mohamed-rifi/?originalSubdomain=es)