# Portafolio de Automatización e Integración con n8n

Repositorio oficial de proyectos de automatización de flujos de trabajo, integración de APIs y mensajería multicanal sobre infraestructura basada en contenedores.

---

## 🛠️ Infraestructura y Tecnologías

* **Core Engine:** n8n (Self-hosted sobre Docker & WSL2)
* **Control de Versiones:** Git & GitHub Desktop
* **Autenticación:** Service Accounts (Google Cloud Platform) M2M, Telegram Bot API
* **Persistencia & Notificaciones:** Google Sheets API, Telegram API

---

## 🚀 Proyectos Implementados

### 🟢 Proyecto 1: Sistema de Captura y Validación de Leads
* **Carpeta:** `/project-1-lead-capture`
* **Descripción:** Pipeline de ingesta de datos con interfaz web, lógica condicional para filtrado de registros corruptos/inválidos y persistencia directa en hojas de cálculo empresarial mediante autenticación M2M.

### 🟢 Proyecto 2: Sistema de Notificaciones Multicanal en Tiempo Real (Telegram)
* **Carpeta:** `/project-2-telegram-notifications`
* **Descripción:** Extensión de la arquitectura de captura mediante la integración de la API de Telegram. Permite el monitoreo activo mediante alertas formateadas e instantáneas al teléfono del equipo técnico/comercial ante cada nuevo registro válido.

---

## 💼 Enfoque para Entrevistas Técnicas (STAR)

* **Situación / Tarea:** Requerimiento de monitoreo inmediato para reducir el tiempo de respuesta (*Speed-to-lead*) a clientes potenciales.
* **Acción:** Integración de nodos de mensajería API con plantillas HTML/Markdown de respuesta dinámica basadas en los atributos del payload de la consulta.
* **Resultado:** Reducción del tiempo de notificación a **< 1 segundo** tras la validación de los datos.