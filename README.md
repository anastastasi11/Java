package com.company;

public class Main {

    public static void main(String[] args) {
        String r = "home schooling";
        int h = 15;
        byte o = 100;
        short q = 20;
        long g = 900000L;
        float a = 10.5f;// b = 15.6f, c = 20.9f, d = 25.1f;
        double e = 15.897;
        char k = '&';
        boolean l = true;
       // System.out.println(a * b + c / d);
    }
    private static float maths1 (float a, float b, float c, float d){
        return a * (b + (c / d));
    }
    private static boolean maths2(int a, int b ) {
       int sum = a*b;
       return sum >=10 && sum <= 20;
    }
    private static void Znak1 (int chislo ){
    if (chislo >= 0){System.out.println ("Положительное");}
    else {System.out.println ("Отрицательное");}
    }
    private static boolean Znak2 (int number ){
        return number<0;
    }
    private static void Name (String n){
        System.out.println ("Hello, " +n + "!");
    }
    private static void Year (int year){
        if ((year%4==0 && year%400==0)|| year%100!=0){
            System.out.println ("Високосный");
        }else  {System.out.println ("Не високосный");}
    }

}

