# Length-of-string
import java.util.*;
public class Length
{
  public static void main(String[] args) 
  {    
        Scanner sc=new Scanner(System.in);    
        int count = 0,i=0;    
        System.out.print("Enter a String:");
		String str = sc.nextLine();
		while(i < str.length())
		{
			if(str.charAt(i) != ' ') 
			{
				count++;
			}
			i++;
		}		
		System.out.println(" Total Number of Characters  =  " + count);        
    }      
}
