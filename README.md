# Projeto Java Stack - Alura

## Descrição
Projeto de estudos em Java, com foco em tratamento de exceções, fluxo de execução e boas práticas de manipulação de erros. O projeto demonstra como criar exceções customizadas, tratar exceções em métodos e controlar o fluxo de execução em diferentes cenários.

## Estrutura das Classes

- **Account**: Classe de exemplo que possui um método `deposit()` que pode lançar uma exceção customizada (`MineException`).
- **MineException**: Exceção customizada que herda de `RuntimeException`.
- **AccountTestCheckedException**: Classe de teste que instancia `Account` e executa o método `deposit()`, tratando possíveis exceções.
- **Flow**: Demonstra o fluxo de execução com métodos aninhados e o lançamento de uma exceção customizada.
- **FlowWithTreatment**: Similar à classe Flow, mas com tratamento específico para `NullPointerException` e `ArithmeticException`.
- **FlowError**: (Conteúdo não totalmente disponível) Provavelmente demonstra fluxo com erros e exceções.
- **Conection** e **TestConection**: (Conteúdo não disponível) Provavelmente relacionadas a testes de conexão e manipulação de recursos.

## Como executar
1. Compile todos os arquivos `.java` na pasta `src`.
2. Execute as classes de teste, como `AccountTestCheckedException`, `Flow` ou `FlowWithTreatment`, para ver exemplos de tratamento de exceções.

## Objetivo
O objetivo deste projeto é praticar e demonstrar conceitos de:
- Criação e uso de exceções customizadas
- Tratamento de exceções (try/catch)
- Controle de fluxo em métodos
- Boas práticas de manipulação de erros em Java

---
Projeto para fins didáticos, baseado em exercícios da formação Java da Alura.

