import java.util.*;
public class Main
{
  public static void main (String args[])
  {
    Scanner sc = new Scanner (System.in);
      System.out.println (" Enter 1st Number:-");
    int num1 = sc.nextInt ();
      System.out.println (" Enter 2st Number:-");
    int num2 = sc.nextInt ();
      System.out.println (" Enter 3st Number:-");
    int num3 = sc.nextInt ();
    
    if(num1>num2&&num1>num3)
    {
        System.out.println(num1+"This number is Greater");
    }
    else if(num2>num1&&num2>num3)
    {
        System.out.println(num2+"This numer is Greater");
    }
    else
    {
    System.out.println(num3+" This number is Greater");  
    }
  }
}
