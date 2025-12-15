# Aula 04

## Comparador Númerico:

### Visão Geral
Descrição: Coletar dois valores, compara - los e exibir a comparação na tela de maneira descritiva.

## Objetivos

1.  Colerar dois números e comparar os dois números coletados
2.  Devolver a comparação dos números coletados de maneira descritiva

---

## Funções principais

### 1. Entrada de dados (Dois números)
Descrição: Coleta de dois números para comparação

    Input

    ```Portugol
    Escreva("Cadastre 1o número: ")
    Leia(n1)
    Escreva("Cadastre 2o número: ")
    Leia(n2)
    ```

### 2. Comparar os dois valores coletados
Descrição: Calcular a diferença dos valores com operadores relacionais
    
    Calculo relacional

    ```Portugol
    Se (n1>n2) entao
        maiornumero <- n1
        menornumero <- n2
    SeNao
        Se (n1<n2) entao
            maiornumero <- n2
            menornumero <- n1
        SeNao
    FimSe
    ```

### 3. Devolver valores comparados
Descrição: Devolução de comparação para o úsuario
    
    Output

    ```Portugol
    Se (n1=n2) entao
        Escreva("Os numeros ", n1, " e ", n2, " são iguais!")
    SeNão
        Escreval(maiornumero, " é o meior número")
        Escreva(menornumero, " é o menor número")
    FimSe