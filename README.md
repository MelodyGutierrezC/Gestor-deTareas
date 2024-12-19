# Gestor-deTareas

Manual de Usuario
Proyecto: Gestor de Tareas
Revisión: final

MATERIA
Taller de Programación
                                                         
INTEGRANTES:

Rivera Picon Carlos  Jhoel

Gutierrez Caero Melody Alejandra

Cayo Huañarraya Anahy 




![image](https://github.com/user-attachments/assets/fb905a33-0b3e-4678-a5b1-d76e7c97ec7a)

Contenido 

1.	Descripción....................................................................................... 1

1.1Requerimientos ..................................................................................... 2

2.	Instalación ..................................................................................................... 3

3.	Funciones .......................................................................................................4

       3.1 Inicio de Sesión ...................................................................................... 5

       3. 2  Captura Crear usuario ....................................................................... 5

3.3	Mostrar usuarios ............................................................................... 6

3.4	 Crear tarea usuario ......................................................................... 7

3.5	   Lista de tarea del usuario .............................................................8

3.6 Mostar tarea de usuario.......................................................................9

4	Información adicional .............................................................................. 10


1 .DESCRIPCION 

El Gestor de Tareas es un sistema desarrollado en NetBeans que ofrece una solución práctica y eficiente para la organización y administración de actividades. Este sistema se estructura en dos roles principales, Administrador y Usuario, cada uno con funcionalidades específicas diseñadas para cubrir necesidades particulares de gestión.

Características principales con Roles definidos:

 Administrador:
 ° Acceso a funcionalidades avanzadas como:
 ° Inicio: Vista principal con un resumen de actividades y acceso rápido a las herramientas * ° principales.
° Gestión de usuarios: Administración de cuentas de usuarios registrados en el sistema.
° Lista de usuarios: Visualización y gestión del listado completo de usuarios.
° Crear tarea: Registro de nuevas tareas asignables a usuarios específicos.
° Lista de tareas: Administración y visualización de todas las tareas creadas en el sistema.
° Historial: Registro detallado de todas las acciones realizadas en el sistema para fines de auditoría.

Usuario:
*Acceso a funciones específicas para la gestión de tareas personales, tales como:
*Inicio: Resumen de tareas asignadas y estado general.
*Lista de tareas asignadas: Visualización de las tareas que le han sido asignadas, junto con su estado y detalles.
*Historial: Registro de las actividades y acciones relacionadas con sus tareas.

2. REQUIRIMIETO :

Sistema Operativo:
o	Windows 7 o superior
o	macOS 10.12 o superior
o	Linux (Distribuciones modernas como Ubuntu, Fedora, etc.)

Lenguaje de Programación:
o	Java 8 o superior 

Entorno de Desarrollo:
o	NetBeans IDE 

Bibliotecas y Dependencias:
o	JDK 8 o superior
o	JavaFX (Si se utiliza para la interfaz gráfica).

Requerimientos de Hardware

Procesador:
o	Mínimo Intel Core i3 o equivalente.

Memoria RAM:

o	Mínimo 4 GB de RAM (se recomienda 8 GB para mejor rendimiento).
Espacio en Disco Duro:

o	Mínimo 100 MB de espacio libre para la instalación y funcionamiento del sistema.
Pantalla:
o	Resolución mínima de 1280x720 píxeles para una visualización adecuada de la interfaz gráfica.


INSTALACION:

Paso A :

Instalar Java JDK y NetBeans IDE
Descarga e instala Java JDK 8 o superior desde Oracle.
Descarga e instala NetBeans IDE desde NetBeans.

![image](https://github.com/user-attachments/assets/84f84256-8237-4007-b50b-60ce459b650c)





![image](https://github.com/user-attachments/assets/e7f21f38-7d8c-4f89-8f71-2d4a211ff542)



Escoges la versión que gustes y la capacididad de tu computador
PASO B 

Una vez ya descagramos procedemos a instalar 


![image](https://github.com/user-attachments/assets/7d07513f-1e5c-4a38-8772-92a6fce7cecf)



PASO C 

Ya instalada y ponemos en función 

![image](https://github.com/user-attachments/assets/0cc60fa6-ae91-42dc-abc6-3fbfd65e4ac9)


![image](https://github.com/user-attachments/assets/d5d180f3-c0a7-46b6-9c16-bff3e55bf05f)

FUNCIONES 

Una vez que todo está listo, comenzamos a crear la interfaz de la aplicación "Gestor de Tareas", comenzando con la vista para el Administrador. Al iniciar sesión como Administrador, se accede a la pantalla principal, que presenta un panel de navegación con las opciones principales: Gestión de Usuarios, Lista de Usuarios, Crear Tarea, Lista de Tareas y Historial. Desde la sección de Gestión de Usuarios, el Administrador puede crear, modificar o eliminar usuarios, completando un formulario con los datos del nuevo usuario, como nombre, correo electrónico, contraseña y rol, eligiendo entre Administrador o Usuario. En la Lista de Usuarios, se muestran todos los usuarios registrados con sus roles, y el Administrador puede buscarlos, filtrarlos o eliminarlos según sea necesario. Para Crear Tarea, el Administrador llena un formulario con los detalles de la tarea, como nombre, descripción, fecha de vencimiento y asignación de usuario. Las tareas pueden ser consultadas en la Lista de Tareas, donde el Administrador puede ver el estado de cada tarea mediante un sistema de colores, lo que facilita el seguimiento del progreso. Finalmente, el Administrador puede acceder al Historial, donde se muestra el registro de todas las tareas completadas, con detalles sobre las fechas de asignación y finalización, así como el estado de cada tarea. De esta manera, el Administrador tiene control total sobre la gestión de usuarios y tareas dentro del sistema.

3.1 INICIO DE SESION 

Al iniciar sesión en el Gestor de Tareas, se solicita al usuario ingresar su nombre de usuario y contraseña. Si el usuario no está registrado, puede hacer clic en la opción "Registrar", donde tendrá la posibilidad de crear una cuenta como Usuario o Administrador. El proceso de registro implica ingresar los datos necesarios, como el nombre completo, correo electrónico, contraseña y seleccionar el rol que se desea asignar. Una vez registrado, el usuario podrá acceder al sistema con las credenciales proporcionadas, ya sea como Administrador o Usuario, según el rol elegido durante el registro.

![image](https://github.com/user-attachments/assets/41e227b3-7dd6-47a6-8ec8-a07491ea8446)




![image](https://github.com/user-attachments/assets/477b8f81-600f-439e-9f81-04cf4f51488a)


3.1 CAPTURA CREAR USUARIO

En el sistema, el Administrador tiene la capacidad de crear usuarios, ya sea como Administrador o Usuario. Para ello, el Administrador ingresa los datos del nuevo usuario, como su nombre, correo electrónico, rol y contraseña. Una vez completado el formulario, el sistema guarda la información en la lista de usuarios y, dependiendo del rol asignado, el nuevo usuario tendrá acceso a las funcionalidades correspondientes. El acceso se realiza con el correo y la contraseña proporcionados.

![image](https://github.com/user-attachments/assets/1e30b1c6-1a9b-4b98-863d-696995a9e793)



3.2 CAPTURA MOSTRAR USUARIO 

El sistema dispone de una lista de usuarios, que muestra los nombres de todos los Usuarios y Administradores registrados en el sistema. Esta lista permite al Administrador visualizar de manera organizada a los usuarios activos, tanto los que tienen rol de Administrador como los que tienen rol de Usuario. A través de esta vista, el Administrador puede realizar un seguimiento de los usuarios registrados, gestionando y controlando el acceso y roles asignados a cada uno, lo que facilita el manejo del sistema y la asignación de tareas.


![image](https://github.com/user-attachments/assets/ab7b0e5c-2ac3-4e41-90f6-7439837047c6)




3.3 CAPTURA CREAR TAREA DEL USUARIO

El sistema cuenta con una opción de crear tarea, que permite al Administrador asignar tareas exclusivamente a los Usuarios registrados que están en la lista de usuarios. Al crear una tarea, el Administrador selecciona el usuario destinatario, ingresa la descripción de la tarea, establece la fecha de vencimiento y define otros detalles importantes, como la prioridad. Esta funcionalidad garantiza que solo los usuarios previamente registrados puedan ser asignados a tareas, lo que facilita la gestión de las responsabilidades dentro del sistema


![image](https://github.com/user-attachments/assets/d7cfce89-8fb6-428c-a3ed-1029c78f3dd7)




3.4 LISTA DE TAREAS DE USUSARIO 

Después de crear una tarea, el Administrador puede ver la lista de tareas asignadas a cada usuario. Esta lista muestra todas las tareas que han sido asignadas, con un sistema de colores que indica el estado de la tarea (por ejemplo, alto , media, baja). Este sistema visual facilita el seguimiento del avance de cada tarea. Además, como se puede observar en la imagen, los colores proporcionan una forma rápida de identificar el estado de las tareas, mejorando la eficiencia en la gestión y seguimiento de las actividades asignadas.
4o mini


![image](https://github.com/user-attachments/assets/b934e36d-e699-4857-9ecb-abfd6622a84b)



El historial en el sistema permite tanto al Administrador como al Usuario consultar un registro detallado de todas las tareas realizadas. Este historial muestra un listado de tareas anteriores, incluyendo información como el nombre de la tarea, su estado (completada, pendiente, etc.), la fecha de asignación y la fecha de finalización. Esto proporciona una visión clara del progreso de las tareas a lo largo del tiempo, permitiendo hacer un seguimiento de las actividades pasadas y evaluar el rendimiento de los usuarios

![image](https://github.com/user-attachments/assets/4cf18703-5696-410b-88ab-adbbb3f4d8c5)



3.5 MOSTRAR TAREA DE USUARIO 

El usuario tiene acceso a una vista donde puede ver las tareas asignadas. En esta sección, el usuario podrá ver el nombre de la tarea, la descripción, quién le asignó la tarea y su estado actual. Además, el usuario puede marcar una tarea como realizada una vez que haya completado la actividad, lo que actualiza automáticamente el estado de la tarea en el sistema. También tiene acceso a su propio historial, donde podrá consultar todas las tareas que ha realizado previamente, con detalles sobre el estado, la fecha de asignación y finalización, permitiéndole hacer un seguimiento de su progreso a lo largo del tiempo.

![image](https://github.com/user-attachments/assets/6eaca185-98c1-468f-8ba0-6e7183aed6c8)




![image](https://github.com/user-attachments/assets/fd5eb709-872d-4558-b09d-c85288ccb29f)



4.	CONCLUSION 

En resumen, el Gestor de Tareas proporciona una herramienta eficaz para organizar y gestionar las actividades dentro de un equipo. Con una interfaz que permite al Administrador crear y asignar tareas a los Usuarios registrados, realizar un seguimiento de su progreso mediante un sistema visual de colores y consultar un historial detallado de tareas completadas. Por su parte, los Usuarios pueden visualizar las tareas asignadas, marcarlas como realizadas y revisar su propio historial para evaluar su desempeño. Este sistema contribuye a una mejor gestión del tiempo, optimiza la distribución de tareas y facilita el seguimiento del avance del proyecto.
