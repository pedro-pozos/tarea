## Introducción


## ¿Qué es un  MVC?

MVC es una propuesta de arquitectura del software utilizada para separar el código por sus distintas responsabilidades, manteniendo distintas capas que se encargan de hacer una tarea muy concreta, lo que ofrece beneficios diversos.

El patrón MVC se ha convertido en un estándar para el desarrollo de aplicaciones que permite separar la aplicación en tres capas que, aunque estén relacionadas no siempre tiene porque estar juntas. Estas capas son la Vista, el Controlador y el Modelo y a continuación se explica que es cada uno

•	El Modelo que contiene una representación de los datos que maneja el sistema, su lógica de negocio, y sus mecanismos de persistencia

•	La Vista, o interfaz de usuario, que compone la información que se envía al cliente y los mecanismos interacción con éste.

•	El Controlador, que actúa como intermediario entre el Modelo y la Vista, gestionando el flujo de información entre ellos y las transformaciones para adaptar los datos a las necesidades de cada uno.



## Desarrollo

## ¿Que frameworks utiliza el modelo MVC?

1.-CodeIgniter

CodeIgniter es un framework PHP que usa una arquitectura de Model View Controller (MVC). En términos sencillos, eso significa que CodeIgniter utiliza diferentes componentes para manejar tareas de desarrollo específicas. Este enfoque es muy popular entre los desarrolladores porque permite crear aplicaciones web altamente escalables con un tamaño más reducido.

2.-Zend

Zend te permite enfocarte solo en los componentes y funciones que quieres, e ignorar todo lo demás. Gracias a este enfoque y la naturaleza orientada a objetos del framework, deberías poder reutilizar gran parte del código que escribas, lo que siempre es una buena noticia. Además, es bastante fácil integrar la plataforma con bibliotecas externas para ampliar aún más su funcionalidad.

3.-Phalcon

Phalcon es un poco extraño en el mundo de los frameworks PHP. Su código fuente está escrito en C, por lo que es básicamente una extensión C de PHP. Esto suena raro, pero en la práctica, resulta ser uno de los frameworks más rápidos que hemos tenido el placer de usar.

##  ¿Qué ventajas ofrece el modelo MVC?

Muchos frameworks MVC ya incluyen librerías de Javascript como Jquery, lo que te facilitará validar formularios (Ej. Jquery.Validate) en el cliente y en el servidor.

Los frameworks están creados para facilitar el trabajo de los desarrolladores, encontrarás clases para controlar fechas, URL's, Webservices, etc. lo que tiene una gran ventaja en cuanto a productividad. Inicialmente como es lógico habrá una curva de aprendizaje, pero luego tendrás muchos beneficios.

Un Framework MVC te ayuda a controlar los recursos del servidor, evitando Bugs que puedan repercutir en el rendimiento, por ejemplo, muchas veces olvidamos cerrar conexiones a la base de datos, sobrecargando el servidor.

Es posible agregar múltiples representaciones de los datos.

Permite que el sistema sea escalable si es requerido.



##  ¿Que otros modelos/frameworks existen de patrones de diseño?

Modelo MV-VM

MVVM significa Modelo Vista VistaModelo, porque en este patrón de diseño se separan los datos de la aplicación, la interfaz de usuario pero en vez de controlar manualmente los cambios en la vista o en los datos, estos se actualizan directamente cuando sucede un cambio en ellos, por ejemplo si la vista actualiza un dato que está presentando se actualiza el modelo automáticamente y viceversa.


## Ejemplifique un modelo MVC en el lenguaje dde preferencia



## Referenciass

https://si.ua.es/es/documentacion/asp-net-mvc-3/1-dia/modelo-vista-controlador-mvc.html

https://www.hostinger.mx/tutoriales/mejores-frameworks-php/

https://www.adictosaltrabajo.com/2012/10/07/zk-mvc-mvvm/

https://medium.com/@maniakhitoccori/los-10-patrones-comunes-de-arquitectura-de-software-d8b9047edf0b
