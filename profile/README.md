# 🐯 Desbravadores - Projeto Tigre da Montanha

O **Tigre da Montanha** é uma solução robusta de monitoramento inteligente voltada para a infraestrutura de tecnologia e segurança. Nosso foco é garantir a integridade dos sistemas através de análise de dados em tempo real, prevenção de falhas e segurança operacional.

---

### 🚨 O Problema
Muitas infraestruturas sofrem com a falta de visibilidade sobre o que acontece no hardware e na rede, resultando em:
* **Interrupções inesperadas** (Downtime).
* **Vulnerabilidade a ações maliciosas** ou falhas humanas internas.
* **Manutenção reativa**, que gera custos elevados e urgências desnecessárias.

### 💡 A Solução: Tigre da Montanha
Desenvolvemos um ecossistema completo para monitoramento proativo:
* **Coleta de Métricas:** Monitoramento de saúde de CPU, Memória, Disco e Tráfego de Rede.
* **Inteligência Preditiva:** Identificação de padrões que precedem falhas de sistema.
* **Segurança Cibernética:** Detecção de comportamentos anômalos no ambiente monitorado.
* **Visibilidade Total:** Dashboards intuitivos para tomada de decisão rápida.

---

### 🗂️ Estrutura da Organização
O projeto está segmentado para garantir escalabilidade e organização:

* 📂 **[Tigre-Banco-De-Dados](https://github.com/desbravadores-sisa)**: Scripts SQL e modelagem relacional (MySQL).
* 📂 **[Tigre-Coleta-Python](https://github.com/desbravadores-sisa)**: Agente de captura de dados de baixo nível.
* 📂 **[Tigre-Backend-Java](https://github.com/desbravadores-sisa)**: Motor de processamento construído com Spring Boot.
* 📂 **[Tigre-App-Web](https://github.com/desbravadores-sisa)**: Dashboard front-end (JS, HTML, CSS).
* 📂 **[Tigre-Infra-AWS](https://github.com/desbravadores-sisa)**: Configurações de nuvem e instâncias EC2.

---

### ⚙️ Tecnologias
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)

---

### 🌐 Arquitetura do Sistema
1. **Agente de Coleta:** Scripts Python capturam métricas de hardware.
2. **Processamento (ETL):** Aplicação Java Spring Boot consome e trata os dados.
3. **Persistência:** Banco de dados MySQL armazena o histórico para análises.
4. **Camada de Visão:** Interface Web consome a API para exibir gráficos e alertas.

---

### ✒️ Equipe Desbravadores
*(Preencha os nomes dos integrantes abaixo)*

* **Integrante 1:** [Nome Completo] - [Função/Cargo]
* **Integrante 2:** [Nome Completo] - [Função/Cargo]
* **Integrante 3:** [Nome Completo] - [Função/Cargo]
* **Integrante 4:** [Nome Completo] - [Função/Cargo]
* **Integrante 5:** [Nome Completo] - [Função/Cargo]
* **Integrante 6:** [Nome Completo] - [Função/Cargo]

---
*Projeto desenvolvido pela organização Desbravadores para monitoramento inteligente de ativos.*
