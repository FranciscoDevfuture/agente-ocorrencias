# 🚌 Agente de Ocorrências

> Aplicativo Android para registro de ocorrências operacionais em terminais de ônibus urbanos, com geração automática de relatórios via IA.

---

## 📱 Sobre o Projeto

O **Agente de Ocorrências** nasceu de uma necessidade real da operação. Como Agente de OTU (Operação de Trânsito Urbano) em um terminal de ônibus de São Paulo, percebi que o registro de ocorrências poderia ser mais ágil, padronizado e profissional.

O app conduz o atendente por um fluxo inteligente de perguntas — adaptado ao tipo de ocorrência — e gera automaticamente um relatório formal completo, pronto para uso operacional.

> Desenvolvido através de curso sobre **Claude AI da Anthropic**.

---

## 🔴 Tipos de Ocorrência

| Tipo | Descrição |
|------|-----------|
| 🆘 **Mal Súbito** | Fluxo clínico completo com lógica de consciência, recusa de atendimento e Termo de Recusa |
| 🚌 **Acidente entre Coletivos** | Dados dos dois coletivos, dinâmica, danos, vítimas, PM/GCM e SAMU |
| 🚗 **Acidente com Veículo Particular** | Dados do coletivo + veículo particular, condutor, CNH, danos e vítimas |

---

## ✅ Funcionalidades

- 💬 Fluxo de perguntas em estilo chat com lógica condicional
- 🤖 Geração de relatório com IA (Groq / LLaMA 3.3 70B)
- 📵 Modo offline com template local
- 📲 Compartilhamento direto via WhatsApp
- 💾 Histórico de ocorrências salvo no dispositivo
- 📷 Registro fotográfico (câmera ou galeria, máx. 2 fotos)
- 📊 Barra de progresso em tempo real
- ✏️ Correção do relatório com IA

---

## 🛠️ Tecnologias

- **React 18** + **Vite**
- **Capacitor 6** (APK Android)
- **Groq API** (LLaMA 3.3 70B)
- **Android Studio**

---

## 🚀 Como Rodar

### Pré-requisitos
- Node.js 18+
- Android Studio
- Conta na [Groq](https://console.groq.com) para obter a API Key

### Instalação

```bash
git clone https://github.com/FranciscoDevfuture/agente-ocorrencias.git
cd agente-ocorrencias
npm install
npm install @capacitor/core @capacitor/cli @capacitor/android
npm run build
npx cap add android
npx cap sync android
npx cap open android
```

No Android Studio: **Build → Build APK(s)**

---

## ⚙️ Configuração

No app, acesse **Configurações** e informe:
- **Chave API Groq** — obtenha em [console.groq.com](https://console.groq.com)
- **Terminal padrão** — pré-preenche automaticamente

---

## 👤 Autor

**Francisco José Santos**
- OTU — Operador de Terminal Urbano
- Estudante de Análise e Desenvolvimento de Sistemas — UniFECAF
- GitHub: [@FranciscoDevfuture](https://github.com/FranciscoDevfuture)

---

## 📄 Licença

MIT License



Prints do Projeto


<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/055570ba-b369-4c98-ac6c-68d0cd25dc9f" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/cb3d246c-2fa4-412b-a71c-d3d00c0136f4" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/39660cfb-ad33-431b-a011-6d7b9fe198cf" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/a9eb5bbe-8e1e-4142-82f8-0c1ca4055c72" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/fc9d481a-e763-4236-a69f-9f06159d845c" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/d865506b-b517-444a-8d03-24e80f439c6f" />
<img width="738" height="1600" alt="image" src="https://github.com/user-attachments/assets/9f10bfd7-5b9c-4a1c-abbe-966909b2234e" />








