# COMPUTING-Tabla-Mult
/*EJERCICIO: Programa que escribe la tabla de multiplicar de un número introducido por teclado. 
El programa debe tener un método que recibe como parámetro un número entero y muestra la tabla de 
multiplicar de dicho número.*/

import java.io.BufferedReader;
import java.io.IOException;
import java.io.InputStreamReader;
public class Main {
    public static void main(String[] args) throws IOException {
        {
            int x ,m;
            BufferedReader in = new BufferedReader(new InputStreamReader(System.in));
            System.out.println("Ingrese un número: ");
            x =Integer.parseInt(in.readLine());
            System.out.println("La tabla de multiplicar és del: " + x);
            m=mult(x);
        }
        }
    private static int mult(int x) {
            for(int i = 1; i<=10; i++){
                System.out.println(x+"*"+i+"="+x*i);
        };
        return x;
    }
}
