# 🔐 Riepilogo Accessi, Credenziali e URL

Riepilogo completo di tutti gli accessi, credenziali e URL (sia tramite rete sicura **Tailscale** che tramite **IP Diretto**), suddivisi per piattaforma:

---

### 🖥️ **1. Server Host (VPS Ubuntu Linux)**
* **IP Pubblico Diretto:** `187.7.28.155`
* **IP Rete Tailscale:** `100.85.249.30`
* **Accesso SSH Diretto:** `ssh root@187.7.28.155`
* **Accesso SSH Tailscale:** `ssh root@100.85.249.30`
* **Password Root:** `JHemsWMPTiol8xmGQDGiSApepnf2zeEb`

---

### 📎 **2. Paperclip AI (Orchestrazione Agenti & Wiki)**
* **URL Rete Tailscale:** [http://100.85.249.30:45133](http://100.85.249.30:45133)
* **URL Diretto:** [http://187.7.28.155:45133](http://187.7.28.155:45133)
* **Wiki Aziendale (Tailscale):** [http://100.85.249.30:45133/PEE/wiki](http://100.85.249.30:45133/PEE/wiki)
* **Wiki Aziendale (Diretto):** [http://187.7.28.155:45133/PEE/wiki](http://187.7.28.155:45133/PEE/wiki)
* **Email Admin:** `sorrentino.alessio@gmail.com`
* **Password:** `JHemsWMPTiol8xmGQDGiSApepnf2zeEb`

---

### 🧠 **3. Obsidian Web (Knowledge Hub & Vault Note)**
* **URL Rete Tailscale:** [http://100.85.249.30:8080](http://100.85.249.30:8080) *(porta alternativa: `:3000`)*
* **URL Diretto:** [http://187.7.28.155:8080](http://187.7.28.155:8080) *(porta alternativa: `:3000`)*
* **Nome Vault Predefinito:** `KnowledgeHub`
* **Obsidian Local REST API (HTTP):** `http://100.85.249.30:27123`
* **Obsidian Local REST API (HTTPS):** `https://100.85.249.30:27124`
* **API Key / Token Bearer:** `JHemsWMPTiol8xmGQDGiSApepnf2zeEb`

---

### 🐙 **4. Repository Remoto GitHub (Backup & Sync Automatico)**
* **URL Repository:** [https://github.com/peerreviewagents-business/agents](https://github.com/peerreviewagents-business/agents)
* **Branch Principale:** `main`
* **Username GitHub:** `peerreviewagents-business`
* **Email:** `peerreviewagents@gmail.com`
* **Personal Access Token (PAT):** `ghp_mUfmMYHuNUXx0JT4... (Configurato nel server Git)`
* **Cartella Log Agenti:** `AgentLogs/`

---

### 🪽 **5. Hermes Bridge & Soul Memory Engine**
* **Dashboard Manager & Memoria (Tailscale):** [http://100.85.249.30:8000](http://100.85.249.30:8000)
* **Dashboard Manager & Memoria (Diretto):** [http://187.7.28.155:8000](http://187.7.28.155:8000)
* **Endpoint API OpenAI Compatibile:** `http://100.85.249.30:8000/v1`
* **Modello:** `hermes-agent`
* **OpenRouter API Key Collegata:** `sk-or-v1-d0eca0b429... (Configurata su .env)`

---

### ⚡ **6. n8n Automation Engine**
* **URL Rete Tailscale:** [http://100.85.249.30:5678](http://100.85.249.30:5678)
* **URL Diretto:** [http://187.7.28.155:5678](http://187.7.28.155:5678)
* **Webhook Base URL:** `http://100.85.249.30:5678/`
