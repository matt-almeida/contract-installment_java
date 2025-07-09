# Processador de Parcelas de Contrato

Aplicação simples em Java que demonstra o uso de **interfaces**, **orientação a objetos** e a **API de data/hora** para automatizar o processamento de parcelas de contratos de serviço.

Este projeto foi desenvolvido como parte de um curso de Java, com o objetivo de praticar os seguintes conceitos:
- Implementação de interfaces
- Inversão de controle e injeção de dependência
- Camadas de serviço
- Composição entre objetos
- Modelagem básica de domínio

---

## 📋 Descrição do Problema

Uma empresa precisa automatizar o pagamento de seus contratos. Para cada contrato:
- O valor total é parcelado em quantidades mensais definidas.
- Cada parcela possui:
  - **1% de juros simples por mês**
  - **2% de taxa de pagamento**, aplicada após os juros
- A primeira parcela vence um mês após a data do contrato, e assim por diante.

---

## 🛠️ Tecnologias Utilizadas

- Java 8 ou superior
- Orientação a Objetos (classes, interfaces, encapsulamento)
- API de Data/Hora (`LocalDate`, `DateTimeFormatter`)
- Maven (opcional)
- Sem dependências externas

---

## 🧱 Estrutura do Projeto

src/
├── application/ # Classe principal com interação via console
├── model/
│ ├── entities/ # Entidades: Contract, Installment
│ └── services/ # Serviços: PaypalService, ContractService, interface

---

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/matt-almeida/contract-installment_java.git
