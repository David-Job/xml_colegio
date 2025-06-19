# UF2217 - Práctica 1: Fundamentos de XML y Validación

- David Job Jiménez Suárez
- 19 de junio de 2025

Ejercicios
---
---

1. **Diseñar un documento XML** que contenga información sobre **alumnos**, **profesores** y **asignaturas**, agrupadas de forma jerárquica.
2. **Diseñar un esquema XSD** que valide dicho XML, cumpliendo los siguientes requisitos:
	- El código de asignatura debe tener formato: 3 letras + 3 cifras (ej. `MAT001`)
	- El expediente del alumno debe tener formato: 1 letra mayúscula + 3 cifras (ej. `A001`)
	- Incluir tipos restringidos (`enumeration`) para campos como nivel educativo o departamento.
	- Incluye elementos con atributos y al menos cuatro campos de texto por entidad.
3. **Diseñar una hoja de estilo XSL** que transforme el XML en una página **HTML** formateada con **Bootstrap**, mostrando al menos los datos de los alumnos en una tabla.
4. *(Opcional)* **Preparar un CRUD en HTML/JS/PHP** sobre la subentidad `alumno`, que lea y escriba en el XML de forma persistente (si el entorno lo permite).

