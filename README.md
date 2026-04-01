 13/03/2026

 Área: Programación de aplicaciones para dispositivos móviles.

 Tema: Diagnostico

 Nombre y apellido: Maldonado Roman Omar

 Preguntas:
 1.	¿a que nos referimos cuando hablamos de app?
 2.	¿Qué es el frontend y que es el backend? ¿De una definición con sus propias palabras y explique cómo se comunican habitualmente?
 3.	¿Qué es una API REST? ¿Cuál es su función principal cuando desarrollamos una aplicación para dispositivos móviles?
 4.	¿Qué es el formato JSON? Escribe un ejemplo simple de cómo se vería un objeto “alumno” con nombre, apellido y una lista de 3 notas en este formato.
 5.	¿Qué es una librería o biblioteca y que es un framework? ¿Son lo mismo? Justifique su respuesta.
 6.	¿Qué es un sistema de control de versiones y para qué sirve? Explique que sucede si 2 desarrolladores modifican la misma línea de código en el mismo archivo y como se resuelve.
 7.	¿Qué es la programación orientada a objetos (POO)? Define brevemente los conceptos de clase, objeto y herencia.
 8.	¿Cuál es el propósito de los modificadores de acceso public y private en el contexto de la programación orientada a objetos?
 9.	Explique las principales diferencias entre los sistemas operativos IOS (iPhone) y Android desde el punto de vista del desarrollo (lenguajes nativos, tiendas de aplicaciones y tipos de dispositivos). Además, mencione si conoce algún otro sistema operativo para móviles que exista o haya existido en el mercado.
 10.	 ¿Cómo piensa que una aplicación móvil podría facilitar la vida de una persona con discapacidad visual en las lajitas?
 DESARROLLO
### 1.	¿a que nos referimos cuando hablamos de app? 
 Un conjunto de programas diseñados para ejecutarse en dispositivos móviles como teléfonos, tablets, relojes. Para realizar una tarea especifica como redes sociales, juegos, herramientas de producción. Se descargan desde las tiendas o paginas oficiales.
### 2.	¿Qué es el frontend y que es el backend? ¿De una definición con sus propias palabras y explique cómo se comunican habitualmente? 
 El frontend es la parte que el usuario puede visualizar en la pantalla, mientras que el backend es la parte interna o no visible de la aplicación. Se encarga de la creación y conexión con las bases, autenticación. Asegurándose que la interfaz funcione correctamente. 
### 3.	¿Qué es una API REST? ¿Cuál es su función principal cuando desarrollamos una aplicación para dispositivos móviles?
 API REST (interfaz de programación de aplicaciones de transferencia de estado representacional) es un estilo de arquitectura que se ###considera el estándar para diseñar y crear las aplicaciones en red que impulsan la Web.
### 4.	¿Qué es el formato JSON? Escribe un ejemplo simple de cómo se vería un objeto “alumno” con nombre, apellido y una lista de 3 notas en este formato. 
JSON: Es un formato basado en texto para representar datos estructurados en la sintaxis de objetos de JavaScript. Comúnmente se usa para el intercambio de datos
ejemplo:
 {
 “dia”:13,
 “mes”:”Marzo”,
 “año”:2026,
 “peligro”:[“Viernes”, 13]
 }
### 5.	Librería y Framework
 No, no son lo mismo. La diferencia fundamental radica en el control.
 Librería (Biblioteca): Es un conjunto de funciones o recursos que tú invocas cuando los necesitas. Tú tienes el control del flujo del programa y decides cuándo llamar a la librería (ejemplo: Pandas en Python o Axios en JavaScript).
 Framework (Marco de trabajo): Es una estructura completa que define cómo debes trabajar. El framework es quien invoca tu código en los momentos adecuados. A esto se le llama Inversión de Control.
 Justificación: Mientras que en una librería tú eres el arquitecto que usa herramientas, en un framework tú rellenas los huecos de un plano ya diseñado.
### 6.	Control de Versiones y Conflictos. 
Un Sistema de Control de Versiones (VCS), como Git, es una herramienta que registra los cambios realizados en archivos a lo largo del tiempo, permitiendo recuperar versiones específicas y trabajar en equipo.
### ¿Qué sucede si dos personas modifican la misma línea? 
Ocurre lo que se conoce como un Conflicto de Fusión (Merge Conflict). El sistema no sabe qué cambio debe prevalecer y detiene el proceso de integración.
Resolución: El desarrollador debe abrir el archivo, donde el sistema marcará ambas versiones del código. Se debe elegir manualmente cuál dejar (o combinar ambas), guardar el archivo y realizar un nuevo commit para confirmar la solución.
### 7.	Programación Orientada a Objetos (POO) 
La POO es un paradigma de programación basado en el concepto de "objetos", que pueden contener datos y código.
Clase: Es el molde o plano (blueprint). Define las características y comportamientos que tendrán los objetos.
Objeto: Es la instancia de una clase. Si "Auto" es la clase, un "Toyota Corolla rojo" es el objeto.
Herencia: Es la capacidad de una clase de derivar de otra, adquiriendo sus atributos y métodos, lo que permite reutilizar código.
### 8.	Modificadores de Acceso: Public vs. Private 
Su propósito es el Encapsulamiento, es decir, proteger la integridad de los datos.
Public: El atributo o método es accesible desde cualquier parte del programa.
Private: El atributo o método solo puede ser accedido o modificado dentro de la misma clase donde fue definido. Esto evita que agentes externos alteren estados internos de forma inesperada.
### 9.	Desarrollo: iOS vs. Android 
Característica	iOS (Apple)	Android (Google)
Lenguajes Nativos	Swift, Objective-C	Kotlin, Java
Tienda oficial	App Store (Más restrictiva)	Google Play Store (Más abierta)
Dispositivos	Exclusivo de hardware Apple (iPhone)	Multimarca (Samsung, Xiaomi, Pixel, etc.)
Otros sistemas: Históricamente han existido Windows Phone/Mobile, BlackBerry OS, Symbian (Nokia) y actualmente existen alternativas como HarmonyOS (Huawei).
### 10.	Tecnología y Discapacidad Visual. 
Una aplicación móvil puede ser una herramienta transformadora mediante:
Lectores de pantalla: Conversión de texto a voz (TalkBack/VoiceOver).
Reconocimiento de IA: Identificación de objetos, colores o lectura de billetes en tiempo real usando la cámara.
Navegación asistida: GPS de alta precisión con instrucciones auditivas detalladas sobre cruces y obstáculos.
Asistentes de voz: Permitir el control total del dispositivo sin necesidad de interactuar físicamente con la pantalla táctil.
