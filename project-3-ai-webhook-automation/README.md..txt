# Proyecto 3: Sistema Inteligente de Procesamiento de Inbound Webhooks con IA (LLM)

Pipeline de automatización avanzado que consume eventos HTTP en tiempo real mediante Webhooks, procesa payloads no estructurados utilizando Inteligencia Artificial (LLM) para clasificación/resumen de datos y ejecuta enrutamiento dinámico hacia servicios de persistencia y alertas.

---

## 🛠️ Tecnologías e Integraciones

* **Trigger:** Webhook (HTTP POST Listener)
* **AI/LLM Engine:** OpenAI / Anthropic API (Extracción de entidades y clasificación de urgencia)
* **Routing Logic:** Switch Node (Enrutamiento condicional según prioridad)
* **Persistencia & Alerta:** Google Sheets API & Telegram Bot API