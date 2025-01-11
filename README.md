# sum-of-odd-numbers
Program to display sum of odd numbers from 1-100 Java.txt
public class SumOfOddNumbers {
public static void main(String[] args) {
int sum = 0;
for (int i = 1; i <= 100; i += 2) {
sum += i;
}
System.out.println("Sum of odd numbers between 1 and 100: " + sum);
}
}
Output:
Sum of odd numbers between 1 and 100: 2500
[Program finished]
