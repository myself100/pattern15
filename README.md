# pattern15

import java.util.Scanner;
public class pattern {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		for(int i=1;i<=n;i++) {
			int k=1;
			for(int j=1;j<=i;j++) {
				if(i%2==0) {
					System.out.print((char)(j+64) + " ");
				}
				else {
					System.out.print(k + " ");
					k++;
				}
			}
			System.out.println();
		}
	}

}

output::                                ////when n is 5
5
1 
A B 
1 2 3 
A B C D 
1 2 3 4 5 
