# ADS
Integrantes:
- Hernandez Flores Aldo Yael
- Mompin Beristain Ana Fernanda
- Sanchez Tellez Ethan Abraham
- Zainos Ascencio Ivan

## Descripción de proyecto
Creación de una fracción de un Sistema Administrativo Escolar (SAES). Algunas de las características de la versión completa son:
- Administración de cuentas estudiantiles, docentes y adminstrativas
- Consulta de calificaciones
- Registro y consulta de datos personales, medicos y deportivos
- Creación y seguimiento de trámites y citas
### Para alumnos
- Consulta de historial académico (Kardex)
- Consulta de materias irregulares
- Consulta de horario de semestre actual
- Consulta de calificaciones de semestre actual
- Inscripción a materias
- Inscripción y consulta de calificaciones de ETS
- Inscripcion y consulta de calificaciones de Saberes Previamente Adquiridos
- Consulta y evaluación de tutores
- Evalueación de profesores
- Consulta de todas las materias, semestre al que corresponden y cupo disponible
- Consulta de materias por carrera y semestre, así como sus características (creditos, horas de estudio, etc.)
- Consulta de fechas relevantes (inicio de curso, dias inhabiles, periodos vacionales)
- Consulta de calendario de exámenes extraordinarios por carrera, especialidad y semestre
- Consulta de calendario de ETS por carrera, especialidad y semestre
- Pestaña no funcional de "Equivalencias"
- Consulta de manual y reglamento de estudiantes
- Función de recuperar contraseña
### Para profesores y administrativos
Se carece de información de esta parte del sistema, sería ideal que se obtuviera una captura de pantalla detallada de estos sistemas
Por esta misma razón no se puede determinar que características son exclusivas para la vista de alumno y cuales se comparten entre los tipos de usuario


## Objetivo del proyecto
Dado que se cuenta con recursos limitados, se limitará el alcance del proyecto a solo una fracción del sistema actualmente implementado.
El producto a entregar al final del curso cumplirá con las siguientes características:
- El sistema debe poder soporta una base de usuarios de al menos el tamaño de estudiantes en la UPIIT
- El sistema debe usar la paleta de colores del IPN
- El sistema se creará por medio de una aplicación web
- Las actualizaciones a la bases de datos deberán de ser rápidas
- El sistema deberá funcionar en dispositivos de baja capacidad
- El sistema será tendrá mejores medidas de seguridad que el sistema actualmente implementado

Y será capaz de realizar las siguientes funciones:
- Manejo de vistas distintas para 3 tipos de usuarios: estudiantes, docentes, y administrativos.
- Creación, modificación y eliminación de cuentas para cada tipo de usuario, así como de los datos contenidos dentro de cada cuenta
- Registro y consulta de carreras, así como datos pertinentes a cada carrera (nombre, área, semestre, etc.)
- Creación de grupos por parte de los administrativos.
  Para la creación de un grupo, este debe contener:
  - Un docente
  - La materia que se enseñará
  - El periodo de duración. Al terminar este periodo, los grupos se eliminarán automaticamente
  Para el registro de alumnos a un grupo, estos deben de poder ser eliminados y añadidos tanto al momento de crear un grupo como después de su creación
- Asignación de calificaciones por parte de un docente a todos los estudiantes dentro de un grupo
  Al asignar los cambios a las calificaciones de un grupo, estos se verán reflejados en el historial de cada alumno
  **Sería buena idea notificar al estudiante de cambios en calificaciones
- Consulta de calificaciones por parte del alumno, tanto a las calificaciones que tiene dentro del grupo como de todo su historial académico
- La vista del sistema se puede adaptar a pantallas de distintos tamaños

Si a lo largo del desarrollo se dermina que se puede expandir el alcance del proyecto, este se ajustará de acuerdo a lo posible. De igual manera si se determina que se debe reducir la escala del proyecto puede que no se la versión entregada no cumpla con todas las funciones y características indicadas arriba.
