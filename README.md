# swaping-of-values
import java.util.Scanner;
public class Swap{
 public static void main(String[]args)
 {
   int x= 100, y= 200;
   System.out.println("Before Swap");
   System.out.println("x = " + x);
   System.out.println("y = " + y);
   
     int alter = x;
     x=y;
     y=alter;
   
   System.out.println("After Swap");
   System.out.println("x = " + x);
   System.out.println("y = " + y);
    
   }
 }
