### Hola! 👋, mi nombre es Hernán y soy programador

## **Conocimientos Avanzados**
- **HTML**
- **CSS**, framaworks derivados como **_Bootstrap_** y **_Tailwind_** y extensiones como **_Sass_** y **_Less_**.
- **Javascript** y sus derivados como la librería **_React_** o frameworks como **_Next JS_** y **_Qwik_**.
- **React Native** versiones **_Bare y EXPO_** para creación de aplicaciones **_Android e IOs_** 
- Entorno de ejecución **_Node JS_** y su framework **_Express JS_**.
- **C#** y su framework **_.NET_** (versiones .NET Framework, .Net Core y .Net X).
- **UNITY/C#**.
- **GIT** tanto versiones _GUI_ como **_Sourcetree_** o línea de comandos.
- **SQL Server**.
- **Firebase**.
- Herramientas de procesado de imágenes e ilustración como **_Photoshop_** e **_Illustrator_**.

## **Conocimientos Intermedios**
- **GO**.
- **C/C++**.
- **LINUX** versión **_Arch_**.

## **Desarrollo**
- Página Web para la firma [**ARCA Software**](https://arca.com.ar/).
Se trata de una SPA con técnicas modernas de animación web, elección automática de tema claro/oscuro, y además cuenta con la posibilidad de elegir entre 4 idiomas (español, portugues, italiano e ingles). Fué diseñada en **_NEXT JS_**, lo qué gracias a su modularidad permite facilmente agregar tantos idiomas como se desee sin tener que variar ni un solo componente.
- Asimismo, para la página, fué requerimiento desarrollar el cliente de correo (smtp) el cual fué realizado en **_NODE JS_** y puesto en producción en un servidor **_Nginx_**.

## **Colaboración**
[**RETAIL 100**](http://www.retail100.com.ar/) es una empresa argentina dedicada a la organización de grandes eventos para grandes compradores, qué además posee filiales en _Méjico_, _Brasil_, _Perú_, _Chile_ y _EEUU_. es una empresa argentina dedicada a la organización de grandes eventos para grandes compradores, qué además posee filiales en _Méjico_, _Brasil_, _Perú_, _Chile_ y _EEUU_.

El sistema de frontend y backend fue desarrollado por la firma [**MATIRA**](https://www.matira.com.ar/) para la cual se usó **.NET Framework** tanto en **VB** como en **C#** y el soporte de datos en **SQL Server**
- El requerimiento fué hacer una interfaz frontend para el ingreso de nuevos inscriptos a los eventos (tanto compradores como vendedores), el cual fuese intuitivo para el operador, ya que en primera instancia se ingresaba directo por _SQL_ a la base de datos. Dicha interfaz debía contar con 2 columnas, a la izquierda una lista de los nuevos inscriptos y a la derecha las empresas que ya son parte de los eventos. El funcionamiento de la aplicación es por **_drag & drop_** y en cuanto se comienza a arrastrar un inscripto hacia la columna derecha la aplicación debe analizar si el inscripto pertence a alguna empresa existente, si es el caso la aplicación hara un desplazamiento en la columna derecha hasta la ubicación de dicha empresa y será debidamente notificado con un marcado de la zona donde soltar el inscripto. Así mismo si no existiera una empresa asociada al inscripto le indicara que debe soltarlo en el lugar de creacion de "nueva empresa". Además de hacer toda la interfaz de usuario mi labor tambien fue hacer todos los endpoints en la API para dar de alta al inscripto en las bases de datos o en su defecto dar de alta una nueva empresa. Se usaron los patrones _MVC_, _Repositorio_ e _Inyección de dependecias_ para loo relacionado con el backend y para el frontend una conjunción entre _code behind_ y _javascript_.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/cd2304ad-b7ba-4355-8c73-8283b64a0e62" />
</p>

## **Desarrollo**
- El requerimiento fué desarrollar una app móvil (_Android_ e _IOs_) para la antes citada [**RETAIL 100**](http://www.retail100.com.ar/), en la cual los participantes de los eventos usarían para votar por las marcas que mejor hicieron presentaciones de productos, propuestas, etc. Esta app debía contar con un sistema de autenticación que manejara tanto "Administradores", los qué son los encargados de armar las encuestas, como de "Compradores", que son los que votarán por sus stands favoritos. La app está desarrollada en **_React Native_** y usa 2 tipos de backend: para la sección de encuestas se confió en **_FIREBASE_**. Para la sección de autenticación se usó una alianza entre **_FIREBASE_** y una API interna de la firma qué provee los datos del ingresante. Se desarrollo multilingüe (ingles, español) pero tiene la posibilidad de escalar a mas idiomas sin hacer grandes modificaciones. Tiene además la posibilidad de elegir tema claro/oscuro y de usar la cámara del móvil para tomarse una foto o bien usar una disponible en la galería del mismo, las imagenes pueden ser redimensionadas dentro de la app sin recurrir a ningún elemento externo.

## **Colaboración**
En Argentina existen unas evaluaciones anuales para los colegios de orden público que miden el nivel de los alumnos tanto en matemáticas como en lengua.
Estas pruebas son a nivel nacional y tienen relevancia en toda américa. Se trata de un "multiple choice" que el alumno completa en una planilla en papel. Esas planillas deben luego ser digitalizadas y se debe poder procesar todos los datos, para ser almacenados en bases de datos. Se trata de millones de evaluaciones, por lo que la aplicación de backend para procesar las mismas debe ser robusta y totalmente optimizada. Para esta labor se confio en **_.NET Framework/C#_** y como soporte de bases de datos **_SQL Server_**. Para esta labor el gobierno nacional confio en las firmas [**MATIRA**](https://www.matira.com.ar/) y [**ARCA Software**](https://arca.com.ar/). Colaboré con algunos requerimientos de mantenimiento de secciones ya funcionando y también tuve la oportunidad de desarrollar otras desde cero. Algunas fueron:
- El requerimiento fué diseñar una interfaz de usuario, el típico _CRUD_ pero que también implementase _drag & drop_, ya que los items necesitan poder ser ordenados a demanda del operador y guardados en la base de datos respetando dicho orden. Además fui responsable también de todas las tareas de backend. 
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/f33db2c1-4719-4bb6-b6bb-5966afe40e62" />
</p>

-El requerimiento fué diseñar una interfaz con el fin que el administrador pueda elegir los colores que tendrá la interfaz, tanto en los resaltados de menúes (estos detectan si el color es oscuro o claro y determina el color de texto automaticamente), botones (idem que para menúes), pié de página, etc. También era necesario que el operador pudiera elegir algunas imágenes, como ser logos de encabezado, de pantalla de login, de pié de página, etc. En este caso también fue requerimiento desarrollar toda la parte de backend, con guardado de preferencias en base de datos y procesado y posterior almacenado de imagenes en el server.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/44f23509-2500-4380-8c69-fd028cc03de2" />
</p>

- El requerimiento fué desarrollar un filtro para determinar por que criterios se buscarian las evaluaciones. Por lo tanto en base a lo que fuera elegido en estos filtros se crearía el formulario de busqueda dinamicamente. Para que sea cómodo para el operador también se uso _drag & drop_, ya que el orden en el que se presentan tiene relevancia.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/ee1d69a6-835d-4631-8cde-3b4987ad75ff" />
</p>

## **Desarrollo**
- Colaboración desinteresada en el desarrollo (programación) de un juego de **rol - combate por turnos** para plataformas **_Android_** en **_UNITY_**. En la captura se muestra la pantalla de selección de personajes.
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
<!--
**hilonegro52/hilonegro52** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
