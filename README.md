package com.company;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter length of the sides and height of the Equilateral triangle:");
        double lengthOfSides = input.nextDouble();
        //area of triangle.
        double areaOfTriangle = lengthOfSides * lengthOfSides * (Math.sqrt(3) / 4);
        System.out.println("Enter height of the triangle:");
        double height = input.nextDouble();
       //volume of triangle.
        double volumeOfTriangle = areaOfTriangle * height;
        System.out.println("The area of triangle is " + areaOfTriangle +
                " & the volume is " + volumeOfTriangle);
    }
}
