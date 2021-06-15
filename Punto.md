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
public class Punto {
    int x;
    int y;

    public Punto() {
    }

    public Punto(int x, int y) {
        this.x = x;
        this.y = y;
    }
    
    
    
    public void imprimePunto(){
        System.out.println("Coordenadas del punto x="+x+" y="+y);
    }
}
