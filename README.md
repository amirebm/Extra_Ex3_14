# Extra_Ex3_14

/*
 Write a program that lets the user guess whether the flip of
a coin results in heads or tails. The program randomly generates an integer 0 or 1,
which represents head or tail. The program prompts the user to enter a guess and
reports whether the guess is correct or incorrect.
 */

package com.personal.Ex3_14;

import java.util.Scanner;

public class EX3_14 {
	
	public static void main(String[] args) {
		
		 int number=0 ;
		 
			 number= (int)(Math.random()*2 ) ;
			 
				
		 Scanner sc = new Scanner(System.in);
			int coin;
			System.out.print
		      ("guess head or tail :  ");
			coin=sc.nextInt();
			if (coin == number)
				System.out.print
			     ("you guess right" + number );
			else
				System.out.print
			     ("you guess wrong" + number );
				
	}

}
