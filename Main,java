import java.util.*;
public class Main
{
	public static void main(String[] args) {
		String s = "aaaabaacd";
		int n = s.length();
		char str[] = s.toCharArray();
		int len = 0;
		int i = 1;
		int lps[] = new int[n];
		lps[0] = 0;
		
		while(i<n)
		{
		    if(str[i]==str[len])
		    {
		        len++;
		        lps[i] = len;
		        i++;
		    }else{
		        if(len==0)
		        {
		            lps[i] = 0;
		            i++;
		        }else{
		            len = lps[len-1];
		        }
		    }
		}
		System.out.println(Arrays.toString(lps));
	}
}
