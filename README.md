# Java-Coding-Questions
#printing Hollow Square


package pattern;

public class SquareBound {

	public static void main(String[] args) {
		for(int i=0;i<4;i++) {
			for(int j=0;j<4;j++) {
				if(i==0 || j==0 || i==3 || j==3 ) {
					System.out.print("$ ");
					}
				else {
					System.out.print("  ");
				}
				
			}System.out.println();
		}
	}
}

#Printing Triangle Alphabet Pattern



package pattern;

public class PatternChar {

	public static void main(String[] args) 
	{
		for(char c=65;c<91;c++) {
			for(char d=65;d<=c;d++) {
				System.out.print(d + " ");
			}System.out.println();
		}
	}
}
