# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre: Ana
- Nombre: Lucia
- Nombre: Pedro
- Nombre: lina
- Nombre: Hugo

## 3. Requerimientos Funcionales

### RF-01 - [Registrar Tutoria]

#### Resumen
Permite a un profesor registrar una nueva tutoría indicando el tema, la fecha, la hora de inicio y el cupo máximo de estudiantes que puede atender, para que posteriormente los estudiantes puedan encontrarla y solicitar su inscripción.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
|codigoProfesor|	String|	Código que identifica al profesor que ofrece la tutoría|
|tema|String|	Tema o asignatura sobre la que trata la tutoría|
|fecha|Date|	Fecha en la que se realizará la tutoría|
|horaInicio|Time|Hora de inicio de la tutoría|
|cupoMaximo|	Integer|Cantidad máxima de estudiantes que podrán inscribirse|
#### Reglas o condiciones
- La fecha de la tutoría no puede ser anterior a la fecha actual.
- El cupo máximo debe ser un valor entre 1 y 10 estudiantes.
- El código del profesor debe corresponder a un profesor válido registrado en la Universidad.
- Todos los campos (tema, fecha, hora de inicio y cupo máximo) son obligatorios.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
|idTutoria|String|Identificador único asignado a la tutoría creada|
|mensaje|String|Mensaje de confirmación indicando que la tutoría fue creada correctamente, o mensaje de error indicando el motivo del rechazo|

#### Resultado esperado
Se crea un nuevo registro de tutoría en el sistema con un identificador único, quedando disponible para que los estudiantes puedan consultarla e inscribirse en ella. El profesor recibe la confirmación del registro exitoso.


### RF-02 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


### RF-03 - [inscribir tutoria]

#### Resumen
Permite a un estudiante inscribirse en una tutoría de su interés indicando su código estudiantil y el identificador de la tutoría, siempre que cumpla con las condiciones necesarias para completar la inscripción.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


### RF-04 - [Nombre del requerimiento]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


## 4. Gestión de Versiones

### Ramas utilizadas

### Proceso de integración

### Conflictos encontrados
