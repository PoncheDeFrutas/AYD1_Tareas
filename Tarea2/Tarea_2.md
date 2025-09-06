# Tarea #2 – Identificación de Requerimientos

**Curso:** Análisis y Diseño de Sistemas 1  
**Universidad:** Universidad de San Carlos de Guatemala  
**Facultad:** Ingeniería en Ciencias y Sistemas  


## Introducción

El comercio electrónico se ha consolidado como uno de los pilares más importantes dentro del desarrollo de software moderno. La creciente demanda de plataformas de ventas en línea como Amazon, eBay o Walmart exige que los futuros ingenieros puedan analizar y diseñar sistemas robustos, escalables y confiables. Para que dichos sistemas cumplan con las expectativas de los usuarios y con los estándares de calidad, resulta indispensable identificar y documentar los **requerimientos funcionales** y **no funcionales**.

Esta tarea tiene como finalidad aplicar los conceptos aprendidos en el curso de Análisis y Diseño de Sistemas, plasmando de manera ordenada los requerimientos, actores y casos de uso que conforman un sistema de comercio electrónico. El análisis adecuado permitirá evidenciar la relevancia de estos elementos en la obtención de un producto final eficiente y exitoso.

## Actores Identificados

- **Visitante/Cliente**: Usuario que navega sin necesidad de registro, con acceso a la búsqueda y visualización de productos.  
- **Usuario registrado**: Cliente con cuenta creada que puede gestionar su información, historial de pedidos y preferencias.  
- **Administrador**: Encargado de gestionar el catálogo de productos, controlar inventario, supervisar pedidos y generar reportes.  
- **Vendedor (Marketplace)**: Publica y administra productos propios, gestionando ventas asociadas a su cuenta.  
- **Pasarela de pago**: Servicio externo que autoriza y procesa pagos electrónicos.  
- **Banco emisor**: Institución financiera que valida la disponibilidad de fondos y confirma las transacciones.  
- **Servicio de envío**: Transportista encargado de la logística de entrega y actualización de estados de envío.  
- **Soporte al cliente**: Área que atiende dudas, reclamos, devoluciones y solicitudes de los usuarios.  
- **Sistema antifraude**: Servicio encargado de detectar y prevenir operaciones sospechosas.  
- **Servicio de notificaciones**: Plataforma que envía correos electrónicos, SMS o notificaciones push.  
- **ERP/Inventario interno**: Sistema de back-office encargado de sincronizar inventarios y contabilizar operaciones.  

## Requerimientos Funcionales

1. **Gestión de productos**: Crear, modificar y eliminar productos, categorías y variantes.  
2. **Visualización de catálogo**: Mostrar productos con filtros avanzados (categoría, precio, popularidad, stock).  
3. **Carrito de compras**: Agregar, modificar cantidades y eliminar artículos.  
4. **Aplicación de promociones y cupones**: Validación automática de descuentos.  
5. **Checkout seguro**: Proceso guiado con selección de dirección y método de pago.  
6. **Procesamiento de pagos**: Autorización y captura de transacciones a través de pasarelas seguras.  
7. **Confirmación de pedido**: Generación de número de orden, detalle de compra y notificación inmediata.  
8. **Historial de pedidos**: Consulta de compras previas y estados de entrega.  
9. **Seguimiento de envíos**: Integración con servicios de mensajería y actualización de tracking.  
10. **Gestión de devoluciones**: Solicitud y procesamiento de reembolsos o cambios.  
11. **Registro de usuarios**: Creación de cuentas mediante correo electrónico y validación de credenciales.  
12. **Administración del sistema**: Control de usuarios, roles, permisos y generación de reportes.  
13. **Soporte en línea**: Gestión de preguntas, reclamos y reseñas de clientes.  
14. **Gestión de inventario**: Control en tiempo real del stock disponible.  
15. **Recomendaciones personalizadas**: Motor interno que sugiera productos relacionados.  

## Requerimientos No Funcionales

- **Rendimiento**: Respuestas en menos de 300 ms en consultas críticas y soporte mínimo de 1,000 usuarios concurrentes.  
- **Disponibilidad**: Operación continua con un SLA de al menos 99.9% mensual.  
- **Seguridad**: Autenticación segura, cifrado TLS 1.2+, almacenamiento seguro de contraseñas y prevención de ataques comunes (SQLi, XSS, CSRF).  
- **Usabilidad**: Diseño intuitivo, interfaz responsive y cumplimiento de normas WCAG 2.1 AA de accesibilidad.  
- **Escalabilidad**: Capacidad de aumentar recursos automáticamente durante picos de demanda.  
- **Mantenibilidad**: Código modular, documentado, con cobertura de pruebas superior al 80%.  
- **Observabilidad**: Monitoreo de métricas de rendimiento, alertas de fallos y trazabilidad de transacciones.  
- **Internacionalización**: Soporte multilenguaje, multimoneda y reglas fiscales configurables.  
- **Resiliencia**: Respaldos frecuentes y tolerancia a fallos con recuperación ante desastres (RPO ≤ 5 minutos, RTO ≤ 30 minutos).  
- **Compatibilidad**: Correcto funcionamiento en navegadores modernos y dispositivos móviles.  

## Diagramas UML

![Diagrama](./Diagrama%20de%20clases.png)

