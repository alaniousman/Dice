package com.ALSpace;
import java.util.Scanner;
import java.util.Random;
public class Main {


            public static void main(String arg[])
            {
                Scanner scan = new Scanner(System.in);   //Initialize Scanner
                System.out.print("Enter Dice Type: D-"); //Intro Message
                Byte diceType = scan.nextByte();         //Allows the input of dice number
                int result = (int)(Math.random()*diceType+1); //Randomizes dice number creating a result
                System.out.println(result);//Prints out "result"

            }
        }
