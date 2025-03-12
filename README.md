# Controle de Fluxo - Desafio

Este repositório contém a solução para o desafio **"Controle de Fluxo"** proposto pela **DIO**. O objetivo é praticar o uso de estruturas de controle de fluxo em Java, incluindo exceções customizadas e laços de repetição.

## 📌 Descrição do Desafio

O sistema recebe dois números inteiros como entrada via terminal e realiza a contagem de interações conforme as regras:

1. Se o primeiro número for **menor** que o segundo, o programa deve imprimir a quantidade de números entre eles.
2. Caso o primeiro número seja **maior** que o segundo, o programa lança uma exceção customizada ParametrosInvalidosException.

### 🔹 Exemplo de Entrada e Saída

#### ✅ Entrada: 
Digite o primeiro parâmetro: 12   
Digite o segundo parâmetro: 30
#### 🔽 Saída: Imprimindo o número 1 Imprimindo o número 2 Imprimindo o número 3 ... Imprimindo o número 18


Se o primeiro parâmetro for maior que o segundo:

#### ❌ Entrada: 
Digite o primeiro parâmetro: 30  
Digite o segundo parâmetro: 12
#### ⚠️ Saída: O segundo parâmetro deve ser maior que o primeiro

---

## 📂 Estrutura do Projeto

O projeto contém as seguintes classes:

- **Contador.java**: Classe principal que recebe os valores via terminal, valida a entrada e executa a contagem.
- **ParametrosInvalidosException.java**: Classe de exceção customizada para lidar com entradas inválidas.

## 🚀 Como Executar o Programa

1. Clone este repositório:
   

   git clone https://github.com/yohanngusso/Controle_Fluxo-DIO.git

🛠 Tecnologias Utilizadas
- Java 21
- Scanner para entrada de dados via terminal
- Exceções customizadas para tratamento de erros