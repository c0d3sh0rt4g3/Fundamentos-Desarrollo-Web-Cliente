---
marp: true
theme: gaia
_class: lead
paginate: true
backgroundColor: #fff
---
<style>
h1{
    font-size: 60px;
}
h4{
    font-size: 35px
}
h5{
    font-size: 28px
}
{
    font-size: 19px
}
p{
    font-size: 18px
}

</style>

# Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

![imagen_portada](https://us.123rf.com/450wm/andreysuslov/andreysuslov2203/andreysuslov220300005/183781378-concepto-isométrico-de-diseño-web-desarrollo-de-sitios-web-de-todas-las-plataformas-sitio-web-de.jpg?ver=6)

---

#### 1.- Modelos de Programación en Entornos Cliente/Servidor

* **SPA (Aplicaciones de una sola página)**
    * Actualizan el contenido sin recargar la página.
    * Interactividad gracias a AJAX (JavaScript y XML asincrónicos).
    * Ejemplo: Gmail.
    <br>
* **PWA (Aplicaciones Web Progresivas)**
    * Combinan lo mejor de una página web y una app móvil.
    * Funcionan offline y ofrecen rapidez y consistencia.
    * Ejemplo: Telegram.
    <br>
* **SSR (Renderizado del Lado del Servidor)**
    * Convierten archivos HTML en páginas renderizadas.
    * Beneficios para la optimización del motor de búsqueda.
    * Populares en blogs y sitios de comercio electrónico.
    <br>
* **Aplicaciones Prerrenderizadas**
    * Generación de sitios estáticos con páginas HTML, CSS y JS planos.
    * Rápidas, pero aumentan el tiempo de construcción.
    * Ideal para contenido estático como blogs o detalles de productos.

---

* **Aplicaciones Isomórficas**
    * Combina SSR y SPA.
    * Renderizadas primero en el servidor y luego en el cliente.
    * Rápidas, eficientes y amigables para SEO.
    <br>
* **Arquitectura SOA (Arquitectura Orientada al Servicio)**
    * Utiliza servicios para crear aplicaciones empresariales.
    * Añade estabilidad y escalabilidad.
    * Requiere mantenimiento.
    <br>
* **Arquitectura de Microservicios**
    * Divide aplicaciones grandes en partes independientes.
    * Resistente, escalable y fácil de mantener.
    * Ejemplo: Netflix.
    <br>
* **Arquitectura Sin Servidor**
    * Permite crear aplicaciones sin administrar infraestructura.
    * Enfocado en el producto principal.
    * Limitaciones en tareas de larga duración

---

#### 2.- Mecanismos de Ejecución de Código en un Navegador Web

##### Ejecucion del codigo en JavaScript en navegador:

**JavaScript** no es compilado, en su lugar, un interprete en el navegador lee el codigo en **JavaScript**, interpreta cada linea y lo ejecuta, los navegadores mas modernos usan una tecnologia llamada compilacion **Just-In-Time (JIT)**, que compila **JavaScript** a un ejecutable en bytecode justo cuando esta a punto de ejecutarse.

##### Diferencias de compatibilidad entre navegadores:

Los diferentes navegadores web tienen **implementaciones de JavaScript diferentes** y pueden admitir características **específicas del navegador**, ademas, las versiones antiguas de navegadores pueden no ser compatibles con algunas caracteristicas de **JavaScript** y las **APIs** mas nuevas, ademas lo navegadores moviles suelen tener limitaciones de **rendimiento** y **funcionalidad**.

##### Resolucion de problemas de compatibilidad:

Algunas medidas para resolver problemas de compatibilidad serian:

* Realizar pruebas en distintos navegadores y versiones para **identificar posibles problemas**
* Mantener actualizado tanto el navegador como las version de **JavaScript**
* Usar herramientas como **Babel** para convertir nuestro codigo a codigo compatible con versiones mas antiguas de **JavaScript**

---

#### 3.- Lenguajes de Programación en Entorno Cliente

##### JavaScript

![bg right height:160px](https://upload.wikimedia.org/wikipedia/commons/thumb/9/99/Unofficial_JavaScript_logo_2.svg/800px-Unofficial_JavaScript_logo_2.svg.png)

* **Caracteristicas:**
    * **Lenguaje interpretado** en tiempo de ejecución en el navegador.
    * **Tipado dinámico**, sin **tipos de dato fijados**.
    * **Multiparadigma**, se puede usar para programar **orientado a objetos**.

* **Aplicaciones:**
    * Creación de webs **interactivas**.
    * Desarrollo de aplicaciones móviles híbridas con **React Native**.
    * Desarrollo de servidores usando **Node.js**

---

##### TypeScript

<!-- ![height:60px](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4c/Typescript_logo_2020.svg/2048px-Typescript_logo_2020.svg.png) -->

* **Caracteristicas:**
    * Extensión de JavaScript con **tipado estático opcional**.
    * Soporte para programación **orientada a objetos**.

* **Aplicaciones:**
    * Desarrollo de aplicaciones web **grandes y complejas**.
    * Desarrollo de aplicaciones móviles con frameworks como **NativeScript**.
    * Desarrollo de aplicaciones de servidor a través de **Node.js**.

##### Elm

<!-- ![height:60px](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Elm_logo.svg/1024px-Elm_logo.svg.png) -->

* **Caracteristicas:**
    * Lenguaje de programación **funcional puro**.
    * Sistema de **tipado fuerte y estático** que atrapa errores en compilación.
    * Patrón de diseño conocido como "Elm Architecture."
    * Mensajes de error claros y descriptivos.

* **Aplicaciones:**
    * Creación de webs interactivas de alto rendimiento.
    * Desarrollo de SPAs y aplicaciones críticas.
    * Eficiente gestión del estado de la aplicación y minimización de errores.


---

#### 4.- Caracteristicas de los Lenguajes de Script

##### Ventajas

* **Facilidad de aprendizaje:**
    * Tienen una **sintaxis mas simple** y legible en comparacion con otros **lenguajes tradicionales**.
    * Más **accesibles** para gente que está **empezando a programar**.

* **Desarrollo rapido:**
    * Se requieren **menos lineas de codigo** para conseguir una funcionalidad
* **Gran comunidad:**
    * Lenguajes con **Python y JavaScript** tienen grandes comunidades activas. 
    * Gran variedad de librerias y **recursos para aprender online** 

---
##### Desventajas

* **Rendimiento Limitado:**
    * Suelen ser **más lentos que lenguajes tradicionales**.
    * Interpretación en tiempo real y **falta de optimización**.

* **Dependencia de la Máquina Virtual:**
    * Requieren m**áquinas virtuales o intérpretes específicos**.
    * Puede causar problemas de **compatibilidad**.

* **Limitaciones en Aplicaciones de Alto Rendimiento:**
    * No ideales para aplicaciones que necesitan control preciso del hardware.
    * No óptimos en términos de optimización.

* **Seguridad:**
    * Más vulnerables a ataques como la **inyección de código**.
    * Requieren precauciones adicionales para mantener la seguridad.

---

#### 5.- Integracion de Codigo con las Etiquetas HTML
##### Exploracion de tecnologias como CSS y HTML5

* **HTML:**
  Es el **lenguaje de marcado estandar** utilizado para crear la estructura y el contenido de una pagina web. **HTML** utiliza etiquetas para definir elementos como encabezados, parrafos, imagenes y enlaces
* **CSS:**
  Se utiliza para dar **estilo y diseño** a las paginas web, permite **controlar la apariencia** de los elementos **HTML** como el tamaño, los colores, las fuentes y los margenes.
![bg right height:300px](https://velog.velcdn.com/images/mj9457/post/a063d5f9-a43e-4777-b21e-f3c85cb63e04/image.jpg)

---
