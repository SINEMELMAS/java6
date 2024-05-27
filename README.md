# java6
package lab1;

public class Q8{

	public static void main(String[] args) {

		 int Rabbits = 1042;
	      int Birds = 2272;
	      double reproducedRabbits = 0.038; 
	      double reproducedBirds = 0.012; 
	      int year = 0;

	        while (Rabbits <= Birds) {
	            Rabbits += Rabbits * reproducedRabbits;
	            Birds += Birds * reproducedBirds;
	            year++;
	        }

	        System.out.println("In " + year + " years, there will be more rabbits than birds.");
	        
	}
}
