# Desafio Conrole de Fluxo - DIO Bootcamp (Bradesco)

Este projeto foi desenvolvido como parte do bootcamp Java da DIO em parceria com o Bradesco.  
O programa recebe dois números inteiros como entrada e imprime uma contagem com base na diferença entre eles.

## 💻 Sobre o Projeto

O exercício propõe a criação de um contador que imprime valores sequenciais a partir da diferença entre dois parâmetros fornecidos pelo usuário.  
Caso o segundo parâmetro seja menor que o primeiro, uma exceção personalizada é lançada.

## 🚀 Como Executar

1. **Clone o repositório ou copie o código.**
2. **Compile o arquivo Java:**

```bash
javac Contador.java
```

3. **Execute o programa:**

```bash
java Contador
```

4. **Digite os dois números quando solicitado.**

## 🧪 Exemplo de Uso

```
Digite o primeiro parâmetro  
2  
Digite o segundo parâmetro  
5  
Imprimindo número 1  
Imprimindo número 2  
Imprimindo número 3  
```

Se o segundo parâmetro for menor que o primeiro:

```
Digite o primeiro parâmetro  
5  
Digite o segundo parâmetro  
2  
O segundo parâmetro deve ser maior que o primeiro.
```

## 📚 Conceitos Utilizados

- Manipulação de entrada com `Scanner`
- Lançamento e tratamento de exceções
- Estrutura de repetição `for`
- Criação de método auxiliar (`contar`)
- Classe de exceção personalizada (`ParametrosInvalidosException`)
