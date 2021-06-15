# Practica4.ClasesYObjetos
POO/Practica4. Clases Y Objetos

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package poop4;

/**
 *
 * @author Optiplex 780
 */
public class POOP4 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Punto punto1 = new Punto();
        punto1.imprimePunto();
        punto1.x= 7;
        punto1.y= 2;
        punto1.imprimePunto();
        
        Punto punto2 = new Punto(9,5);
        punto2.imprimePunto();
        /*********************************************************/
        Perro perro1 = new Perro("Chihuahua"); 
        perro1.ladrar();
        
        Perro perro2 = new  Perro("Yeontan", "Pug");
        perro2.dormir();
        /*********************************************************/
        
        Alumno miAlumno = new Alumno ("Dana",317345153,19,9.99f,4);
        System.out.println(miAlumno);
        miAlumno.estudiar();
        miAlumno.leer("Harry Potter");
        miAlumno.aprobar("POO");
        
        /*****************************EJERCICIO********************************/
        Coche micoche = new Coche ("Rosa","Genesis GV80","Hyundai",4,6);
        micoche.apagar("Genesis GV80");
        micoche.avanzar(6);
        micoche.ensender("Hyundai");
        micoche.frenar();
        micoche.girar();
    }

    public POOP4() {
    }
    
}
