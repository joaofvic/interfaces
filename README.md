# 💳 Processamento de Contratos em Java

Este projeto simula o processamento de um contrato com pagamento parcelado, aplicando **juros mensais** e **taxa de serviço** sobre cada parcela.

Desenvolvido como prática de conceitos fundamentais da **Programação Orientada a Objetos em Java**, com foco em **interfaces**, **injeção de dependência**, **serviços**, e **manipulação de datas**.

---

## 🔧 Tecnologias e Conceitos Utilizados

- **Java 17+**
- **Programação Orientada a Objetos (POO)**
- **Composição e Encapsulamento**
- **Interfaces e Inversão de Dependência (DIP - SOLID)**
- **Serviços com regras de negócio (juros e taxas)**
- **API `java.time` (LocalDate, DateTimeFormatter)**
- Entrada e saída via console (`Scanner`, `System.out`)
- Boas práticas de estruturação de código

---

## 📌 Funcionalidades

- Entrada de dados do contrato via console:
  - Número do contrato
  - Data do contrato
  - Valor total
  - Número de parcelas
- Cálculo automático das parcelas mensais com:
  - Juros simples de 1% ao mês
  - Taxa de pagamento de 2% sobre o valor com juros
- Geração e exibição das parcelas com valor e data de vencimento formatada

---

## 📁 Estrutura do Projeto

src/
├── application/
│ └── Program.java // Classe principal
├── model/
│ ├── entities/
│ │ ├── Contract.java // Representa o contrato
│ │ └── Installment.java // Representa cada parcela
│ └── services/
│ ├── ContractService.java // Lógica de processamento de contrato
│ ├── OnlinePaymentService.java // Interface de serviço de pagamento
│ └── PaypalService.java // Implementação concreta da interface

---

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
Compile e execute o projeto com sua IDE Java (Eclipse, IntelliJ, VSCode) ou via terminal.

📷 Exemplo de Uso

Enter contract data:
Number: 2222
Date (dd/MM/yyyy): 25/08/2025
Contract value: 600.00
Enter the number of installments: 3

Installments:
25/09/2025 - 206.04
25/10/2025 - 208.08
25/11/2025 - 210.12
👨‍💻 Autor
João Victor Firmino Sousa
📧 fjoao2012v@gmail.com
🔗 [linkedin.com/in/seu-perfil](https://www.linkedin.com/in/jo%C3%A3o-victor-firmino-sousa-130874208/)
