# Documento de diseño y planificación 
Este documento posee el diseño y la planificación tentativa para el desarrollo del sistema a lo largo de la iteración 3.

**Lider de la iteración**: Acuña, Rubén Omar.

## Backlog de iteración
Conforme a lo que respecta la iteración 3, se han elegido las siguientes historias de usuario.

- **P1**: Como preceptor, quiero poder registrar la asistencia de los alumnos de acuerdo a su materia. <br>
- **P2**: Como preceptor, quiero poder registrar la ausencia de los alumnos de acuerdo a su materia. <br>
- **P3**: Como preceptor, quiero poder registrar la ausencia justificada de los alumnos de acuerdo a su materia. <br>
- **P7**: Como preceptor, quiero poder imprimir el listado de asistencia. <br>

Dichas historias de usuario conforman un lo que sería gestor de asistencia. 


## Diseño OO

![alt text](../../img/CLASE-asistencia.png)


## WireFrame

- Asistencias Escritorio <br>
![alt text](../../img/ASISTENCIA-1.png)

- Asistencias Movil <br>
![alt text](../../img/ASISTENCIA-2.png)


## Casos de Uso

1. Registrar Asistencia
    - El usuario visita la página web y se dirige a la sección de "Registrar Asistencia".
    - El sistema lo redirecciona a la pantalla apropiada.
    - El usuario hace clic en la lista desplegable "Materia". 
    - El sistema despliega la lista de materias registradas en el sistema.
    - El usuario selecciona la materia correspondiente.
    - El sistema carga el listado de alumnos matriculados en la materia seleccionada.
    - El usuario hace clic en la lista desplegable "Año". 
    - El sistema despliega la lista de los años lectivos.
    - El usuario selecciona el año lectivo.
    - El usuario hace click en los "alumnos presentes".
    - El usuario hace click en los "alumnos ausentes".
    - El usuario hace click en los "alumnos ausentes justificados".
    - El usuario hace click en el boton "Guardar".
    - El sistema envía los datos y limpia el formulario.
  
   2. Imprimir Asistencia
    - El usuario visita la página web y se dirige a la sección de "Registrar Asistencia".
    - El sistema lo redirecciona a la pantalla apropiada.
    - El usuario hace clic en la lista desplegable "Materia". 
    - El sistema despliega la lista de materias registradas en el sistema.
    - El usuario selecciona la materia correspondiente.
    - El sistema carga el listado de alumnos matriculados en la materia seleccionada.
    - El usuario hace clic en la lista desplegable "Año". 
    - El sistema despliega la lista de los años lectivos.
    - El usuario selecciona el año lectivo.
    - El sistema imprime el registro de asistencia actual.


