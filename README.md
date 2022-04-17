# Basic-Java-Programs
# Average Program in an array 

public class arraverage 
{
public static void main(String args[])
{
	int a[]= {1,2,3,4,6};
	int sum=0 ,average=0;
	for( int i=0;i<a.length;i++)
	{ 
		sum=sum+a[i];
		average= (sum/a.length);
	}
	System.out.println("sum of array is:"+sum );
	System.out.println("Average of array is:"+average );
  
}
}
