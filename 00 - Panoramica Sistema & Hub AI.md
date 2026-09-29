# 🧠 Knowledge Hub - Hermes & Paperclip AI

Benvenuto nel tuo archivio note centrale sincronizzato e collegato a tutti gli agenti intelligenti del server VPS.

---

## 🔗 Servizi e Connessioni Attive

| Servizio | Indirizzo Tailscale | Scopo |
| :--- | :--- | :--- |
| **Hermes Bridge (OpenAI API)** | `http://100.85.249.30:8000/v1` | Agente AI con Soul e Memoria Dinamica |
| **Hermes Web Manager & Memory** | `http://100.85.249.30:8000` | Gestione anime, personalità e memoria |
| **Paperclip AI Dashboard** | `http://100.85.249.30:45133` | Orchestratore e gestione task agentici |
| **n8n Automation Engine** | `http://100.85.249.30:5678` | Workflow automatici e webhook |
| **Obsidian Local REST API** | `http://100.85.249.30:27123` / `:27124` | API per leggere e scrivere note dall'esterno |

---

## 🤖 Come Usare Hermes in Obsidian (Copilot)
1. Apri la barra laterale destra e clicca sull'icona di **Copilot**.
2. Nelle impostazioni di Copilot (**Settings -> Copilot -> BYOK**), imposta:
   - **Provider:** Custom OpenAI Endpoint
   - **Base URL:** `http://100.85.249.30:8000/v1`
   - **Model:** `hermes-agent`
3. Ora puoi fare domande, riassumere note o generare documentazione parlando direttamente con Hermes, che applicherà la memoria condivisa del team!
