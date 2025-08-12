public class palindrome number {
public static void main (string[] args) {
 scanner sc = new scanner (system.in);

 system.out.print("Enter a number : ")
 int num = sc.nextInt();
 int reversed = 0;
 while (num !=0)
 {
  int digit = num % 10;
  reversednum = reversed num * 10 + digit;
  num /=10
  }
  if (originalNum == reversednum) {
    system.out.println(originalNum + "is a palindrome.");
    }
    else { system.out.println(originalNum + "is not a palindrome.");
    }
    sc.close();
    }
}
