# 🛡️ Wazuh: Guia de Implementação Estruturada e Monitoramento Multiplataforma

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![Wazuh Version](https://img.shields.io/badge/Wazuh-4.x-blue.svg)](https://wazuh.com)
[![Platform](https://img.shields.io/badge/Platform-Ubuntu%20%7C%20Windows%20%7C%20Linux-orange.svg)](https://ubuntu.com)

Bem-vindo ao repositório oficial do livro **"Wazuh: Guia de Implementação Estruturada e Monitoramento Multiplataforma"**[cite: 2, 4]. 

Este material foi criado como um passo a passo prático e detalhado, documentando todo o processo de instalação, configuração e operação da plataforma open-source de **SIEM / XDR Wazuh** em um ambiente real com **Ubuntu Server**[cite: 2, 4, 14].

---

## 📚 Conteúdo do Livro

O guia abrange desde a preparação do sistema até técnicas avançadas de monitoramento e resposta a incidentes:

- **Instalação do Wazuh Server (Manager & Dashboard)** no Ubuntu Server[cite: 4, 5, 11].
- **Implementação e gestão de Agentes** em sistemas Linux e Windows[cite: 14, 59].
- **Monitoramento de Integridade de Arquivos (FIM)** e verificação do Registro do Windows[cite: 24, 69, 70].
- **Detecção de Vulnerabilidades (CVEs)** e avaliação de segurança (SCA / Hardening)[cite: 26, 27].
- **Resposta Ativa (Active Response):** Bloqueio automático de ataques (ex: Brute Force SSH/RDP)[cite: 28, 85].
- **Auditoria Avançada:** Auditoria de comandos via `auditd`, monitoramento de Docker e logs de Nginx/Apache[cite: 30, 32, 38, 47].
- **Integração com Suricata (NIDS)** e alertas em tempo real via **Slack**[cite: 42, 44].
- **Regras Customizadas, Decoders e Controle de Dispositivos USB**[cite: 31, 51].

---

## 📁 Estrutura do Repositório

O repositório está organizado para facilitar tanto a leitura rápida quanto a colaboração da comunidade:

```text
.
├── 📂 docs/       # Manual oficial pronto para leitura e download (PDF)
├── 📂 source/     # Arquivos fontes do livro para edições, correções e contribuições
├── 📄 LICENSE     # Licença de uso do projeto (MIT)
└── 📄 README.md   # Informações gerais sobre o projeto
