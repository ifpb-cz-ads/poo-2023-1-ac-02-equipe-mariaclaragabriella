Questão 1. 
Em outras linguagens de programação compiladas como C e Pascal, o código-fonte quando é compilado se torna num executável que apenas irá funcionar no sistema operacional no qual foi compilado o programa. Para evitar esse tipo de situação, a linguagem Java possui a Máquina Virtual Java (JVM) que tem como função compilar o formato intermediário (bytecode) que é gerado quando o código-fonte em Java é compilado. Assim, como o código de um programa em Java sempre será transformado em bytecode e depois interpretada pela JVM, não é necessário se preocupar como o código será executado em sistemas operacionais diferentes.


Questão 3. 
public class PrimeiroPrograma {
    public static void main(String[] args) {
        System.out.print("Terminei a primeira aula com um programa Java!");
    }
}

Questão 4.
Apareceu o seguinte erro no terminal:
"Erro: Não foi possível localizar nem carregar a classe principal PrimeiroPrograma
Causada por: java.lang.ClassNotFoundException: PrimeiroPrograma"

Questão 5.
Apareceu o seguinte erro no terminal:
"Erro: o método main não foi encontrado na classe PrimeiroPrograma; defina o método main como:
   public static void main(String[] args)
ou uma classe de aplicativo JavaFX deve expandir javafx.application.Application"
