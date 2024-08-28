### Actividades

* Tarea, Assignment
* Disponibilidad, Tipos de entrega, Calificación.
* Availability, Submission types, Grade
* Asistencia, Attendance
* Crear preguntas
* Consulta
* Cuestionario

Cambiar rol a ... me sirve para chequear otro rol, p.ej. estudiante.

#### Crear Preguntas

##### Preguntas de opción múltiple

Administración del curso > Banco de preguntas

* Categorías: 
	* Añadir categoría: 
		* Categoría padre, 
		* nombre de la categoría (*genera una estructura de temas y subtemas*).
* Crear una nueva pregunta: 
	* Tipo; 
	* Categoría, 
	* nombre (*código interno*), 
	* enunciado -- imagen: *La descripción es importante para los lectores de pantalla*
	* Una o varias respuestas, barajar respuestas, numeración.
	* Elección 1: correcta, calificación 100%; elección 2: distractor, calificación 0%; etc.
	* Guardar cambios

##### Preguntas masivas

Archivo de texto con preguntas pertenecientes a una categoría determinada.

1. Hoja de cálculo

|A|B|C| 
|-|-|-| 
|::01.::|Enunciado pregunta 1|{| 
|=|Respuesta correcta|| 
|~|Distractor|| 
|~|Distractor|| 
|~|Distractor|| 
|}||| 
|||| 
|::02.::|Enunciado pregunta 2|{| 
|=|Respuesta correcta|| 
|~|Distractor|| 
|~|Distractor|| 
|~|Distractor|| 
|}|||

2. Copiar y pegar en editor de texto, codificación UTF-8

```
::01.:: 	Enunciado pregunta 1 	{
= 	Respuesta correcta 	
~ 	Distractor 	
~ 	Distractor 	
~ 	Distractor 	
} 		
		
::02.:: 	Enunciado pregunta 2 	{
= 	Respuesta correcta 	
~ 	Distractor 	
~ 	Distractor 	
~ 	Distractor 	
} 	
```

Guardar el archivo.

3. Banco de preguntas > Importar, formato GIFT

#### Añadir Cuestionario

**Configurar Administración del sitio > Calificaciones** 
Ver archivo Calificaciones

**Agregar categorías: Calificaciones > Agregar categoría**  
Ver archivo Calificaciones

**Añadir cuestionario** 
Activar edición > Añadir una actividad o recurso > Cuestionario

* Ajustes
* Nombre, descripción
* Temporalización
* Categoría: una de las agregadas en Calificaciones > Agregar categoría 
* Opciones de revisión: dejar solamente *puntos*.
* Restricciones extra sobre los intentos (**medidas de seguridad**):
  * clave de acceso;
  * dirección de red;
  * *Ventana emergente a pantalla completa con alguna seguridad Javascript*;
  * cuestionario oculto hasta la fecha del examen.
* Guardar cambios

##### Editar cuestionario

* Reordenar las preguntas al azar
* Agregar preguntas: simple, banco, aleatoria (de banco)
* Cantidades intermedias por encima de 10 se agregan secuencialmente, p.ej. 20+5
* Previsualización

#### Consulta 

Pregunta o consigna con opciones; *no califica*.

Título, descripción, disponibilidad.

#### Taller

Revisión por pares, califica por el envío y por los otros estudiantes. 
Nombre, la descripción , mostrar en la página 
Ajustes de calificación: pondera la nota, por rúbrica. 
[Rubistar](http://rubistar.4teachers.org/index.php?&skin=es&lang=es&) en [4Teachers](http://www.4teachers.org/tools/?lang=EN)
Parámetros de los envíos: debe contener las consignas
Configuración de la evaluación: instrucciones para el evaluador
Comentario: conclusión de la actividad.
Calificación: a partir de 0 (más alta)
Fases: envíos, evaluación, calificación, cierre.
