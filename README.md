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
