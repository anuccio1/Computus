
import java.util.Scanner;
public class ComputusMain {

/**
 * This main method will ask the user for a year, and output the date of easter for that year
 * @param args default parameter for main
 */
	public static void main(String[] args) {
	
			int year;
			System.out.println("Enter a year:\n");			
			Scanner input = new Scanner(System.in);
			year = input.nextInt();
			
			if(year < 1){
				while(year < 1){
				System.out.println("Invalid Year. \nEnter a year:\n");
				year = input.nextInt();
			}//end while
			}//end if
			
			Computus e = new Computus(year);
			e.EasterDate();
			e.DisplayEaster();
			/*
			e.Eastercounter();			//will run the cycle to count how many times easter occured on each day
			*/
		}

			

	}


