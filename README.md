# 👨‍💻 Desafio de Contagem em Java

Este projeto é um exemplo simples de uma aplicação Java desenvolvida na IDE Eclipse usando a versão 22 do Java. O objetivo é realizar uma contagem de números com base em dois parâmetros fornecidos pelo usuário.

Este projeto é um [desafio](https://github.com/digitalinnovationone/trilha-java-basico/tree/main/desafios/controle-fluxo) proposto pelo expert Gleyson Sampaio na trilha de Java Básico na plataforma [DIO](https://www.dio.me/).


## 💻 Tecnologia utilizada no projeto:
<div>
   <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
</div>


## 📂 Estrutura do Projeto

O projeto contém os seguintes arquivos:

1. **Contador.java**: Este é o arquivo principal que contém a lógica de leitura dos parâmetros, validação e execução da contagem.

2. **ParametrosInvalidosException.java**: Este arquivo define uma exceção personalizada que é lançada quando os parâmetros fornecidos pelo usuário não seguem a regra de que o segundo parâmetro deve ser maior que o primeiro.


## 💻 Funcionamento

### Contador.java

O arquivo `Contador.java` realiza as seguintes etapas:

1. **Leitura dos Parâmetros**: O programa solicita ao usuário que insira dois números inteiros. O primeiro número é armazenado na variável `parametroUm` e o segundo em `parametroDois`.

2. **Validação dos Parâmetros**: Após a leitura dos parâmetros, o programa chama o método `contar`, que valida se `parametroUm` é maior que `parametroDois`. Se esta condição for verdadeira, uma exceção do tipo `ParametrosInvalidosException` é lançada.

3. **Contagem**: Caso os parâmetros sejam válidos, o programa calcula a diferença entre `parametroDois` e `parametroUm` e realiza uma contagem do número 1 até essa diferença, imprimindo cada número no console.

### ParametrosInvalidosException.java

O arquivo `ParametrosInvalidosException.java` define uma exceção personalizada que é utilizada para sinalizar que os parâmetros inseridos pelo usuário são inválidos. Esta exceção é lançada especificamente quando o primeiro parâmetro é maior que o segundo.


## 👨‍🔧 Como Executar

1. Abra o projeto na IDE Eclipse.

2. Execute o arquivo `Contador.java`.

3. Insira os dois parâmetros quando solicitado:
    - O primeiro parâmetro deve ser um número inteiro.
    - O segundo parâmetro deve ser um número inteiro maior que o primeiro.

4. Se os parâmetros forem válidos, o programa imprimirá uma contagem do número 1 até a diferença entre os dois parâmetros.

5. Se o segundo parâmetro for menor que o primeiro, uma exceção será lançada e uma mensagem de erro será exibida.


## 👨‍🏫 Exemplo de Uso

Suponha que o usuário insira os seguintes valores:

- Primeiro parâmetro: `3`
- Segundo parâmetro: `7`

O programa irá imprimir:

Iniciando a contagem do resultado da subtração dos dois parâmetros:

   ```sh
      Imprimindo o número 1
      Imprimindo o número 2
      Imprimindo o número 3
      Imprimindo o número 4
   ```


## 🛑 Tratamento de Erros

Se o usuário inserir um primeiro parâmetro maior que o segundo, o programa exibirá a seguinte mensagem de erro:

```sh
O segundo parâmetro deve ser maior que o primeiro
```


## ☕ Versão do Java

Este projeto utiliza a versão 22 do Java.


## 📝 Requisitos

- **Java 22** ou superior.
- **IDE Eclipse** (opcional, mas recomendada para fácil navegação e execução).


## 👨‍💻 Expert

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://avatars.githubusercontent.com/u/44624583?v=4"
    />
    <p>&nbsp&nbsp&nbspMarcos Winther<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/MarcosWinther">
    GitHub</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/marcoswinthersilva/">LinkedIn</a>
    </p>
</p>
<br/><br/>

---

⌨️ com 💜 por [Marcos Winther](https://github.com/MarcosWinther)
