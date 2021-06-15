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
public class Alumno {
    String nombre;
    int numCuenta;
    int edad;
    float promedio;
    int semActual;

    public Alumno(String nombre, int numCuenta, int edad, float promedio, int semActual) {
        this.nombre = nombre;
        this.numCuenta = numCuenta;
        this.edad = edad;
        this.promedio = promedio;
        this.semActual = semActual;
        
        System.out.println("Bienvenida! "+nombre);
    }
