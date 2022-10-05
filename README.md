# farming-program
farming program
package  farmprogram;
public class main {

	public static void main(String[] args) {
		mesurement();

	}
	// method to check crop health
	public static void mesurement()
	//shows current salt value
	{ int saltlevel = 100;
	// checks to see if specified value os considured safe or dangourose
		if(saltlevel < 100)
		
			System.out.print("soil safe");
		
		else if (saltlevel > 100)
		
			System.out.print("safe but performance reduced");
		
		//else if (saltlevel < 250 )
		
		//	System.out.print("safe but performance reduced");
		
		else
			System.out.print("crop died");
	}
	
	// i did some googling to get the values used, this just applies to weat. we can use thsi structure for oher crops and implimnt a menu system for the biggur virsion.
	// this is just sudo code
}
