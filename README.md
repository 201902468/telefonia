/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package telfonia;

import java.util.Scanner;

/**
 *
 * @author LAB-A2
 */
public class Telfonia {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
       Scanner entrada = new Scanner(System.in);
        double mensajes_texto=200;
        double saldoDisponible= 800 ;
        double datos_navegacion = 512;
        double transferir_saldo = 0;
        double pedir_saldo = 0;
        int resp = 0;
        
        while(resp != -1){
            System.out.println("---- Bienvenido usuario de  ---- ");
            System.out.println(" 1. Consulta de saldo  "); 
            System.out.println(" 2. Mensajes de texto ");
            System.out.println(" 3. Datos de Navegacion");
            System.out.println(" 4. Transferir Saldo ");
            System.out.println(" 5. Pedir saldo");
            System.out.println(" Que desea realizar... ? ");
            resp = entrada.nextInt();
        
                switch(resp){
                case 1:
                    System.out.println("");
                    System.out.println("----------------------------------------");
                    System.out.println("Mensajes de Texto "+mensajes_texto);
                    System.out.println("Datos de Navegacion... "+datos_navegacion);
                    System.out.println("Tranferir Saldo...   ("+transferir_saldo+")");
                    System.out.println("----------------------------------------");
                    System.out.println("Saldo disponible...   "+saldoDisponible);
                    System.out.println("----------------------------------------");
                    System.out.println("Pedir saldo....  "+pedir_saldo);
                    break;
                    case 2: 
                    System.out.println("");
                    System.out.println("Mensajes de Texto "+mensajes_texto);
                    System.out.println("Saldo disponible   "+saldoDisponible);
                    System.out.println("Ingrese el saldo a transferir "+transferir_saldo);
                    System.out.println(" Pedir saldo ");
                    
                    double saldo = entrada.nextDouble();
                    
                    
                     
                        
                    }
                    }
                    
            
                
                    
                }
    

        }
}
