import java.util.Scanner;
import java.math.BigInteger;

public class fibonacci {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);

        System.out.print("Enter how many Fibonacci numbers you want: ");
        int n = input.nextInt();

        BigInteger first = BigInteger.ZERO;
        BigInteger second = BigInteger.ONE;

        if (n <= 0) {
            System.out.println("Please enter a number greater than 0.");
            return;
        }

        for (int i = 1; i <= n; i++) {
            System.out.print(first + " ");

        BigInteger next = first.add(second);
        first = second;
        second = next;

        System.out.println();
        input.close();
    }
}

}
