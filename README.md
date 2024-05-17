Esta aplicación móvil ha sido desarrollada utilizando el framework Ionic y Firebase Authentication. Permite a los usuarios registrarse, iniciar sesión y acceder a una página de inicio (dashboard). La autenticación de usuarios se gestiona mediante Firebase Authentication.

Características clave:

Registro de Usuarios: Los usuarios pueden registrarse proporcionando un correo electrónico y una contraseña.
Inicio de Sesión: Los usuarios pueden iniciar sesión utilizando su correo electrónico y contraseña.
Página de Inicio: Una vez autenticados, los usuarios son redirigidos a la página de inicio (dashboard).
La estructura del proyecto incluye:

HomePage: Página principal que se muestra después del inicio de sesión.
LoginPage: Página de inicio de sesión de usuarios.
RegisterPage: Página de registro de nuevos usuarios.
Configuración de Firebase: Se realiza en el archivo environment.ts, donde se encuentra la configuración de Firebase Authentication.
La aplicación utiliza las siguientes dependencias principales:

Ionic Framework: Proporciona la estructura y los componentes UI para aplicaciones móviles híbridas con Angular.
@ionic/angular: Componentes y servicios de Ionic para Angular.
Firebase para Angular: Para integrar Firebase Authentication.
@angular/fire: Integración de Firebase con Angular.
firebase: Biblioteca de Firebase para operaciones de autenticación y otros servicios.
En el desarrollo, se utilizan herramientas como Angular CLI, Angular Firebase, firebase-tools, Typescript, Node.js y npm, AngularFire, entre otras, para generar, desarrollar y probar la aplicación.

El proyecto demuestra cómo combinar Ionic Framework con Firebase Authentication para crear una experiencia de registro e inicio de sesión eficiente y segura en una aplicación móvil.
