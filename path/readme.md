# Programa de referidos
## Descripción
En función de incrementar la difusión y generar un compromiso entre el cliente y empresa, se propone un programa de referidos para incentivar las promoción del servicio por parte de los clientes a potenciales clientes.

## Modulos 
### Sistema de referidos
El modulo core del sistema, se encarga de orquestar el flujo del envío de invitaciones y su seguimiento a través de un sistema de tracking. Permite la generación de reportes para premiar a los usuarios.
### Invitaciones
El api de invitaciones permite crear invitaciones, enviar invitaciones, asignar promotores y referenciar a los invitados.
### Premios
El api de premios permite crear premios, implementar condiciones de ganancia y asignar los premios a los usuarios.
### Sistema de Tracking
El sistema de tracking tiene el rol de actualizar el estado de la invitaciones durante el proceso de referencia de un invitado.
### Generador de códigos de referencia
Este modulo se encarga de generar los códigos de referencia para la invitaciones.

## Hitos
### Envío de Invitaciones
- [ ] Invitaciones API.
- [ ] Agregar tab del sistema de referidos (UI).
- [ ] Crear el formulario de invitación (UI).
- [ ] Envío de correos de invitación.
- [ ] Añadir los códigos de referencias en las invitaciones.

### Generación de códigos de referencia
- [ ] Diseñar e implementar algoritmo de generación de códigos.
- [ ] Permitir crear códigos para las invitaciones.

### Registro de referidos
- [ ] Añadir cajón de texto para escribir el cupón en el formulario de registro (UI).
- [ ] Asociar el referido con la invitación a través del código.

### Seguimiento de invitaciones
- [ ] Crear la tabla de invitados.
- [ ] Tracking interface.
- [ ] Actualizar el estado de la invitación.
- [ ] Crear el premio cuando el estado de la invitación sea "subscrito".
- [ ] Agregar el panel de acciones en los tiles de cada invitación.

### Sistema de premios
- [ ] Api de premios.
- [ ] Generar un reporte con los advocer con premios. 
