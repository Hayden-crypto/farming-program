# farming-program
farming program
package  farmprogram;
public class main {

	public static void main(String[] args) {
		mesurement();

	}
	
	// mechine learning code to access weather data goes here
	
	// method to check crop health
	public static void mesurement()
	//shows current salt value
	{ int saltlevel = 100;
	// checks to see if specified value is considered safe or dangerous
		if(saltlevel < 100)
		
			System.out.print("soil safe");
		
		else if (saltlevel > 100)
		
			System.out.print("safe but performance reduced");
		
		//else if (saltlevel < 250 )
		
		//	System.out.print("safe but performance reduced");
		
		else
			System.out.print("crop died");
	}
	
	//Values used in Pseudocode are obtained online these just appliy to weat. we can use this structure for oher crops and implimnt a menu system for the updated virsion.
}
