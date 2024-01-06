[**ENGLISH**](https://github.com/nanreh-dev/nanreh/edit/master/README.en.md)
# Hernán, desarrollo de software.
## **Conocimientos Avanzados**
- **HTML**
- **CSS**, frameworks derivados como **_Bootstrap_** y **_Tailwind_** y extensiones **_Sass_** y **_Less_**.
- **Javascript** y sus derivados como la librería **_React_** o frameworks como **_Next JS_** y **_Qwik_**.
- **React Native** versiones **_Bare y EXPO_** para creación de aplicaciones **_Android e IOs_** 
- Entorno de ejecución **_Node JS_** y su framework **_Express JS_**.
- **C#** y su framework **_.NET_** (versiones .NET Framework, .Net Core y .Net X).
- **UNITY/C#**.
- **GIT** tanto versiones _GUI_ **_Sourcetree_** o línea de comandos.
- **SQL Server**.
- **Firebase**.
- **Jira**.
- Herramientas de procesado de imágenes e ilustración **_Photoshop_** e **_Illustrator_**.

## **Conocimientos Intermedios**
- **GO**.
- **C/C++**.
- **LINUX** distribución **_Arch_**.

## **Desarrollo**
- Página Web para la firma [**ARCA Software**](https://arca.com.ar/).
Se trata de una SPA con técnicas modernas de animación web, elección automática de tema claro/oscuro, y además cuenta con la posibilidad de elegir entre 4 idiomas (español, portugués, italiano e inglés).<br/>Fue diseñada en **_NEXT JS_**, lo que gracias a su modularidad permite fácilmente agregar tantos idiomas como se desee sin tener que variar ni un solo componente.
- Asimismo, para la página, fue requerimiento desarrollar el cliente de correo (smtp) el cual fue realizado en **_NODE JS_** y puesto en producción en un servidor **_Nginx_**.

## **Colaboración**
[**RETAIL 100**](http://www.retail100.com.ar/) es una empresa argentina dedicada a la organización de grandes eventos para grandes compradores, que además posee filiales en _México_, _Brasil_, _Perú_, _Chile_ y _EEUU_.

El sistema de frontend y backend fue desarrollado por la firma [**MATIRA**](https://www.matira.com.ar/) para la cual se usó **.NET Framework** tanto en **VB** como en **C#** y el soporte de datos en **SQL Server**
- El requerimiento consistió en hacer una interfaz frontend para el ingreso de nuevos inscriptos a los eventos (tanto compradores como vendedores), el cual fuese intuitivo para el operador, ya que en primera instancia se ingresaba directo por _SQL_ a la base de datos.<br/>Dicha interfaz debía contar con 2 columnas, a la izquierda una lista de los nuevos inscriptos y a la derecha las empresas que ya son parte de los eventos.<br/>El funcionamiento de la aplicación es por **_drag & drop_** y en cuanto se comienza a arrastrar un inscripto hacia la columna derecha la aplicación debe analizar si el inscripto pertence a alguna empresa existente, si es el caso la aplicación hara un desplazamiento en la columna derecha hasta la ubicación de dicha empresa y será debidamente notificado con un marcado de la zona donde soltar el inscripto.<br/>Además de hacer toda la interfaz de usuario mi labor tambien fue hacer todos los endpoints en la API para dar de alta al inscripto en las bases de datos o en su defecto dar de alta una nueva empresa.<br/>Se usaron los patrones _MVC_, _Repositorio_ e _Inyección de dependecias_ para loo relacionado con el backend y para el frontend una conjunción entre _code behind_ y _javascript_.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/cd2304ad-b7ba-4355-8c73-8283b64a0e62" />
</p>

## **Desarrollo**
- El requerimiento consistió en desarrollar una app móvil (_Android_ e _IOs_) para la antes citada [**RETAIL 100**](http://www.retail100.com.ar/), en la cual los participantes de los eventos usarían para votar por las marcas que mejor hicieron presentaciones de productos, propuestas, etc.<br/>Esta app debía contar con un sistema de autenticación que manejara tanto "Administradores", los que son los encargados de armar las encuestas, como de "Compradores", que son los que votarán por sus stands favoritos.<br/>La app está desarrollada en **_React Native_** y usa 2 tipos de backend: para la sección de encuestas se confió en **_FIREBASE_**. Para la sección de autenticación se usó una API interna de la firma que provee los datos del ingresante.<br/>Se desarrollo multilingüe (inglés, español) pero tiene la posibilidad de escalar a mas idiomas sin hacer grandes modificaciones.<br/>Tiene además la posibilidad de elegir tema claro/oscuro.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/3eb42d26-52b2-47a9-a49a-305144fd5087" />&nbsp;
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/5d2b5973-9d3e-4a09-aa08-1bb53b63ee12" />&nbsp;
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/da6d01d7-2b87-4d13-b84c-64c3950c3b3b" />
</p>

## **Colaboración**
En Argentina existen unas evaluaciones anuales para los colegios de carácter público que miden el nivel de los alumnos tanto en matemáticas como en lengua.<br/>
Estas pruebas son a nivel nacional y tienen relevancia en toda américa. Se trata de un "multiple choice" que el alumno completa en una planilla en papel.<br/>Esas planillas deben luego ser digitalizadas y se debe poder procesar todos los datos, para ser almacenados en bases de datos.<br/>Se trata de millones de evaluaciones, por lo que la aplicación de backend para procesar las mismas debe ser robusta y totalmente optimizada.<br/>Para esta labor se confió en **_.NET Framework/C#_** y como soporte de bases de datos **_SQL Server_**.<br/>Para llevar a cabo esta tarea el gobierno nacional confio en las firmas [**MATIRA**](https://www.matira.com.ar/) y [**ARCA Software**](https://arca.com.ar/).<br/>Colaboré con algunos requerimientos de mantenimiento de secciones ya funcionando y también tuve la oportunidad de desarrollar otras desde cero. Algunas fueron:
- El requerimiento consistió en diseñar una interfaz de usuario, el típico CRUD, pero que también implementara drag & drop, ya que los ítems necesitan poder ser ordenados a demanda del operador y guardados en la base de datos respetando dicho orden.<br/>Además, fui responsable también de todas las tareas de backend. 
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/f33db2c1-4719-4bb6-b6bb-5966afe40e62" />
</p>

- El requerimiento consistió en diseñar una interfaz con el fin de que el administrador pueda elegir los colores que tendrá la aplicación, tanto en los resaltados de menús (éstos detectan si el color es oscuro o claro y determinan el color de texto automáticamente), botones (ídem que para menús), pie de página, etc.<br/>También era necesario que el operador pudiera elegir algunas imágenes, como logos de encabezado, de pantalla de inicio de sesión, de pie de página, etc.<br/>En este caso, también fue requerimiento desarrollar toda la parte de backend, con guardado de preferencias en la base de datos y procesamiento y posterior almacenamiento de imágenes en el servidor.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/44f23509-2500-4380-8c69-fd028cc03de2" />
</p>

- El requerimiento consistió en desarrollar un filtro para determinar por qué criterios se buscarían las evaluaciones. Por lo tanto, en base a lo que fuera elegido en estos filtros, se crearía el formulario de búsqueda dinámicamente.<br/>Para que sea cómodo para el operador, también se usó drag & drop, ya que el orden en el que se presentan tiene relevancia.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/ee1d69a6-835d-4631-8cde-3b4987ad75ff" />
</p>

## **Desarrollo**
- Colaboración desinteresada en el desarrollo (programación) de un juego de **rol - combate por turnos** para plataformas **_Android_** en **_UNITY_**.<br/>En la captura se muestra la pantalla de selección de personajes.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/45e2ce10-8c36-4ee5-8989-a8a959961d50" />
</p>
<!--[2023-12-27 17-29-23.webm](https://github.com/nanreh-dev/nanreh/assets/100144295/a0bebf15-3874-4ad4-a30b-24cff52d13ca)
![inscriptos](https://github.com/nanreh-dev/nanreh/assets/100144295/cd2304ad-b7ba-4355-8c73-8283b64a0e62)
-->
<!--![game](https://github.com/nanreh-dev/nanreh/assets/100144295/45e2ce10-8c36-4ee5-8989-a8a959961d50)
![filtros](https://github.com/nanreh-dev/nanreh/assets/100144295/ee1d69a6-835d-4631-8cde-3b4987ad75ff)
![replaces](https://github.com/nanreh-dev/nanreh/assets/100144295/f33db2c1-4719-4bb6-b6bb-5966afe40e62)
![look](https://github.com/nanreh-dev/nanreh/assets/100144295/44f23509-2500-4380-8c69-fd028cc03de2)
![AppAdmin](https://github.com/nanreh-dev/nanreh/assets/100144295/3eb42d26-52b2-47a9-a49a-305144fd5087)
![AppEstadisticas](https://github.com/nanreh-dev/nanreh/assets/100144295/da6d01d7-2b87-4d13-b84c-64c3950c3b3b)
![AppVotos](https://github.com/nanreh-dev/nanreh/assets/100144295/5d2b5973-9d3e-4a09-aa08-1bb53b63ee12)
<!--
**hilonegro52/hilonegro52** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
Hola! 👋
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
