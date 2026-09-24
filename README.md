# Ayush-project
This is my first Git Repository
<br>
I change here some thing 
<br>
I write some code here
<br>
import java.util.Scanner;

public class LargestElemen_In_Array {

	public static void main(String[] args) {
	
	Scanner sc = new Scanner(System.in);
	System.out.print("enter array size  ");
	int n = sc.nextInt();
	
		int [] a = new int[n];
		 
		System.out.println("enter element  ");
			
		for(int i=0; i<a.length;i++) {
			a[i] = sc.nextInt();
				

			}

		int max = a[0];
		
		for(int i=1; i<a.length;i++) {
			if(a[i]>max) {
				max = a[i];
			
				
			}
		}
		System.out.print("max value is "+max);

	}

}
