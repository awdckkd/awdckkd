- š Hi, Iām @awdckkd
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
awdckkd/awdckkd is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.Scanner;
public class EvenOddBitwise
{
   public static void main(String[] args)
   {
      Scanner sc = new Scanner(System.in);
      System.out.print("Please enter a number: ");
      int number = sc.nextInt();
      if((number & 1) == 0)
      {
         System.out.println(number + " is an even number.");
      }
      else
      {
         System.out.println(number + " is an odd number.");
      }
      sc.close();
   }
}
Please enter a number: 28
28 is an even number.
