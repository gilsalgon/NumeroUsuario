# NumeroUsuario
package numerousuario;

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;

/**
 *
 * @author Gsalazar
 */
public class NumeroUsuario {

    /**
     * @param args the command line arguments
     * @throws java.io.IOException
     */
    public static void main(String[] args) throws IOException {
        
        int a;//declarar primera variable he igualar a 5
        int b;//declarar segunda variable he igualar a 7
        int c;// declarar tercera variable he igualar a 3
        int resultado;// declarar variable resultado
        System.out.println("DIGITE PRIMER NUMERO:  ");//solicite el primer numero
        BufferedReader leer1= new BufferedReader(new InputStreamReader(System.in));
        a = Integer.parseInt(leer1.readLine());
        System.out.println("DIGITE EL SEGUNDO NUMERO:  "); //solicite el segundo numero
        BufferedReader in2 = new BufferedReader(new InputStreamReader(System.in));
        b = Integer.parseInt(in2.readLine());
        System.out.println("DIGITE EL TERCER NUMERO:  "); //solicite el tercer numero
        BufferedReader in3= new BufferedReader(new InputStreamReader(System.in));
        c = Integer.parseInt(in3.readLine());
        resultado = a+b+c; //igualar resultado con las tres variables
        System.out.println("LA SUMA DE ES :  "+ resultado);
         if(a==5 && b==7 && c==3)     
           System.out.println("los numeros son correctos");
        else
            System.out.println("los numeros son incorrectos");   
    }
  
    }

