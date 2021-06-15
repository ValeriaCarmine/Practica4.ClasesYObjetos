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
public class Coche {
    String color;
    String modelo;
    String marca;
    int numPuertas;
    int numAsientos;

    public Coche(String color, String modelo, String marca, int numPuertas, int numAsientos) {
        this.color = color;
        this.modelo = modelo;
        this.marca = marca;
        this.numPuertas = numPuertas;
        this.numAsientos = numAsientos;
        
        System.out.println("Usted compro un nuevo coche "+marca);
    }
    
    
    public void ensender (String marca){
        System.out.println("El auto "+marca+" esta encendido");
    }
    public void apagar (String modelo){
        System.out.println("El auto "+modelo+" esta apagado");
    }
    public void avanzar (int numPuertas){
        System.out.println("Las "+numPuertas+" puertas estan cerradas, auto en movimiento");
    }
    public void frenar (){
        System.out.println("Auto parado");
    }
    public void girar (){
        System.out.println("Girando auto");
    }

   
}
