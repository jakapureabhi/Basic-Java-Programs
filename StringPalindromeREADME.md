# Basic-Java-Programs
# To check whether the given String is Palindrome or not.
# Palindrome:-A String is called a palindrome string if the reverse of that string is the same as the original string. For example, radar .

public class PalindromeString {
	public static void main(String args[])
	{
		String s="madam";
		String org_s=s;
		String rev="";
		int len=s.length()-1;
		for(int i=len;i>=0;i--)
		{
			rev=rev+s.charAt(i);
			
		}
		System.out.println(s);
		System.out.println(rev);
		if(s.equals(rev))
		{
			System.out.println("the string is palindrome ");
		}
		else
		{
			System.out.println("the string is not palindrome ");
		}
	}
	
	
}
