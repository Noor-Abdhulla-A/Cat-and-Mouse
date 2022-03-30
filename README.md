# Cat-and-Mouse
# Hackerrank Problem Solution in java

import java.util.Scanner;

public class CatandMouse {
	
		

	public static void main(String[] args) {
       Scanner sc = new Scanner(System.in);
       int q = sc.nextInt();
       for (int i = 0; i < q; i++) {
		
       int x = sc.nextInt();
       int y = sc.nextInt();
       int z = sc.nextInt();
       int d1 = 0;
		int d2 =0;
		
		d1 =Math.abs (x - z);
		d2 =Math.abs (y - z);
		if(d1 < d2) {
			System.out.println("Cat A");
		}
		else if(d1 > d2) {
			System.out.println("Cat B");
		}
		else  {
			System.out.println("Mouse C"); 
		}
	}
   }
       
}	 
	
