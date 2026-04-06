# 🎯 Leads Intelligence API (n8n + JavaScript)

<p align="center">
  <a href="#about-en">English</a> • 
  <a href="#about-pt">Português</a>
</p>

---

<h2 id="about-en">🇺🇸 About the Project</h2>

This project demonstrates a real-time **Lead Scoring & Triage API** built entirely within n8n. It receives data via Webhook, processes business logic using JavaScript, and returns a dynamic, styled HTML response directly to the user's browser.

### 🛠️ Key Technical Skills:
* **Serverless API Design**: Creating a functional endpoint that processes GET requests.
* **Lead Scoring Logic**: Custom JavaScript to identify B2B leads vs. personal emails and assign priority levels.
* **Dynamic Frontend Generation**: Using the **Respond to Webhook** node to render stylized HTML templates on the fly.
* **Business Logic**: Automated triage based on domain recognition (e.g., recognizing `n8n.io` as a VIP partner).

### 📋 How to test (Zero Config)
1. Import the `leads_api_workflow.json` file into your n8n instance.
2. Click **"Listen for test event"** in the Webhook node.
3. Paste the following URL into your browser (replace with your local n8n address if different):
   `http://localhost:5678/webhook-test/triagem-leads?nome=JohnDoe&email=john@n8n.io&empresa=AcmeCorp`
4. **The Result:** You will receive a stylized result card directly in your browser.

---

<h2 id="about-pt">🇧🇷 Sobre o Projeto</h2>

Este projeto demonstra uma **API de Score e Triagem de Leads** em tempo real, construída inteiramente dentro do n8n. Ele recebe dados via Webhook, processa a lógica de negócios via JavaScript e retorna uma resposta HTML estilizada e dinâmica diretamente para o navegador do usuário.

### 🛠️ Competências Técnicas:
* **Design de API Serverless**: Criação de um endpoint funcional que processa requisições GET.
* **Lógica de Score de Leads**: JavaScript customizado para identificar leads B2B vs. e-mails pessoais e atribuir níveis de prioridade.
* **Geração Dinâmica de Frontend**: Uso do nó **Respond to Webhook** para renderizar templates HTML estilizados em tempo real.
* **Lógica de Negócios**: Triagem automatizada baseada em reconhecimento de domínio (ex: reconhecendo `n8n.io` como parceiro VIP).

### 📋 Como testar (Sem cadastro)
1. Importe o arquivo `leads_api_workflow.json` na sua instância do n8n.
2. Clique em **"Listen for test event"** no nó Webhook.
3. Cole a seguinte URL no seu navegador:
   `http://localhost:5678/webhook-test/triagem-leads?nome=Rodrigo&email=contato@n8n.io&empresa=MinhaEmpresa`
4. **O Resultado:** Você receberá um card de resultado estilizado diretamente no seu navegador.

---

<p align="center">
  <i>Part of an automation portfolio showcasing Low-code development and Backend logic.</i>
</p>
