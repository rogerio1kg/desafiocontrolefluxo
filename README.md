
## Desafio Controle de Fluxo - DIO - Santander Backend - 2024

Este repositório contém o código-fonte para o desafio "Controle de Fluxo", que visa aplicar os conceitos de controle de fluxo (laços de repetição e estruturas condicionais) na linguagem de programação Java. O desafio consiste em desenvolver um programa que recebe dois números inteiros como entrada via terminal e imprime no console os números incrementados entre o menor e o maior valor, inclusive. Caso o primeiro número informado seja maior que o segundo, uma exceção personalizada ParametrosInvalidosException deve ser lançada.



## Pré-requisitos

- Ter o IDE IntelliJ Community Edition instalado e configurado ou IDE de sua preferência.
- Ter conhecimento básico da linguagem de programação Java, incluindo conceitos de controle de fluxo (laços de repetição e estruturas condicionais).


## Instruções

    1. Clone este repositório para o seu computador local.
    2. Abra o projeto no IntelliJ Community Edition.
    3. Execute a classe Contador passando dois números inteiros como argumentos.
    4. Observe a saída do programa no console.

### Exemplo de execução

```bash 
Contador 12 30
```
### Saída esperada 
```bash 
Imprimindo o número 13
Imprimindo o número 14
...
Imprimindo o número 29
Imprimindo o número 30
```

### Execução
```bash 
Contador 30 12
```

### Saída esperada

```bash 
Exception in thread "main" ParametrosInvalidosException: O segundo parâmetro deve ser maior que o primeiro
```

## Observações

- A classe **```ParametrosInvalidosException```** é uma exceção personalizada que representa um erro de negócio no sistema.
- O código do programa foi desenvolvido com foco em legibilidade e clareza, utilizando comentários para explicar o funcionamento das instruções.
- Este desafio pode ser utilizado como base para aprimorar seus conhecimentos em controle de fluxo em Java.




## Tecnologias Utilizadas

 - Linguagem de programação - Java
 - IDE - IntelliJ IDEA Community Edition 2024.1
 - Git 
 


## Licença

[MIT](https://choosealicense.com/licenses/mit/)

