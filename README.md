
### Portada

**Título del Documento**: Documentación de Requisitos del Sistema de Gestión de Eventos  
**Nombre del Proyecto**: Sistema de Gestión de Eventos  
**Versión**: 1.0  
**Fecha**: [Fecha Actual]  
**Autor(es)**: [Nombre(s) del Autor(es)]  

---

### Introducción

En la actualidad, la organización y gestión de eventos se ha vuelto una actividad compleja que requiere una planificación meticulosa y un seguimiento constante. Este documento describe los requisitos para el desarrollo de un Sistema de Gestión de Eventos, el cual tiene como finalidad facilitar la creación, planificación, seguimiento y evaluación de eventos. Con este sistema, se pretende mejorar la eficiencia y efectividad en la gestión de eventos, permitiendo a los organizadores tener un control centralizado y accesible de toda la información relevante.

---

### Objetivo

El objetivo de este documento es proporcionar una descripción clara y detallada de los requisitos del sistema de gestión de eventos. Esto incluye la identificación de las funcionalidades necesarias tanto para los organizadores como para los participantes, así como los parámetros no funcionales que garantizarán un rendimiento óptimo del sistema. 

---

### Alcance

El Sistema de Gestión de Eventos abarcará las siguientes funcionalidades:

- Creación y gestión de eventos (fecha, lugar, descripción, etc.)
- Registro de participantes
- Gestión de inscripciones
- Envío de notificaciones (confirmaciones, recordatorios, etc.)
- Generación de reportes sobre asistencia y feedback

Queda fuera del alcance del proyecto la gestión de eventos de terceros y la realización de pagos online.

---

### Herramienta de Captura de Requisitos

Para capturar y estructurar los requisitos de este proyecto, se opta por utilizar **Diagrama de Casos de Uso**. Esta herramienta permite visualizar las interacciones entre los actores involucrados (organizadores, participantes, administradores) y el sistema, facilitando la comprensión de los requisitos funcionales.

---

### Requisitos Funcionales

1. **Crear Eventos**
   - **Descripción**: Los organizadores podrán crear eventos, especificando fecha, hora, lugar, descripción y límite de participantes.
   - **Actor**: Organizador.
   - **Precondición**: El organizador debe estar autenticado.
   - **Postcondiciones**: El evento queda registrado en el sistema y es visible para los participantes.

2. **Registrar Participantes**
   - **Descripción**: Los participantes podrán registrarse para asistir a un evento.
   - **Actor**: Participante.
   - **Precondición**: El evento debe estar disponible para inscripción.
   - **Postcondiciones**: El participante queda registrado y recibe un correo de confirmación.

3. **Enviar Notificaciones**
   - **Descripción**: El sistema enviará notificaciones a los participantes sobre la confirmación de su inscripción y recordatorios del evento.
   - **Actor**: Sistema.
   - **Postcondiciones**: Los participantes reciben correos electrónicos con la información relevante.

4. **Generar Reportes**
   - **Descripción**: Los organizadores podrán generar reportes sobre el número de participantes registrados y comentarios recibidos.
   - **Actor**: Organizador.
   - **Postcondiciones**: Se crea un reporte descargable en formato PDF.

---

### Requisitos No Funcionales

1. **Rendimiento**
   - **Descripción**: El sistema deberá ser capaz de manejar hasta 1000 inscripciones simultáneas sin degradación en el rendimiento.

2. **Seguridad**
   - **Descripción**: La información de los participantes deberá ser almacenada de manera segura, con acceso restringido basado en roles.

3. **Usabilidad**
   - **Descripción**: La interfaz del sistema deberá ser intuitiva y fácil de usar, permitiendo a los organizadores y participantes navegar sin dificultad.

4. **Escalabilidad**
   - **Descripción**: El sistema deberá ser escalable para permitir la adición de nuevas funcionalidades en el futuro, como la gestión de pagos.

---

### Conclusión

Este documento establece una base sólida para el desarrollo del Sistema de Gestión de Eventos, asegurando que todos los requisitos estén bien definidos y alineados con las expectativas de los stakeholders. La implementación de este sistema facilitará la organización de eventos y mejorará la experiencia tanto para los organizadores como para los participantes.


