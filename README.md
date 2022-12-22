  package supriya11;

import java.util.Scanner;

public class NaturalNumber {

	public static void main(String[] args) {
		int sum=0;
		
		System.out.println("Enter a number");
		Scanner sc=new Scanner(System.in);
		int num=sc.nextInt();
		for(int i=0;i<=num;i++)
		{
			sum=sum+i;
		}
		System.out.println("sum is"+sum);

	}

}
