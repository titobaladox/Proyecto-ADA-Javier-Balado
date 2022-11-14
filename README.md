# Proyecto ADA Javier-Balado
Proyecto para la materia ADA Cerp del Este

# Software Bedelias Cerp del Este
[![images.png](https://i.postimg.cc/q70r0tkR/images.png)](https://postimg.cc/v4PktZxF)


Este proyecto se va a centrar en crear profesores y asignarles materias a los mismos.

El sistema debe poder cargar a los profesores, asignarles sus horas de trabajo, asignarles grupos y asignarles una o más materias.

### Requerimientos Funcionales:

  -Dar alta, baja y modificación a los docentes
  
  -Dar alta, baja y modificación a los cursos
  
  -Dar alta, baja y modificación a las materias
  
  -El sistema debe contar con usuarios normales y administradores
  
  -Los administradores deben poder crear otros administradores y usuarios
  
  -Los administradores deben poder modificar todo tipo de usuarios
  
  -Los usuarios deben poder ver sus datos, guros y horas asignadas
  
  -Los usuarios deben poder solicitar la baja de las horas asignadas
  
  -La interfaz debe contar con un LogIn que otorgue acceso al sistema
  
  
### Requerimientos no Funcionales:

  -El sistema debe contar con una base de datos con capacidad para almacenar al menos 200 usuarios
  
  -El sistema debe trabajar de forma local y remota
  
  -El sistema permite dividir los horarios por turnos (Matutino,Vespertino,Nocturno)
  
  -El sistema tendrá soporte para dispositivos móviles
  
  -El sistema pedirá confimación al momento de realizar cualquier cambio
  
  -El sistema guardará un respaldo de los datos borrados durante un mes
  
  
  ## Modalidad de trabajo
  
  La modalidad de trabajo que se seleccionó para este proyecto es el **Modelo Iterativo Incremental.**
  
  [![iteracion.png](https://i.postimg.cc/Y28TLntt/iteracion.png)](https://postimg.cc/kD6TkyVH)
  
  #### ¿Qué es?
  
El incremental es un modelo de tipo evolutivo que está basado en
varios ciclos Cascada realimentados aplicados repetidamente, con
una filosofía iterativa.
El modelo incremental es útil sobre todo cuando el personal
necesario para una implementación completa no esta disponible.

En este caso en particular el equipo de trabajo es unipersonal por lo cuál crear una implementación completa requeriría mucho tiempo
antes de que el cliente pueda ver el producto, además este modelo permite un contacto directo con el cliente por si surgen nuevos requerimientos
durante el transcurso de la creación del software.

#### Ventajas:

-Se reduce el tiempo de desarrollo inicial, ya que se implementa la funcionalidad parcial.


-Proporciona todas las ventajas del modelo en cascada realimentado, reduciendo sus desventajas sólo al ámbito de cada incremento.

-Los modelos iterativos e incrementales disminuyen riesgos ya
que estos modelos se basan en la retroalimentación sobre los
avances.


-Resulta más sencillo acomodar cambios al acotar el tamaño
de los incrementos.

#### Desventajas:

-El modelo Incremental no es recomendable para
casos de sistemas de tiempo real, de alto nivel de
seguridad, de procesamiento distribuido, y/o de alto
índice de riesgos.

-Requiere de mucha planificación, tanto administrativa
como técnica.

-Requiere de metas claras para conocer el estado del
proyecto.

## Conclusión

Para realizar el proyecto con esta modalidad de trabajo se requieren objetivos bien definidos, una comunicación directa con el cliente/usuario. Siempre teniendo en cuenta que el conocimiento en cuanto a desarrollo de software por parte de este puede ser **nula o casi nula**.

Debemos poder concretar entra ambas partes entregas con pequeñas metas (*requerimientos*) alcanzables para las distintas instancias.

Se ha concretado el plazo máximo para la entraga final en la fecha 28/02/2023 y anteriormente se deben entregar un minimo de 5 adelantos del proyecto.

[![direccion-de-proyectos-control-de-proyectos.jpg](https://i.postimg.cc/Hx7ZvgKg/direccion-de-proyectos-control-de-proyectos.jpg)](https://postimg.cc/JDM5t9M6)


# Base de Datos del Sistema

[![danysoft-webinar-BBDDERStudio-banner-spain.jpg](https://i.postimg.cc/66PbZzHZ/danysoft-webinar-BBDDERStudio-banner-spain.jpg)](https://postimg.cc/MXyY20JZ)

**De los docentes se conoce:**

-Cédula

-Nombre y Apellido

-Dirección

-Teléfono

**De los administradores se conoce:**

-Cédula

-Nombre y Apellido

-Dirección

-Teléfono

**De los grupos se conoce:**

-Identificador

-Turno

**De las materias se conoce:**

-Identificador

-Horario

-Nombre

**Se sabe que:** Un profesor puede dictar una o más materias, a su vez una materia puede ser dictada por un solo profesor. Un grupo tiene muchas materias y las    materias pueden estar en más de un grupo. Los administradores pueden crear grupos, materias y profesores pero también, supervisar el dictado de las materias.

### MER

[![MER.png](https://i.postimg.cc/brwCh875/MER.png)](https://postimg.cc/9RstP3FP)

### TABLAS

[![Screenshot-7.png](https://i.postimg.cc/MpsLXchP/Screenshot-7.png)](https://postimg.cc/w1m2GBxL)

[![Screenshot-2.png](https://i.postimg.cc/v83fJW9N/Screenshot-2.png)](https://postimg.cc/QVKF5KfQ)

[![Screenshot-1.png](https://i.postimg.cc/25D1b6hW/Screenshot-1.png)](https://postimg.cc/QFf8vj6N)
