[<img src="https://github.com/nanreh-dev/nanreh/assets/100144295/adc20965-e0bf-4a22-9a6d-6d3fbe23d229" />](https://github.com/nanreh-dev/nanreh/blob/master/README.md)
&nbsp;
<img src="https://github.com/nanreh-dev/nanreh/assets/100144295/3dc7c0f8-868b-47fe-b786-5b0842a76c9b" />
## **Advanced Skills**
- **HTML**
- **CSS**, derived frameworks like **_Bootstrap_** and **_Tailwind_**, and extensions **_Sass_** and **_Less_**.
- **Javascript** and its derivatives, such as the library **_React_** or frameworks like **_Next JS_** and **_Qwik_**.
- **React Native** versions **_Bare y EXPO_** for creating **_Android e IOs_** apps. 
- Runtime enviroment **_Node JS_** and its framework **_Express JS_**.
- **C#** and its framework **_.NET_** (versions .NET Framework, .Net Core and .Net X).
- **UNITY/C#**.
- **GIT** using both _GUI_ versions like **_Sourcetree_** or command line.
- **SQL Server**.
- **Firebase**.
- **Jira**.
- Image processing and illustration tools **_Photoshop_** and **_Illustrator_**.

## **Intermediate Skills**
- **GO**.
- **C/C++**.
- **LINUX** distribution **_Arch_**.

## **Development**
- Website for [**ARCA Software**](https://arca.com.ar/).
This is a Single Page Application (SPA) with modern web animation techniques, automatic light/dark theme switching, and the ability to choose from 4 languages (Spanish, Portuguese, Italian, and English).<br/>It was designed in **_NEXT JS_**, which, due to its modularity, allows for easy addition of as many languages as desired without having to alter a single component.
- Additionally, for the website, it was a requirement to develop the email client (SMTP), which was implemented in **_NODE JS_** and deployed on an **_Nginx_** server.

## **Collaboration**
[**RETAIL 100**](http://www.retail100.com.ar/) is an Argentine company dedicated to organizing large events for significant buyers, with branches in Mexico, Brazil, Peru, Chile, and the USA.

The frontend and backend system was developed by the firm [**MATIRA**](https://www.matira.com.ar/) using **.NET Framework** in both **VB** and **C#**, with the data support in **SQL Server**
- The requirement was to create a frontend interface for entering new registrations for events (both buyers and sellers), which would be intuitive for the operator since initially, entries were made directly into the database via _SQL_.<br/>This interface should have 2 columns, with a list of new registrants on the left and the companies already participating in the events on the right.<br/>The application operates through **_drag & drop_**, and as a registrant is dragged to the right column, the application must analyze if the registrant belongs to an existing company. If so, the application will scroll to the location of that company in the right column, and the operator will be notified with a marked area to drop the registrant.<br/>In addition to designing the entire user interface, my role also involved creating all the endpoints in the API to register the participant in the databases or, if necessary, register a new company.<br/>Patterns such as _MVC_, _Repository Pattern_ and _Dependency Inyection_  were used for backend-related tasks, and for the frontend, a combination of code behind and javascript was utilized.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/cd2304ad-b7ba-4355-8c73-8283b64a0e62" />
</p>

## **Development**
- The requirement involved developing a mobile app (_Android_ and _IOs_) for the aforementioned [**RETAIL 100**](http://www.retail100.com.ar/),  where event participants would use it to vote for the brands that delivered the best product presentations, proposals, etc.<br/>This app needed to have an authentication system that handles both "Administrators," who are responsible for creating surveys, and "Buyers," who vote for their favorite stands.<br/>The app is developed in **_React Native_** and uses two types of backend: for the survey section, it relies on **_FIREBASE_**. For the authentication section, an internal API from the company was used, providing data for the login process.<br/>It is developed to be multilingual (English, Spanish) but can be easily scaled to more languages without major modifications.<br/>Additionally, it has the option to choose between light and dark themes.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/3eb42d26-52b2-47a9-a49a-305144fd5087" />&nbsp;
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/5d2b5973-9d3e-4a09-aa08-1bb53b63ee12" />&nbsp;
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/da6d01d7-2b87-4d13-b84c-64c3950c3b3b" />
</p>

## **Collaboration**
In Argentina, there are annual assessments for public schools that measure students' proficiency in both mathematics and language.<br/>
These nationwide tests hold significance throughout America. They are in a "multiple-choice" format, where students fill out a paper form. These sheets must then be digitized, and the data processed for storage in databases.<br/>Given the millions of evaluations, the backend application to process them must be robust and highly optimized. For this task, trust was placed in **_.NET Framework/C#_** with **_SQL Server_** as the database support.<br/>To carry out this work, the national government relied on the firms [**MATIRA**](https://www.matira.com.ar/) and [**ARCA Software**](https://arca.com.ar/).<br/>I collaborated on some maintenance requirements for existing sections and also had the opportunity to develop new ones from scratch. Some of them include:
- The requirement involved designing a user interface, the typical CRUD, but it also needed to implement drag & drop functionality. This was necessary because items needed to be sortable based on the operator's demand and saved in the database while preserving the specified order.<br/>Additionally, I was also responsible for all backend tasks. 
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/f33db2c1-4719-4bb6-b6bb-5966afe40e62" />
</p>

- The requirement was to design an interface so that the administrator can choose the colors of the application, including menu highlights (which automatically detect whether the color is dark or light and determine the text color accordingly), buttons (similarly to menus), footer, etc.<br/> It was also necessary for the operator to be able to choose some images, such as logos for the header, login screen, footer, etc.<br/> In this case, it was also a requirement to develop the entire backend, including saving preferences in the database and processing and subsequently storing images on the server.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/44f23509-2500-4380-8c69-fd028cc03de2" />
</p>

- The requirement was to develop a filter to determine the criteria for searching evaluations. Therefore, based on the chosen filters, the search form would be dynamically generated.<br/>To make it convenient for the operator, drag & drop functionality was also used since the order of presentation is relevant.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/ee1d69a6-835d-4631-8cde-3b4987ad75ff" />
</p>

## **Development**
- Uncompensated collaboration in the development (programming) of a turn-based role-playing game for **_Android_** platform developed on **_UNITY/C#_**.<br/>The screenshot displays the character selection screen.
<p align="center">
  <img src="https://github.com/nanreh-dev/nanreh/assets/100144295/45e2ce10-8c36-4ee5-8989-a8a959961d50" />
</p>
