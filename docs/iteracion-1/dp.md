# Documento de diseño y planificación 
Este documento posee el diseño y la planificación tentativa para el desarrollo del sistema a lo largo de la iteración 1.

**Lider de la iteración**: Saldaña Micaela Soledad.

## Backlog de iteración
Conforme a lo que respecta la iteración 1, se han elegido las siguientes historias de usuario.

**P1**: Como preceptor, quiero poder agregar alumnos al sistema. <br> 
**P2**: Como preceptor, quiero poder eliminar una alumnos del sistema en caso de que se haya cargado incorrectamente. <br>
**P3**: Como preceptor, quiero poder modificar los datos de los alumnos. <br>

Dichas historias de usuario conforman un ABM básico de un alumno. 

## Trabajo en equipo y Tareas
Las tareas, desarrolladas en equipo, se dividen de la siguiente manera, siendo cada columna un miembro del equipo.

| Leonardo Quiroga | Martin Lacheski | Jose luis Montejano |
| -----------| ------------------|-----------------|
| Elaborar la clase Habitación. | Establecer conexión desde el entorno de desarrollo de Java a la BD (librerías, configuraciones, etc). | Creación de formulario inicial para el alta de la habitación.
| Codificación de lógica en capa de negocio para captar datos desde el cliente| Codificación de lógica en capa de modelos para almacenar los datos captados en capa de negocio | Codificación de controles en el formulario para depuración de datos (campos con números que solamente acepten números, etc) |
| Codificación de lógica en capa de modelos y negocio para obtener las habitaciones cargadas. | Elaboración estética de listado en template | Codificación en capa de modelos para obtención de una habitación en específico|
| Codificación en capa de negocio y template para elegir una habitación en específico la cual será expuesta en el mismo formulario de alta de habitación. | Elaboración de clase tipoHabitacion y relación con clase Habitacion| Creación de formulario de alta de tipoHabitación | Codificación de lógica en capa de negocio y modelos para almacenar los datos cargados en el formulario de alta de tipoHabitacion|
| Elaboración de botón de "Eliminar", ubicado en cada renglon del listado de habitaciones | Codificación en capa de negocio y modelos para eliminación de una habitación | Codificación de control para no cargar habitaciones y/o tipos de habitaciones repetidas |



## Diseño OO

![alt text](../../img/CLASE-alumno.png)


## WireFrame

- Iniciar sesión Escritorio <br>
![alt text](../../img/LOGIN-1.png)

- Iniciar sesión Movil <br>
![alt text](../../img/LOGIN-2.png)

- Lista de alumnos
![alt text](../../img/READ-alumno.png)

- Agregar Alumno <br>
![alt text](../../img/CREATE-alumno.png)

- Modificar Alumno <br>
![alt text](../../img/UPDATE-alumno.png)

- Eliminar Alumno <br>
![alt text](../../img/DELETE-alumno.png)


## Casos de Uso

1. Agregar un alumno
    - El usuario visita la página web y este le pedirá inicie sesión.
    - El sistema lo redirecciona a la pantalla apropiada.
    - El usuario hace clic en el botón "Agregar". 
    - El sistema redirecciona a un formulario tipo con los datos necesarios para un alumno.
    - El usuario completa los campos requeridos en el formulario desplegado y hace clic en "Guardar y cerrar" o "Guardar y cargar otro".
    - El sistema actualiza la página para que el nuevo alumno se vea reflejada en el listado.

2. Modificar un alumno
    - El usuario, en la sección de alumnos, hace clic en el botón "Editar".
    - El sistema redirecciona a un formulario con los datos precargados del alumno elegido.
    - El usuario modifica los campos que cree apropiados modificar y hace clic en el botón "Guardar cambios"
    - El sistema modifica los datos en la base de datos y actualiza la página para reflejar los datos modificados en el listado.

3. Eliminar un alumno
    - El usuario, en la sección de alumnos, hace clic en el botón de "Eliminar".
    - El sistema despliega un modal a modo de confirmación indicando en un mensaje si se está seguro de eliminar al alumno.
    - El usuario hace clic en el botón "Aceptar". 
    - El sistema esconde el modal, elimina los datos en la base de datos y actualiza la página para reflejar los datos modificados en el listado.


    

