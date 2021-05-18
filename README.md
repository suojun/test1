# 4일차

package ex.java.input;

public class InputPameter {

	public static void main(String[] args) {
		System.out.println("Length: " + args.length);
		//
		System.out.println( args[0]); 
		System.out.println( args[1]);
		System.out.println( args[2]);
		
		System.out.println( args[0] instanceof String);
		System.out.println( args[1] instanceof String);
		System.out.println( args[2] instanceof String);
		
		int a = Integer.parseInt(args [0]);
		int b = Integer.parseInt(args [1]);
		int c = Integer.parseInt(args [2]);
		
		System.out.println( a + b + c);



	}

}

//  과제
package ex.java.input;

public class EX {

	public static void main(String[] args) {
		int a = 20;
		int b = 35;
		
		System.out.println( 100+ a);
		System.out.println(b%10);
		
		int c = 35;
		int d = 10;
		int e = c%d;
		int f = c/d;
		System.out.println(c + "/" + d +'='  + f + "..."+ e);
		
		
	    int i = 10;
	    int g = 25;
	    int s = 33;
	    int value =  i + g + s;
	    
	    System.out.println("sum : " + value );
	    System.out.println("avg : " + value/3);
	}

}

package ex.java.input;

public class fes {

	public static void main(String[] args) {
		int myAge = 23;
		int teacherAge = 38;
		
		boolean value  = (myAge > 25);
		System.out.println(value);
		
		System.out.println(myAge <= 25);
		System.out.println(myAge == teacherAge);
		
		char ch;
		ch = (myAge > teacherAge)? 't' : 'f';
		
				
		System.out.println(ch);

	}

}
## 5일차


