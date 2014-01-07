SVIPprogram
===========

Java(adding numbers)

public class AddNumbers {
	
	public static void main(String[] args) {

		int sum = 0;	
		for (int i = 0; i <= 1000; i++) {
			if(i%3 == 0){
				sum = sum + (2*i);
			}
			else if(i%5 == 0){
				sum = sum + (2*i);
			}
			else {
				sum = sum + i ;
			}
		}
	     
		System.out.println( " The total sum is" + " : "+ sum );
		
	}

}
