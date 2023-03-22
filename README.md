Questão 1. <br>
Em outras linguagens de programação compiladas como C e Pascal, o código-fonte quando é compilado se torna num executável que apenas irá funcionar no sistema operacional no qual foi compilado o programa. Para evitar esse tipo de situação, a linguagem Java possui a Máquina Virtual Java (JVM) que tem como função compilar o formato intermediário (bytecode) que é gerado quando o código-fonte em Java é compilado. Assim, como o código de um programa em Java sempre será transformado em bytecode e depois interpretada pela JVM, não é necessário se preocupar como o código será executado em sistemas operacionais diferentes.

Questao 2.

O JRE, ou ambiente de execução Java, é responsável por executar os códigos desenvolvidos em Java. Ele contém uma máquina virtual Java, as bibliotecas e pacotes básicos da linguagem, como o lang, que contém as principais funcionalidades que conhecemos. Já o JDK, ou kit de desenvolvimento Java, é um pacote que pode ser utilizado para desenvolver código em Java. O JDK é composto por compilador, depurador e pelo próprio JRE, o que faz com que seu espaço de armazenamento precise ser maior.

Questão 3. <br>
public class PrimeiroPrograma { <br>
public static void main(String[] args) { <br>
System.out.print("Terminei a primeira aula com um programa Java!"); <br>
} <br>
} <br>

Questão 4. <br>
Apareceu o seguinte erro no terminal: <br>
"Erro: Não foi possível localizar nem carregar a classe principal PrimeiroPrograma <br>
Causada por: java.lang.ClassNotFoundException: PrimeiroPrograma"

Questão 5. <br>
Apareceu o seguinte erro no terminal: <br>
"Erro: o método main não foi encontrado na classe PrimeiroPrograma; defina o método main como: <br>
public static void main(String[] args) <br>
ou uma classe de aplicativo JavaFX deve expandir javafx.application.Application"

Questão 7.

O código não compilou e aconteceram vários erros de sintaxe, como o não reconhecimento do pacote e da declaração da classe.

Questao 8.

Ocorre um erro de compilação seguido da advertência que o tipo público NomeTime, a classe, deve ser definido em seu prórpio arquivo. Isso ocorre pelo fato de que para que uma classe seja efeti
