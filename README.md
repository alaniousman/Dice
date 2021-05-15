package com.ALSpace;

import java.sql.SQLOutput;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter Dice Type : D-");
        byte diceType = scan.nextByte();
        int result = (int) (Math.random()*diceType+1);
        System.out.println(result);
    }
}
