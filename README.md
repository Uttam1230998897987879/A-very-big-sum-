# A-very-big-sum-
HackerRank solution , A very big sum , solution 
uttam kumar 

import java.util.Scanner;

public class BigSum {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int uttam = scanner.nextInt();
        long sum = 0;
        while (uttam-- > 0 ) {
            sum += scanner.nextInt();
        }
        System.out.println(sum);
    }
}
