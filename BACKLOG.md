# Backlog funcional - Gestión Estética

## Epic
- [EPIC] Gestión Estética - Backlog funcional

## Sprint 1 — Fundamentos y primera reserva (22/10–04/11)
- [ ] [P0][BASE] Definir los módulos y la lógica de negocio central de reservas, pagos, clientes y cuponeras.
- [ ] [P0][BASE] Definir estados, transiciones y reglas de reservas, retenciones, pagos y sesiones de cuponera.
- [ ] [P0][BASE] Diseñar el esquema inicial de PostgreSQL, restricciones y migraciones.
- [ ] [P0][BASE] Crear la estructura modular del backend Spring Boot y sus convenciones de API, validación y errores.
- [ ] [P0][BASE] Crear la estructura del frontend React, navegación y diseño móvil primero.
- [ ] [P0][BASE] Configurar repositorio, ramas, revisión de PR, integración continua y ambientes de desarrollo y prueba.
- [ ] [P0][BASE] Preparar datos de prueba y estructura de pruebas unitarias e integración.
- [ ] [P1][N1][CU19] Administrar servicios.
- [ ] [P1][N1][CU20] Configurar disponibilidad de la agenda.
- [ ] [P1][N4][CU03] Autenticarse.
- [ ] [P1][N4][CU04] Registrarse como cliente.
- [ ] [P1][N4][CU06] Administrar usuarios y roles.
- [ ] [P1][N1][CU01] Consultar servicios y disponibilidad.
- [ ] [P1][N1][CU02] Solicitar una reserva.
- [ ] [QA] Probar el recorrido inicial y registrar evidencias vinculadas a los CU implementados.

## Sprint 2 — Confirmación y cobros (05/11–18/11)
- [ ] [P1][N2][CU21] Configurar condiciones de pago.
- [ ] [P1][N1][CU43] Retener temporalmente un horario.
- [ ] [P1][N1][CU44] Liberar un horario vencido.
- [ ] [P1][N1][CU46] Confirmar una reserva.
- [ ] [P1][N2][INT] Configurar y probar Mercado Pago en su entorno de pruebas.
- [ ] [P1][N2][CU11] Realizar un pago en línea.
- [ ] [P1][N2][CU45] Procesar la confirmación de un pago en línea.
- [ ] [P1][N2][INT] Preparar el almacenamiento y acceso restringido a comprobantes.
- [ ] [P1][N2][CU12] Presentar un comprobante de transferencia.
- [ ] [P1][N2][CU23] Validar una transferencia.
- [ ] [QA] Probar vencimientos, pagos duplicados, confirmaciones repetidas y errores de integración.
- [ ] [DOC] Actualizar reglas de pago, decisiones y contratos de integración.

## Sprint 3 — Gestión de reservas y pagos administrativos (19/11–02/12)
- [ ] [P1][N1][CU13] Consultar reservas y pagos propios.
- [ ] [P1][N1][CU14] Cancelar una reserva propia.
- [ ] [P1][N1][CU15] Reprogramar una reserva propia.
- [ ] [P1][N4][CU28] Consultar la agenda.
- [ ] [P1][N1][CU29] Registrar administrativamente una reserva.
- [ ] [P1][N1][CU30] Cancelar administrativamente una reserva.
- [ ] [P1][N1][CU31] Reprogramar administrativamente una reserva.
- [ ] [P1][N2][CU24] Aprobar o rechazar una reserva con pago en efectivo.
- [ ] [QA] Probar permisos por rol, conflictos de horarios y cambios de estado de las reservas.
- [ ] [DOC] Actualizar procedimientos de operación administrativa.

