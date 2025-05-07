 

## 1. Introducción
Este documento presenta la evaluación de los requerimientos para el software de gestión de eventos. Se han realizado prototipos de la interfaz y se han desarrollado casos de prueba para validar la funcionalidad del sistema. La evaluación se ha llevado a cabo a través de técnicas de validación de requisitos que permiten asegurar que el sistema cumpla con las expectativas de los usuarios y los objetivos del negocio.

## 2. Alcance
El alcance de este documento incluye:
- La validación de cuatro historias de usuario seleccionadas.
- La creación de prototipos de cada interfaz.
- La elaboración de casos de prueba asociados a cada historia de usuario/prototipo.

## 3. Lista de Requerimientos
Las siguientes historias de usuario han sido seleccionadas para la validación:

1. **Historia de Usuario 1:** Como organizador, quiero crear un nuevo evento para gestionar su información.
2. **Historia de Usuario 2:** Como asistente, deseo registrarme en un evento para poder participar.
3. **Historia de Usuario 3:** Como organizador, quiero enviar invitaciones a los asistentes para promover el evento.
4. **Historia de Usuario 4:** Como asistente, quiero recibir notificaciones sobre próximos eventos para no perderme ninguno.

## 4. Prototipos y Casos de Prueba

### 4.1 Prototipo 1: Creación de Evento
*(Incluir imagen del prototipo aquí)*

#### Caso de Prueba 1
- **Objetivo del caso de prueba:** Validar la creación de un nuevo evento.
- **Identificador:** CP-001
- **Nombre del requerimiento asociado:** Crear un nuevo evento.
- **Precondiciones:** El organizador ha iniciado sesión en el sistema.
- **Pasos:**
  1. Navegar a la sección "Crear Evento".
     - **Resultado esperado:** Se muestra el formulario de creación de evento.
  2. Completar todos los campos obligatorios.
     - **Resultado esperado:** Los campos se completan sin errores.
  3. Hacer clic en el botón "Guardar".
     - **Resultado esperado:** Se muestra un mensaje de confirmación y el nuevo evento aparece en la lista de eventos.

### 4.2 Prototipo 2: Registro en Evento
*(Incluir imagen del prototipo aquí)*

#### Caso de Prueba 2
- **Objetivo del caso de prueba:** Validar el registro de un asistente en un evento.
- **Identificador:** CP-002
- **Nombre del requerimiento asociado:** Registrarse en un evento.
- **Precondiciones:** El asistente tiene acceso a la página del evento.
- **Pasos:**
  1. Hacer clic en el botón "Registrarse".
     - **Resultado esperado:** Aparece un formulario de registro.
  2. Completar el formulario de registro.
     - **Resultado esperado:** Todos los campos se completan correctamente.
  3. Hacer clic en "Enviar".
     - **Resultado esperado:** Se muestra un mensaje de confirmación y el asistente está registrado en el evento.

### 4.3 Prototipo 3: Envío de Invitaciones
*(Incluir imagen del prototipo aquí)*

#### Caso de Prueba 3
- **Objetivo del caso de prueba:** Validar el envío de invitaciones a los asistentes.
- **Identificador:** CP-003
- **Nombre del requerimiento asociado:** Enviar invitaciones.
- **Precondiciones:** El organizador ha creado un evento.
- **Pasos:**
  1. Acceder a la sección "Invitar Asistentes".
     - **Resultado esperado:** Se muestra la lista de invitados.
  2. Seleccionar los contactos de la lista.
     - **Resultado esperado:** Los contactos seleccionados aparecen resaltados.
  3. Hacer clic en "Enviar invitaciones".
     - **Resultado esperado:** Se muestra un mensaje de confirmación de envío.

### 4.4 Prototipo 4: Notificaciones de Eventos
*(Incluir imagen del prototipo aquí)*

#### Caso de Prueba 4
- **Objetivo del caso de prueba:** Validar la recepción de notificaciones sobre eventos.
- **Identificador:** CP-004
- **Nombre del requerimiento asociado
