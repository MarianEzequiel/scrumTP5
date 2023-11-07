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

1. Saldaña Micaela Soledad.
   - **Implementar la funcionalidad para agregar un alumno al sistema.**
      - Crear la página y el formulario de inicio de sesión.
      - Implementar la lógica para verificar los datos de inicio de sesión en la base de datos. 
      - Crear la página y el formulario para agregar un alumno
      - Implementar la lógica para guardar los datos del alumno en la base de datos.
   - **Ayudar en la implementación de la funcionalidad para modificar un alumno.**
      - Colaborar en la creación del formulario con los datos precargados del alumno.
      - Ayudar en la implementación de la lógica para guardar los cambios en la base de datos.
      - Colaborar en la actualización de la página para reflejar los datos modificados en el listado.

2. Acuña, Rubén Omar.
   - **Implementar la funcionalidad para agregar un alumno al sistema.**
      - Crear la página y el formulario de inicio de sesión.
      - Implementar la lógica para verificar los datos de inicio de sesión en la base de datos. 
      - Crear la página y el formulario para agregar un alumno
      - Implementar la lógica para guardar los datos del alumno en la base de datos.
   - **Ayudar en la implementación de la funcionalidad para modificar un alumno.**
      - Colaborar en la creación del formulario con los datos precargados del alumno.
      - Ayudar en la implementación de la lógica para guardar los cambios en la base de datos.
      - Colaborar en la actualización de la página para reflejar los datos modificados en el listado.

3. Dos Santos, Lucas Emanuel.
   - **Implementar la funcionalidad para agregar un alumno al sistema.**
      - Crear la página y el formulario de inicio de sesión.
      - Implementar la lógica para verificar los datos de inicio de sesión en la base de datos. 
      - Crear la página y el formulario para agregar un alumno
      - Implementar la lógica para guardar los datos del alumno en la base de datos.
   - **Ayudar en la implementación de la funcionalidad para modificar un alumno.**
      - Colaborar en la creación del formulario con los datos precargados del alumno.
      - Ayudar en la implementación de la lógica para guardar los cambios en la base de datos.
      - Colaborar en la actualización de la página para reflejar los datos modificados en el listado.

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


    

