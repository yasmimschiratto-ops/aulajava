# aulajava

Assuntos abordados durante as aulas de java:
- fundamentos da linguagem java;
- programação Orientada a objetos (POO);
- estrutura de dados;
- collections freamworks;
- tratamento fe excessões;
- JDBC e banco de dados;
- Swing e JavaFX;
- Threads e concorrência;
- APIs REST com Spring boot;
- JPA/Hibernate;
- Arquitetura de Software;
- Clean Code e boas práticas;
- Testes unitárrios com JUnit;
- Padrões de projetos (Design Patterns).

  O que é Java:
  Java é uma linguagem de programação criada para funcionar em diferentes sistemas operacionais.
  A ideia principal do Java é: "Esccreva uma vez e execute em qualquer lugar".
  Preparado o ambiente: Para podemos rodar códigos em Java, são necessárias algumas instalações, como: oracle Java e Visual Studio code.
  Com o ambirnte preparado, os próximos passos são intalat as extensões necessárias e testar se o Java está funcionando.
  A extensão é: Extension Pack for Java. Essa extensão intala junto o surporte Java, o debugger e o autocomplete.
  Para testar se Java está funcionando precisamos: Abrir o terminal do windows (tecla windows + R -> digitar CMD na caixa que abrir)
  Com o terminal aberto digite: Java --version. Se aparecer o número da versão (20, 21, 25 etc) o Java está funcionando corretamente.
  criando um priogama em Java: Abrir o VSCode, abrir uma pasta (Aulajava, por exemplo), criar um novo arquivo com extensão .java (main.Java, por exemplo).
  Ao criar o arquivo, se a extensão estiver instalada corretamente, aparecerá o código: public class main {

  }
  Na sequência precisamos inserir a parte do código onde o Java de fato funciona: public static void main (String [] args) {

  }
  por fim, para finlizar esse programa, precisamos colocar o código que faz mostrar uma mensagem na tela:
   public class main {
    public static void main (String [] args) {
    System.out.println("Olá, mundo!")
  }
  }
  Para executar esse progama há duas alternativa:
  1- Aparecerá um botão run abaixo da public class Main, basta apertar e o resultado aparece no terminal do VSCode
  2- Abrir o prompt de Comando do windows (cmd)-> navegar até a pasta onde o projeto está salvo (cd nome-da-pasta)-> digitar primeiro: Javac main.Java (se o projeto tiver outro nome é preciso digitar esse outro nome) -> pressione Enter -> na próxima linha digite Java main (ou o nome do programa se for diferente)

  Variáveis:
  Variáveis guardam informações na memória.
  Exemplo:
- String nome = "Yasmim";
- int idade = 17;
- double altura = 1.70;
- boolean aluno = true;

  System.out.println(nome);
  System.out.println(idade);
  System.out.println(altura);
   System.out.println(aluno);
