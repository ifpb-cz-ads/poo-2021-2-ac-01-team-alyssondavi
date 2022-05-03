1- A JVM que permite a portabilidade do código Java, isso ocorre porque todo código Java é compilado para um formato intermediário, o bytecode. Esse formato é então interpretado pela JVM. Assim não precisamos nos preocupar onde ela será executada.

2- O JRE é tudo aquilo que o usuário precisa instalar para que seja possível executar aplicações Java. É o JDK é o que o desenvolvedor precisa para construir as suas aplicações Java.

3- Arquivo Questao3.java

4- Ocorreu o erro abaixo:
Error: Could not find or load main class Questao3
Caused by: java.lang.ClassNotFoundException: Questao3

5- Compilou sem problemas, porém ccorreu o erro abaixo ao executar, porque não tinha método main: //trocamos o metodo 'main' pelo 'start'
Error: Main method not found in class Questao3, please define the main method as:
public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application

6- Arquivo Questao6.java

7- Ocorreu o erro abaixo ao compilar:
Questao6.java:1: error: class, interface, enum, or record expected
CLASS QUESTAO6 {
^
Questao6.java:4: error: class, interface, enum, or record expected
SYSTEM.OUT.PRINT("PALMEIRAS");
^
Questao6.java:5: error: class, interface, enum, or record expected
}
^
3 errors

8- O arquivo compilou, porem teve um erro na hora de executar:

Error: Could not find or load main class Questao8
Caused by: java.lang.ClassNotFoundException: Questao8
