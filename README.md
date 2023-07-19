# ChineseZodiac

package chinesezodiac;

import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		
		int year,remain;
		
		Scanner input = new Scanner(System.in);
		
		System.out.println("Enter the year you were born:");
                year = input.nextInt();
		
		remain = year%12;
		
		if (remain == 0) {
			System.out.println("Your Chinese Zodiac is: Monkey");
		}
		
		else if (remain == 1) {
			System.out.println("Your Chinese Zodiac is: Rooster");
		}

		else if (remain == 2) {
			System.out.println("Your Chinese Zodiac is: Dog");
		}

		else if (remain == 3) {
			System.out.println("Your Chinese Zodiac is: Pig");
		}

		else if (remain == 4) {
			System.out.println("Your Chinese Zodiac is: Mouse");
		}

		else if (remain == 5) {
			System.out.println("Your Chinese Zodiac is: Ox");
		}

		else if (remain == 6) {
			System.out.println("Your Chinese Zodiac is: Tiger");
		}

		else if (remain == 7) {
			System.out.println("Your Chinese Zodiac is: Bunny");
		}

		else if (remain == 8) {
			System.out.println("Your Chinese Zodiac is: Dragon");
		}

		else if (remain == 9) {
			System.out.println("Your Chinese Zodiac is: Snake");
		}

		else if (remain == 10) {
			System.out.println("Your Chinese Zodiac is: Horse");
		}

		else if (remain == 11) {
			System.out.println("Your Chinese Zodiac is: Sheep");
		}

	}

}
