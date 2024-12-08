# number-square
in this code you have to give a no. and it will print other numbers also till that particular no. which you had given in input in different forms
import java.util.Scanner;

public class numberSquare {
    public numberSquare() {
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int r = sc.nextInt();

        for(int i = 1; i <= r; ++i) {
            int k;
            for(k = i; k <= r; ++k) {
                System.out.print(k);
            }

            for(k = 1; k <= i - 1; ++k) {
                System.out.print(k);
            }

            System.out.println();
        }

    }
}

