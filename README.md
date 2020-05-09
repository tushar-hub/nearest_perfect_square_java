// nearest_perfect_square_java
import java.lang.Math; 
import java.util.*;
class A{
static double a;
static double sqr;
static double j;
static double h;
static double l;
static double e;
static double t;
static double u;
static double k;
static double f;

public static void main(String[] args){
	Scanner input=new Scanner(System.in);
	System.out.println("enter the number");
	a=input.nextDouble();
	sqr=(Math.sqrt(a));
	
	j=(Math.floor(sqr));
	h=j*j;
	l=j+1;
	k=j-1;
	f=k*k;
	e=l*l;
	
	u=-(a-e);
    t=(a-h);

	if(u>t && (t!=0)) {
		System.out.println("this is"  +h);
		
	}
	else if(t>u){
		System.out.println(e);
	}
	else if(j==sqr){
		System.out.println("now it will print " +f);
	}
	
	

}
}
