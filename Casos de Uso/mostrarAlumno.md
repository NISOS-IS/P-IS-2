
### Motrar Alumno
**ID:** 006   
**Breve Descripción:** El sistema muestra la información de uno o varios alumnos.

**Actor principal:** Profesor   
**Actor secundario:** Alumno   

**Precondiciones:**
1. El alumno debe existir en el sistema.
2. El profesor debe indicar el DNI, Apellidos o Equipo pertenecientes al alumno.

**Flujo principal:**
1. El caso de uso comienza cuando el sistema necesita mostrar un alumno o varios alumnos.
2. El profesor indica el DNI, Apellidos o Equipo pertenecientes al alumno que desea ver.
3. El sistema recoge los datos del alumnos o alumnos.

**Postcondiciones:**
+ El sistema muestra por pantalla los datos del alumno o alumnos.

**Flujos alternativos:**

3.a. Si el DNI no existe, muestra un mensaje de error.   
3.b. Si el apellido no existe, muestra un mensaje de error.   
3.c. Si el equipo no existe, muestra un mensaje de error.



