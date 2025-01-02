# array-take-set-of-marks-give-grade

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	 int n;
    Scanner s=new Scanner(System.in);
      n=s.nextInt();
      int a[]=new int[n];
      for(int i=0;i<=n;i++)
      {
           a[i]=s.nextInt();
        
          if(a[i]>=90)
          {
              System.out.println("A");
          }
          else if(a[i]>=70)
          {
              System.out.println("B");
              
          }
          else if(a[i]>=40)
          {
              System.out.println("C");
              
          }
          else
          {
              System.out.println("F");
          }
      }
	}
}
