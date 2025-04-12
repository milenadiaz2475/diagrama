Si bien no puedo crear imágenes o diagramas directamente, puedo describirte cómo crear un diagrama de casos de uso con los elementos necesarios. Puedes utilizar herramientas como Lucidchart, Draw.io, Visio, o incluso papel y lápiz. Aquí te dejo una guía paso a paso para que puedas dibujarlo tú mismo.

### Diagrama de Casos de Uso para un Sistema de Gestión de Eventos

**Actores:**
1. **Organizador**
2. **Participante**
3. **Administrador del Sistema**

**Casos de Uso:**
1. **Crear Evento**
   - Actor: Organizador
   - Descripción: El organizador crea un nuevo evento ingresando detalles como nombre, fecha, lugar, descripción, etc.

2. **Invitar Participantes**
   - Actor: Organizador
   - Descripción: El organizador envía invitaciones a los participantes registrados.

3. **Registrarse en Evento**
   - Actor: Participante
   - Descripción: Un participante se registra para asistir a un evento específico.

4. **Recibir Notificaciones**
   - Actor: Participante
   - Descripción: El participante recibe notificaciones sobre el evento (confirmación, recordatorios).

5. **Gestionar Eventos**
   - Actor: Administrador del Sistema
   - Descripción: El administrador gestiona la configuración del sistema, incluyendo eventos y usuarios.

6. **Generar Reportes**
   - Actor: Organizador
   - Descripción: El organizador genera reportes de asistencia y feedback post-evento.

### Esquema del Diagrama de Casos de Uso

A continuación, sigue este esquema textual para visualizar cómo debería organizarse:

```
                        +---------------------+
                        |   Administrador     |
                        +---------------------+
                                |              
                          ---------------
                          | Gestionar Eventos|
                          ------------------
                                      
                               
+-------------------+          +-------------------+
|    Organizador    |----------|      Participante  |
+-------------------+          +-------------------+
          |                           |
          |                    --------------
    ---------------           | Registrarse en  |
    | Crear Evento |          |      Evento     |
    ---------------           --------------
          |
    -------------------
    | Invitar Participantes |
    -------------------
          |
    -------------------
    | Generar Reportes  |
    -------------------
   
```

### Leyenda
- **Los rectángulos** representan a los actores y casos de uso.
- **Las líneas** conectan los actores con los casos de uso que pueden realizar.

### Pasos para Dibujar
1. Dibuja un círculo o un óvalo en el centro e identifica el sistema (por ejemplo, "Sistema de Gestión de Eventos").
2. Coloca los actores (Organizador, Participante, Administrador) alrededor del círculo.
3. Dibuja líneas entre los actores y los casos de uso representados por rectángulos, indicando qué actor puede realizar cada acción.

Cuando completes esto, tendrás un diagrama visual que representa cómo interactúan los diferentes actores con el sistema. Si tienes alguna pregunta específica sobre el diagrama o necesitas más detalles sobre algún caso de uso, ¡házmelo saber!
