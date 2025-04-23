# evenodd1
import java.util.Scanner;
class A{
    public static void main(String args[])
    {  int a,i;
         Scanner x=new Scanner(System.in);
              System.out.println("Enter the first data");
               a=x.nextInt();
          for(i=0;i<=a;i++)
          {
              if(i%2==0)
              {
                      System.out.println("Your output is even" +i); 
              }
              else {
                    System.out.println("Your output is odd " +i);
              }
          }
          
   
        
    }
}
