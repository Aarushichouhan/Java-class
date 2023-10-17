import java.util.Scanner;

public class StringArray {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String[][] s = new String[2][2];

        System.out.println("Enter values for the string array:");

        for (int i = 0; i < 2; i++) {
            for (int j = 0; j < 2; j++) {
                System.out.print("Enter string for s[" + i + "][" + j + "]: ");
                s[i][j] = sc.nextLine();
            }
        }

        System.out.println("String array elements are:");
        for (String[] row : s) {
            for (String element : row) {
                 System.out.println(element);
            }
            System.out.println();
        }
    }
}
