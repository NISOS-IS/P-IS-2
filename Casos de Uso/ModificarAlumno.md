### Modificar Alumno  
**ID:** 003  
**Breve descripcion:** Modificar datos del alumno.  
  
  **Actor principal:** Profesor.  
  **Actor secundario:** Alumno.
    
  **Precondiciones:**
1. El alumno debe existir en el sistema.  

**Flujo principal:**  
1. El caso de uso empieza cuando el profesor quiere modificar los datos de un alumno.
2. El profesor busca al alumno por DNI o apellido.
3. El profesor modifica los datos del alumno.

**Postcondiciones:**
- El sistema guarda los datos del alumno.

**Flujos alternativos:**  

2.a. Si el alumno no existe por DNI, muestra un mensaje de error.
2.b. Si el alumno no existe por Apellido, muestra un mensaje de error.
