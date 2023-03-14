# FibonnaciSeries
Find Fibonnaci Series of given number
public class FibonnaciSeries {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.print("Enter number:");
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int a=0;
		int b=1;
		int c;
//		int i=1;
//		while(i<=n) {
//			i++;
//			c=a+b;
//			System.out.println(c+" ");
//			a=b;b=c;
			
	    for(int i=1;i<=n;i++) {
	    	c=a+b;
	    	System.out.println(c);
	    	a=b;
	    	b=c;
	    	
	    } 
	    System.out.println();

	}

}
