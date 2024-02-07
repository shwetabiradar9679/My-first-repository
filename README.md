# My-first-repository
This is my first repository
My name is Shweta 
</br>
I am from Karnataka
</br>
import java.util.Scanner;

public class NestedFruit {

	public static void main(String[] args) {
 Scanner sc = new Scanner(System.in);
 System.out.println("Enter fn");
 String fn =sc.nextLine();
 System.out.println("Enter qty");
 int qty = sc.nextInt();
 int cost = 0;
 if (fn.equals("Apple"))
		 {
             if (qty<=20)
             {
            	 cost = qty*5;
            	 System.out.println("The Cost of the Apple is = " + cost);
             }
           else {
       cost = qty*7;
	System.out.println("The cost of the Apple = "+cost);
           }
		 }
	     else if (fn.equals("Kiwi"))
	     {
	    	if (qty<=10)
	    			{
	    		cost = qty*2;
	    		System.out.println("The cost of the Kiwi = "+cost);
	    			}
	    	else if ((qty>=10)&&(qty<=25))
	    		{
	    				cost = qty*4;
	           System.out.println("The cost of the Kiwi = "+cost); 
	    			}
	    	else {
	    		cost=qty*6;
	    		System.out.println("The cost of the Kiwi = "+cost);
	    				
	    		}
	    	}
	     else if (fn.equals("Banana"))
	     {
	    	 if (qty<=100)
	    	 {
	    		 cost=qty*3;
	 			System.out.println("The cost of the Banana = "+cost);
	    	 }
	    	 else
	    	 {
	    		 cost=qty*4;
	    		 System.out.println("The cost of the Banana = "+cost);
	    	 }
	     }
	}
	    

}
