# Visión general — VANEMA

- `Visión general --> Modelo productivo --> Personalización bajo pedido (sin stock previo de prendas personalizadas).`
- `Visión general --> Canales --> Web y App móvil integradas con Odoo.`
- `Visión general --> Clientes --> Particulares (B2C) y Empresas (B2B: presupuestos, volumen y recurrencia).`
- `Visión general --> Técnicas --> Bordado y serigrafía sobre prendas base.`
- `Visión general --> Flujo general --> Pedido (Web/App) --> Ventas/CRM --> Diseño --> Logística/Producción --> Envío y Facturación.`
--------------------------------------------------------------------------------------------------------------------------------------
# 👕 VANEMA — ERP (Odoo) y Plataforma de Personalización Textil Bajo Pedido

![Estado del proyecto](https://img.shields.io/badge/Estado-En%20desarrollo-blue)
![ERP](https://img.shields.io/badge/ERP-Odoo-purple)
![Módulo](https://img.shields.io/badge/M%C3%B3dulo-Sistemas%20de%20Gesti%C3%B3n%20Empresarial-green)
![Ciclo](https://img.shields.io/badge/Grado%20Superior-DAW%20%2F%20ASIR-orange)

## 📖 Descripción del proyecto

**VANEMA** es un proyecto académico desarrollado para la optativa de **Sistemas de Gestión Empresarial (SGE)** en un Ciclo Formativo de Grado Superior (**DAW / ASIR**).

El proyecto implementa la gestión integral sobre **Odoo ERP** de una marca especializada en la **personalización textil bajo pedido** (*Make-to-Order*), con acabados de **bordado** y **serigrafía** sobre prendas base.

La comercialización se realiza a través de **Web** y **App móvil**, dando servicio tanto a **clientes particulares (B2C)** como a **empresas (B2B)**. Todo el flujo operativo está centralizado en **Odoo** para coordinar de extremo a extremo la entrada del pedido, la validación del diseño, la producción bajo demanda, el control de inventario y la facturación.

---

## 🎯 Modelo de negocio y canales

- **Modelo productivo:** Producción / personalización **bajo pedido** (*Make-to-Order*), evitando sobrestock de artículos ya personalizados.
- **Canales de venta:** **Web** y **App móvil** conectados con Odoo.
- **Segmentos de clientes:**
  - **Particulares (B2C):** Pedidos unitarios o pequeñas tiradas configuradas directamente desde web o app.
  - **Empresas (B2B):** Pedidos recurrentes o por volumen, gestión de presupuestos personalizados y facturación corporativa.

---

## 🏢 Departamentos y módulos de Odoo

La estructura organizativa de **VANEMA** se articula dentro de **Odoo** mediante la integración de sus distintos departamentos y aplicaciones:

| Departamento | Función en VANEMA | Módulos de Odoo asociados |
| :--- | :--- | :--- |
| **Diseño** | Validación, adaptación y preparación de artes finales para **bordado** o **serigrafía**. | *Documentos / PLM / Proyectos* |
| **Desarrollo de producto** | Definición del catálogo de prendas base, listas de materiales (escandallos) y rutas de fabricación. | *Fabricación (MRP) / PLM / Inventario* |
| **Logística** | Control de stock de prendas base y consumibles (hilos, tintas, embalajes), órdenes de trabajo y envíos. | *Inventario / Fabricación (MRP) / Compras* |
| **Marketing** | Campañas promocionales, automatización de comunicaciones y segmentación B2C y B2B. | *Email Marketing / Automatización / Sitio Web* |
| **Ventas** | Gestión de pedidos web/app, tarifas por volumen, presupuestos a empresas y seguimiento comercial. | *Ventas / CRM / Sitio Web* |
| **Atención al cliente** | Gestión de incidencias, consultas sobre estados de pedido, revisiones de diseño y postventa. | *Servicio de Asistencia (Helpdesk) / Contactos* |
| **Finanzas** | Contabilidad, facturación automatizada, control de cobros/pagos y análisis de rentabilidad por pedido. | *Contabilidad / Facturación* |

---

## 🔄 Flujo operativo bajo pedido en Odoo

1. **Pedido desde Web o App:** El cliente (particular o empresa) selecciona la prenda base, sube o configura su diseño y elige **bordado** o **serigrafía**.
2. **Ventas y CRM:** El pedido o solicitud de presupuesto se registra automáticamente en **Odoo Ventas/CRM**.
3. **Validación de Diseño:** El equipo de **Diseño** revisa el archivo gráfico y aprueba su viabilidad técnica para el taller.
4. **Abastecimiento y Producción (MTO):** **Odoo Inventario y Fabricación** verifican el stock de prenda virgen y consumibles, generando la orden de producción bajo pedido.
5. **Seguimiento y Soporte:** **Atención al cliente** gestiona cualquier consulta o incidencia sobre el estado del pedido desde *Helpdesk*.
6. **Envío y Facturación:** **Logística** despacha el pedido y **Finanzas** emite y contabiliza la factura correspondiente.

---

## 🛠️ Stack tecnológico y arquitectura

- **ERP:** Odoo *(Community / Enterprise)*
- **Base de datos:** PostgreSQL
- **Canales digitales:** Plataforma Web *(Odoo Website / Frontend propio)* y App móvil conectada vía API *(XML-RPC / JSON-RPC)*
- **Infraestructura y despliegue (ASIR):** Servidor Linux, Docker / Docker Compose, Nginx como proxy inverso, SSL y políticas de backup
- **Control de versiones:** Git & GitHub

---

## 👥 Autores

- **Josemanuel Morató** — *[@usuario-github](https://github.com/)*
- **Iván Piera** — *[@usuario-github](https://github.com/)*

---

## 📄 Licencia

Proyecto desarrollado con fines educativos para la asignatura de **Sistemas de Gestión Empresarial** (Grado Superior **DAW / ASIR**).