## Sprint 4 — Cuponeras e incidencias (03/12–16/12)
- [ ] [P1][N3][CU22] Administrar tipos de packs y cuponeras.
- [ ] [P1][N3][CU16] Comprar una cuponera para uso propio o regalo.
- [ ] [P1][N3][CU48] Emitir una cuponera por compra confirmada.
- [ ] [P1][N3][CU26] Registrar administrativamente una cuponera.
- [ ] [P1][N3][CU17] Consultar saldo e historial de una cuponera propia.
- [ ] [P1][N3][CU47] Registrar un movimiento de cuponera.
- [ ] [P1][N3][CU18] Reservar utilizando una cuponera.
- [ ] [P1][N3][CU27] Ajustar administrativamente el saldo de una cuponera.
- [ ] [P1][N2][CU25] Gestionar incidencias de pagos fuera de plazo.
- [ ] [QA] Probar saldos, sesiones reservadas y utilizadas, ajustes, cancelaciones y operaciones simultáneas.
- [ ] [DOC] Documentar las reglas definitivas de consumo y restitución de sesiones.

## Sprint 5 — Fichas e información del cliente (02/01–15/01)
- [ ] [P1][N4][CU07] Recuperar el acceso.
- [ ] [P1][N4][CU08] Actualizar datos personales propios.
- [ ] [P2][N8][CU09] Completar la ficha previa propia.
- [ ] [P2][N9][CU10] Completar la ficha de atención de un cliente.
- [ ] [P2][N9][CU32] Registrar el resultado de una atención.
- [ ] [P2][N9][CU33] Consultar la ficha integral de un cliente.
- [ ] [P2][N9][CU34] Consultar historial de tratamientos propio.
- [ ] [P2][N5][CU36] Administrar información frecuente.
- [ ] [P2][N9][DATOS] Decidir y preparar la carga inicial de fichas existentes, si Leniza confirma que estará dentro del alcance.
- [ ] [QA] Probar privacidad, acceso por rol y actualización del historial sin pérdida de datos.

## Sprint 6 — WhatsApp y asistencia automatizada (16/01–29/01)
- [ ] [P2][N5][INT] Configurar WhatsApp Cloud API y versionar los flujos de n8n.
- [ ] [P1][N4][CU05] Registrarse como cliente mediante WhatsApp.
- [ ] [P2][N5][CU35] Consultar información frecuente.
- [ ] [P2][N5][CU37] Obtener orientación inicial sobre tratamientos.
- [ ] [P2][N5][CU38] Solicitar atención personalizada.
- [ ] [P1][N1][CU49] Enviar una notificación operativa.
- [ ] [P2][N5][INT] Definir respuestas de respaldo y derivación humana cuando una automatización no pueda resolver una consulta.
- [ ] [QA] Probar reintentos, fallas de WhatsApp/n8n y coherencia de datos entre web y WhatsApp.
- [ ] [DOC] Documentar los flujos y cómo desactivarlos o intervenirlos ante una incidencia.

## Sprint 7 — Seguimiento e integración final (30/01–12/02)
- [ ] [P2][N5][CU39] Gestionar una solicitud de atención personalizada.
- [ ] [P3][N6][CU40] Consultar indicadores del negocio.
- [ ] [P3][N6][CU41] Consultar reportes detallados.
- [ ] [P4][N7][CU42] Gestionar seguimiento de clientes y recordatorios.
- [ ] [P2][N8][CU50] Solicitar el completado de la ficha previa tras la primera reserva confirmada.
- [ ] [QA] Ejecutar pruebas integrales de reservas, tres modalidades de pago, cuponeras, fichas y WhatsApp.
- [ ] [QA] Ejecutar pruebas de aceptación con Leniza y registrar correcciones como nuevas issues.
- [ ] [QA] Revisar usabilidad desde teléfono, permisos y requerimientos no funcionales.
- [ ] [DOC] Completar manual de usuario, documentación técnica y evidencias de prueba.
- [ ] [ENTREGA] Preparar despliegue, capacitación y cierre del proyecto.

## Checklist base para todas las issues
- [ ] Regla de negocio
- [ ] Base de datos
- [ ] API
- [ ] Interfaz/canal
- [ ] Permisos
- [ ] Pruebas
- [ ] Criterio de aceptación

## Criterio global
La tarea se considera cerrada solo si:
- la regla de negocio quedó validada,
- la base de datos quedó modelada o ajustada,
- la API quedó implementada y validada,
- la interfaz/canal quedó integrada,
- los permisos quedaron definidos,
- la prueba quedó documentada, y
- el criterio de aceptación fue verificado.
