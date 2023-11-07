# Especificación de requisitos de software

## Enunciado del problema

La Escuela de Negocios enfrenta desafíos en el seguimiento manual de la asistencia de los estudiantes, lo que consume tiempo y es propenso a errores. Esta situación afecta negativamente la eficiencia y precisión en el monitoreo del comportamiento y la asistencia de los alumnos. Por lo tanto, es esencial desarrollar un software que automatice este proceso y brinde una solución eficiente y segura para el registro y seguimiento de asistencias.


## Clientes potenciales
 
1. Los usuarios potenciales del software incluyen:
    - Preceptores: Quienes serán responsables de registrar la asistencia de los estudiantes, gestionar la información de los alumnos y generar informes.
    - Alumnos: Los beneficiarios indirectos, ya que el sistema mejorará la precisión en el registro de asistencias y, por lo tanto, su seguimiento académico.


## Solución propuesta 

1. El Sistema de Asistencias para la Preceptoría del Instituto es una aplicación web que permitirá a los preceptores:
    - Crear cuentas y acceder al sistema con credenciales únicas.
    - Registrar la asistencia diaria de los estudiantes de manera eficiente.
    - Agregar, editar y eliminar información de los estudiantes, incluyendo detalles de contacto y datos personales.
    - Registrar ausencias y ausencias justificadas de los estudiantes.
    - Agregar y gestionar información sobre las materias impartidas.
    - Generar informes detallados sobre la asistencia de los estudiantes en un período específico.
    - Proporcionar una interfaz de usuario intuitiva y fácil de usar.


## Requisitos

1. Requisitos Esenciales:
    - Registro de preceptores con credenciales únicas.
    - Registro de asistencia diaria de estudiantes, incluyendo ausencias y ausencias justificadas.
    - Gestión de información de estudiantes, incluyendo edición y eliminación.
    - Registro y gestión de información de materias.
    - Generación de informes de asistencia.
    - Interfaz de usuario intuitiva.

2. Requisitos No Esenciales:
    - Funcionalidad de recuperación de contraseña.
    - Funcionalidad de exportación de informes en diferentes formatos.
    - Integración con otros sistemas académicos existentes en el instituto.

 
## Arquitectura de software

1. El Sistema de Asistencias para la Preceptoría del Instituto será una aplicación web basada en tecnologías estándar de la web y seguirá una arquitectura cliente-servidor. Se utilizará PHP para el desarrollo del backend, HTML para la estructura, CSS para el diseño y JavaScript para mejorar la interactividad del frontend. MySQL se empleará como el sistema de gestión de base de datos, y phpMyAdmin facilitará la administración visual de la base de datos MySQL.
