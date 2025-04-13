# Atividades-de-Loop

#Questao 1
```java
package teste1;

import java.util.Scanner;

/**
 *1. Escreva um algoritmo que leia 30 valores e conte quantos números digitados
são pares, impares e nulos.
 * @author Henrique
 */
public class Teste1 {

    public static void main(String[] args) {

        int cN, n, cPar, cImpar, cNulos;
        Scanner ler = new Scanner(System.in);

        cN = 1;
        cPar = 0;
        cImpar = 0;
        cNulos = 0;

        while (cN <= 30) {
            System.out.println("Digite um número:");
            n = ler.nextInt();
            if(n==0){
                cNulos++;
            }else if(n%2==0){
                cPar++;
            }else{
                cImpar++;
            }
            cN++;
        }
        System.out.println("Quant.Nulos:"+cNulos);
        System.out.println("Quant.Pares:"+cPar);
        System.out.println("Quant.Impares"+cImpar);
    }

}
````
#questao 2
package loopatividades1;

/**
 * Escreva um algoritmo que gere o números de 1000 a 1999 e escreva aqueles que,
 * divididos por 11, dão resto igual a 5.
 *
 * @author Henrique
 */
public class LoopAtividades1 {

    public static void main(String[] args) {
        
        int numero;
        numero=1000;
        
        while(numero<=1999){
            if(numero%11==5){
                System.out.println(numero);;
            }
            numero++;
            
        }

    }

}
#questao 3
```java
package loopatividades1;

import java.util.Scanner;

/**
 * Escrever um algoritmo que lê 10 valores, um de cada vez, e conta quantos
 * deles estão no intervalo [10,20] e quantos deles estão fora do intervalo,
 * escrevendo estas informações.
 *
 * @author Henrique
 */
public class LoopAtividades1 {

    public static void main(String[] args) {

        int valores, valorEntre, valorFora, cD;
        Scanner ler = new Scanner(System.in);

        valorEntre = 0;
        valorFora = 0;
        cD = 1;

        while (cD <= 10) {
            System.out.println("Digite um valor:");
            valores = ler.nextInt();
            if (valores >= 10 && valores <= 20) {
                valorEntre++;
            } else {
                valorFora++;
            }
            cD++;
        }
        System.out.println("valores entre 10 e 20: " + valorEntre);
        System.out.println("Valores fora de 10 e 20: " + valorFora);

    }

}
```
#Questao 4
```java
package loopatividades1;

/**
 * Chico tem 1,50 metro e cresce 2 centímetros por ano, enquanto Zé tem 1,10
 * metro e cresce 3 centímetros por ano. Construa um algoritmo que calcule e
 * imprima quantos anos serão necessários para que Zé seja maior que Chico.
 *
 * @author Henrique
 */
public class LoopAtividades1 {

    public static void main(String[] args) {

        int chico, ze, anos;
        chico=150;
        ze=110;
        anos=0;
        while(ze<=chico){
            chico+=2;
            ze+=3;
            anos++;
        }
        System.out.println("Levara "+anos+" anos para ze ultrapassar a altura de chico");
    }
}
```
#Questao 5
```java

```
