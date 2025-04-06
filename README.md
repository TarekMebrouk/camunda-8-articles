# 🛠️ Camunda 8 Articles Workspace

Welcome to the official workspace for all articles I write about **Camunda 8**, covering real use cases and hands-on examples such as REST connectors, email integration, automation, and workflow orchestration.

This repository is structured as a central hub, with each article or topic organized into its own branch to keep implementations isolated and focused.

---

## 📂 Repository Structure

- `main`: General information, base structure.
- `rest-connector`: BPMN models, configurations, and assets for the article:  
  **"REST API Integration Made Easy with Camunda 8"**
- Future branches:
  - `email-connector`
  - `external-task-pattern`
  - `zeebe-client-integration`, etc.

---

## 🚀 Getting Started

This project is based on **Camunda 8 Self-Managed** distribution using **Docker Compose**.

### 📦 Camunda Platform Setup

You can find the official `docker-compose.yaml` and setup guide here:  
🔗 [Camunda Distributions Repository](https://github.com/camunda/camunda-distributions)

To spin up the platform:

```bash
git clone https://github.com/camunda/camunda-distributions.git
cd camunda-distributions/self-managed/docker-compose/version/${CAMUNDA_VERSION}
docker compose up -d
```

After startup, the following Camunda services will be available:
- Operate: http://localhost:8081
- Tasklist: http://localhost:8082
- Zeebe Gateway: localhost:26500

## ✍️ Branch: rest-connector
This branch includes all the resources related to the article “🚀Automating REST API Calls with Camunda 8: Everything You Need to Know”:
- BPMN models
- Connector environment configuration (input mappings, headers, etc.)
- Example payloads and responses

## 🎯 Purpose
This repository serves as:
- A central space for sharing Camunda 8 article resources
- A sandbox for trying out BPMN workflows and connectors
- A reference for developers learning Camunda through real-world examples

## 📬 Stay Tuned
Each future article will be added as a separate branch, with:
- Clear structure and documentation
- Live BPMN examples and connectors
- Contextual README in each branch

Feel free to fork, star, or contribute!

Questions? Open an issue or reach out via LinkedIn or GitHub Discussions.

## 📜 License
This project is licensed under the MIT License.
