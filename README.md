# 🚀 Portafolio de Automatizaciones con n8n

Bienvenido a mi portafolio de automatización de flujos de trabajo con **n8n**. En este repositorio documento proyectos prácticos enfocados en la integración de APIs, Inteligencia Artificial, gestión de bases de datos y herramientas de productividad para optimizar procesos operativos.

---

## 📚 Proyectos Incluidos

| # | Proyecto | Descripción | Tecnologías Clave | Estado |
|---|---|---|---|---|
| **01** | **[Telegram & OpenAI Integration](./project-1-telegram-bot/)** | Bot interactivo en Telegram asistido por IA para responder consultas de usuarios en tiempo real. | `n8n`, `Telegram API`, `OpenAI` | 🟢 Completado |
| **02** | **[Automated Form & Database Sync](./project-2-form-to-sheets/)** | Captura de datos mediante formularios web y sincronización automática en Google Sheets con notificaciones. | `n8n`, `HTML Forms`, `Google Sheets API` | 🟢 Completado |
| **03** | **[AI-Powered Webhook & Ticket Router](./project-3-ai-webhook-automation/)** | Clasificación inteligente de solicitudes entrantes vía Webhook usando LLMs y enrutamiento dinámico (Gmail para urgencia ALTA, Google Sheets para NORMAL). | `n8n`, `Webhooks`, `Groq / OpenAI`, `Gmail API`, `Google Sheets` | 🟢 Completado |

---

## 🛠️ Proyecto 3: Procesador Inteligente de Webhooks & Enrutamiento de Tickets

### 📌 Arquitectura del Flujo

```text
[ Webhook POST ] ──> [ IA (Groq / LLM) ] ──> [ Edit Fields ] ──> [ Switch ]
                                                                   ├── (Urgencia ALTA)   ──> [ Gmail ]
                                                                   └── (Urgencia NORMAL) ──> [ Google Sheets ]
