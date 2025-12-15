# Aula 03

## Meu Nome:

### Visão Geral
Descrição: Perguntar o nome e exibir na tela.

---

## Objetivos

1. Perguntar o nome do usuário 
2. Ler o nome do usuário 
3. Devolver o nome do usuário com saudação

## Funcionalidades principais

### 1. Entrada de dados (nome)
Descrição: Perguntar o nome do usuário

    Input

    ```Portugol
    Escreva("Qual o seu nome?")
    ```

### 2. Coletar nome para exibição
Descrição: Salvar nome na memória para exibição

    Save Input

    ```Portugol
    Escreva("Qual o seu nome?")
    Leia(nome)
    ```



### 3. Devolver o nome do usuário com saudação  
Descrição: Exibir o nome do Usuário 
    
    Output

    ```Portugol
    Escreva("Muito prazer, ", nome)
    ```



## Soma Numérica e Média:

### Visão Geral
Descrição: Efetuar a soma entre dois valores e exibir na tela o resultado da soma; em um upgrade da mesma aplicação calcular a média entre os números e exibir na tela.

---

## Objetivos

1. Efetuar soma entre dois números
2. Calcular média dos dois números somados
3. Exibir soma e média na tela

---

## Funcionalidades principais

### 1. Entrada de dados (Dois números)
Descrição: Coleta de números para soma.

    Input

    ```Portugol
    Escreva("Informe um numero: ")
    Leia(n1)
    Escreva("Informe outro número: ")
    Leia(n2)
    ```

### 2. Calculo de valores (Soma/Média)
Descrição: Calculos de valores, soma e média.

    Calculo (Soma)

    ```Portugol
    s <- n1+n2
    ```

    Calculo (Soma/Média)

    ```Portugol
    m <- (n1+n2)/2
    ```
    
### 3. Exibição de resultado (Soma/Média)
Descrição: Exibição de resultados da soma e média dos valores somados, de maneira descritiva.

    Output (Soma)

    ```Portugol
    Escreva("A soma entre ", n1, " e ", n2, " é igual a ", s)
    ```

    Output (Soma/Média)

    ```Portugol
    Escreva("A média entre ", n1, " e ", n2, " é ", m)
    ```

## Conclusão
Aplicação de coleta e armazenamento de dados, calculos com operadores aritméticos.