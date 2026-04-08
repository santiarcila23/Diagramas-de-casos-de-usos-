# TelecomSys — Sistema de Gestión para Telecomunicaciones
### Conexión Total S.A.

---

## Descripción del proyecto

**TelecomSys** es un sistema de gestión integral desarrollado para la empresa de telecomunicaciones **Conexión Total S.A.** El sistema administra los servicios, clientes y operaciones comerciales de la empresa, cubriendo desde el registro de planes y contratos hasta la facturación y el seguimiento de averías técnicas.

---

## Estructura de módulos

El sistema está compuesto por **2 módulos principales**:

### Módulo 1 — Gestión de Clientes
Administra el ciclo de vida completo de los clientes de la empresa.

| Funcionalidad | Descripción |
|---|---|
| Registrar cliente | Alta de clientes personales y empresariales con ID único, datos de identidad, ubicación geográfica y clasificación crediticia |
| Consultar / modificar cliente | Búsqueda por nombre, documento o correo; edición de datos con historial de auditoría |
| Verificar límite de crédito | Validación automática del crédito disponible al momento de contratar un nuevo servicio |
| Buscar cliente | Búsqueda rápida (< 2 segundos) por múltiples criterios |
| Clasificar crédito | Asignación y actualización de la clasificación crediticia por el área financiera |

### Módulo 2 — Contratos y Planes de Servicio
Gestiona los planes disponibles y los contratos firmados con los clientes.

| Funcionalidad | Descripción |
|---|---|
| Registrar plan de servicio | Creación de planes de telefonía móvil, internet fijo, televisión y paquetes con tarifa, permanencia y promociones |
| Crear contrato | Vinculación de cliente + plan + dirección + equipos + condiciones especiales |
| Gestionar estado de contrato | Control del ciclo: borrador → activo → suspendido → cancelado → terminado |
| Activar línea móvil | Registro de IMEI, IMSI, plan activo, consumo promedio y límite de crédito por línea |
| Registrar internet fijo | Alta de instalaciones con tipo de tecnología (ADSL/fibra/coaxial), IP, MAC y parámetros técnicos |
| Consultar planes disponibles | Vista pública de planes vigentes para uso en proceso comercial |



## Actores del sistema

| Actor | Tipo | Acceso |
|---|---|---|
| **Agente comercial** | Principal | Clientes, contratos, planes |
| **Técnico** | Principal | Averías, equipos, internet fijo |
| **Administrador** | Principal | Acceso total + gestión de usuarios |
| **Gerente** | Principal | Solo lectura + reportes ejecutivos |

## Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| Draw.io (diagrams.net) | Elaboración del diagrama UML de casos de uso |
| GitHub | Control de versiones y entrega del proyecto |

---

## Instrucciones de uso del repositorio

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/TU_USUARIO/telecomsys.git
   cd telecomsys
   ```

2. **Estructura de carpetas:**
   ```
   telecomsys/
   ├── README.md
   ├── Link_del_diagrama
   ├── captura_del_diagrama.png
       
  
   ```

3. **Ver el diagrama:** Abre el archivo `.png` directamente en el navegador o en cualquier visor de imágenes.

---

## Información académica

| Campo | Detalle |
|---|---|
| **Estudiante** | Santiago Arcila Gutiérrez |
| **Institución** | CEFIT — Centro de Formación Integral Técnico |
| **Programa** | Técnica en Análisis y Programación de Desarrollo de Software |
| **Asignatura** | ASP-03-11 Desarrollo de Sistemas: Requisitos y Diseño |
| **Docente** | James Mosquera Rentería |
| **Fecha** | Abril 2026 |

---

*Sistema desarrollado como parte del trabajo académico del programa de Análisis y Programación de Desarrollo de Software — CEFIT.*
