# Skillrack
import java.util.*;
public class Hello {

    public static void main(String[] args) {
		//Your Code Here
		Scanner sc=new Scanner(System.in);
		long n=sc.nextLong();
		long c=0;
		while(n>0) {
		    long r1=n%10;
		    long r2=(n/10)%10;
		    if(r1-r2!=1&&r2-r1!=1) {
               c++;
		    }
		  n=n/10;
		}
		if(c!=0) {
		    System.out.print("no");
		}
		else {
		    System.out.print("yes");
		}

	}
}
