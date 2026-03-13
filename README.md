# SIGAU Demo
## Sistema Integrado de Gestión Administrativa Universitaria

Demo HTML navegable orientada a presentación comercial de un sistema de gestión administrativa universitaria para formación continua.

Este prototipo fue diseñado para mostrar de forma visual e interactiva el recorrido completo del aspirante/alumno dentro de una plataforma institucional, desde la oferta académica hasta la certificación final.

---

## Objetivo

Mostrar al cliente una visión integral de lo que puede hacer el sistema, sin backend real ni base de datos, pero con una experiencia navegable y convincente.

La demo busca representar:

- orden institucional,
- trazabilidad del alumno,
- automatización administrativa,
- control académico y arancelario,
- gestión de cuellos de botella,
- certificación con reglas visibles.

---

## Alcance de la demo

La maqueta incluye los siguientes módulos dentro de un único archivo HTML:

### 1. Portal público
- catálogo de propuestas académicas,
- filtros por modalidad, duración y arancel,
- vista de detalle de propuesta,
- inicio del flujo de postulación.

### 2. Ingreso / registro
- acceso del aspirante,
- creación de cuenta,
- validaciones visuales,
- continuidad hacia la inscripción.

### 3. Inscripción
- formulario de datos personales,
- carga documental,
- validaciones simuladas,
- confirmación de estado **PREINSCRIPTO**.

### 4. Backoffice administrativo
- bandeja de preinscriptos,
- semáforo SLA,
- revisión documental,
- acciones sobre expediente,
- generación de legajo y chequera.

### 5. Integración con Secretaría Administrativa
- carga simulada de archivo CSV,
- procesamiento de actualización,
- asignación de número de inscripto / legajo,
- vinculación de chequera,
- visualización del cuello de botella operativo.

### 6. Panel del alumno
- estado académico,
- estado arancelario,
- alertas,
- descargas,
- timeline del proceso.

### 7. Certificación
- validación académica,
- validación administrativa,
- control arancelario,
- elegibilidad para certificar,
- emisión simulada de certificado.

---

## Características

- HTML, CSS y JavaScript puro
- sin dependencias externas complejas
- navegación demostrativa entre pantallas
- filtros funcionales en catálogo y backoffice
- acciones simuladas para demo comercial
- estructura visual institucional y escalable

---

## Importante

Este repositorio contiene una **demo visual**.

No incluye:

- backend real,
- autenticación real,
- persistencia de datos,
- integración real con sistemas externos,
- procesamiento real de archivos CSV,
- emisión real de certificados.

Todas las acciones están simuladas con fines de presentación y validación funcional/comercial.

---

## Caso de uso de esta demo

Este prototipo está pensado para:

- presentar el concepto al cliente,
- validar la experiencia general del sistema,
- mostrar el flujo completo del proceso,
- discutir mejoras funcionales antes del desarrollo productivo.

---

## Estructura actual

```bash
.
├── index.html
