# calculadora
package calculadora3;
import java.util.*;

public class Calculadora3 {


    public static void main(String[] args) {
Scanner sc= new Scanner (System.in);
        int b,c, sol, r=0;
        do{
        System.out.println("Ingresa el primer numero");
        b=sc.nextInt();
        System.out.println("Ingresa el segundo numero");
        c=sc.nextInt();       
        System.out.println("Elige una opcion de calculo\n 1.Calcular la suma\n "
                + "2.Calcular la resta\n "
                + "3.Calcular la multiplicacion\n "
                + "4.Calcular la division\n"
                + " 5.Modulo\n"
                + " 6 Salir");
       sol=sc.nextInt();
        switch(sol){
           case 1:
           System.out.println("El resultado de la suma es\t" +(b+c));  
           break;
           case 2:
           System.out.println("El resultado de resta es\t" +(b-c));
           break;
           case 3:
           System.out.println("El resultado de multiplicacion es\t" +(b*c));
           break;
           case 4:
           System.out.println("El resultado de la division es\t" +(c/b));
           break;
           case 5:
               System.out.println("El resultado del modulo es\t"+(b%c));
           break;
           case 6:
               System.exit(0);
           break;
           default:
               System.out.println("Eligiste una opcion incorrecta");
       }
System.out.println("¿Deseas volver? 1.-Si, 2.-No");
r=sc.nextInt();
            System.out.println();
        }while(r==1);
    }
    
}
