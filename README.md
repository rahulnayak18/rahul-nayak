#
import java.util.Scanner;
public class calculator 
{
  public static void main(String[] args) 
	{
	     int num1;
	     int num2;
	     String operation;
	     Scanner sc=new Scanner(System.in);
	     System.out.println("enter the first number:");
	     num1=sc.nextInt();
	     System.out.println("enter the second number:");
	     num2=sc.nextInt();
	     
	     Scanner st=new Scanner(System.in);
	     System.out.println("enter the operation");
	     operation=st.next();
	     if(operation.equals("+"))
	     {
	    	 System.out.println("output is "+(num1+num2));
	     }
	     else if(operation.equals("-"))
	     {
	    	 System.out.println("output is "+(num1-num2));
	     }
	     else if(operation.equals("*"))
	     {
	    	 System.out.println("output is "+(num1*num2));
	     }
	     else  if(operation.equals("/"))
	     {
	    	 System.out.println("output is "+(num1/num2));
	     }
	     else
	     {
	    	 System.out.println();
	     }
	}
	

}
