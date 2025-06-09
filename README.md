# sartorialis
Web system for bespoke tailoring management, including client registration, measurement tracking, service orders, and automatic pattern generation. Backend in C# with ASP.NET Core and frontend in React.

# Sartorialis

**Sistema web para gestão de alfaiataria sob medida**, com funcionalidades voltadas para o controle completo de clientes, medidas, ordens de serviço e geração automática de moldes personalizados.

---

## ✨ Tecnologias utilizadas

- 🔹 **Backend:** ASP.NET Core (C#)
- 🔹 **Banco de Dados:** MySQL
- 🔹 **Frontend:** React.js + Tailwind CSS + Shadcn UI
- 🔹 **Autenticação:** JWT
- 🔹 **Desenho de Moldes:** SVG via frontend

---

## 🎯 Funcionalidades

- Cadastro e login de clientes e administrador
- Cadastro completo de medidas por tipo de peça
- Solicitação de peças sob medida
- Geração automática de moldes a partir das medidas
- Gestão de pedidos, contratos e ordens de serviço
- Visualização de histórico por cliente
- Painel administrativo

---

## 🧠 Objetivo do projeto

Este sistema está sendo desenvolvido como parte de um projeto real de informatização de uma alfaiataria, com o intuito de aplicar React na prática e demonstrar como conectar frontend moderno com backend robusto usando C#.

---

## 📁 Estrutura do projeto

```bash
/Sartorialis
├── backend/              # ASP.NET Core (Web API)
├── frontend/             # React com Tailwind e Shadcn UI
└── README.md

🚀 Como rodar o projeto localmente
Requisitos:
.NET SDK 7.0+

Node.js 18+

MySQL Server

1. Clonar o repositório

git clone https://github.com/seu-usuario/Sartorialis.git

2. Rodar o Backend
cd Sartorialis/backend
dotnet restore
dotnet run

3. Rodar o Frontend
cd Sartorialis/frontend
npm install
npm run dev

📌 Status do projeto
🛠️ Em desenvolvimento — primeira versão do backend sendo implementada.

📫 Contato
Desenvolvido por Roger Aguiar
📧 roger.silvaaguiar.com

📄 Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.
