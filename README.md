SUM OF ODD NUMBERS BETWEEN 1 TO 100

public class SumOfOddNumbers {
    public static void main(String[] args) {
        int sum = 0; // Initialize sum to 0

        for (int i = 1; i <= 100; i++) { // Loop through all numbers from 1 to 100
            if (i % 2 != 0) { // Check if the number is odd
                sum += i; // Add the odd number to the sum
            }
        }

        System.out.println("The sum of odd numbers between 1 and 100 is: " + sum);
    }
}

O/P

The sum of odd numbers between 1 and 100 is: 2500

