# MathPuzzel
import java.util.Scanner;

public class P06_MathPuzzel {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);

        int key = Integer.parseInt(scanner.nextLine());

        for (int i = 0; i <= 30; i++) {
            for (int j = 0; j <= 30; j++) {
                for (int k = 0; k <= 30; k++) {

                    if (i < j && j < k){

                         while (i + j + j == key) {

                            System.out.printf("%d + %d + %d = %d%n", i, j, k, key);
                        }
                    }
                }
            }
        }



    }

}
