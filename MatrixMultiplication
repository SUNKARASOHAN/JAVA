import java.io.*;
import java.util.*;
public class MatrixAddition {
    public static void main(String args[]) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter rows and columns of 1st matrix:");
        int r1 = sc.nextInt();
        int c1 = sc.nextInt();
        System.out.println("Enter rows and columns of 2nd matrix:");
        int r2 = sc.nextInt();
        int c2 = sc.nextInt();
        if ((r1 != r2)||(c1!=c2)){
            System.out.println("Addition not possible.");
            System.exit(0);
        } else {
            int a[][] = new int[r1][c1];
            int b[][] = new int[r2][c2];
            System.out.println("Enter " + (r1 * c1) + " elements into the matrix a:");
            for (int i = 0; i < r1; i++) {
                for (int j = 0; j < c1; j++) {
                    a[i][j] = sc.nextInt();
                }
            }
            System.out.println("Enter " + (r2 * c2) + " elements into the matrix b:");
            for (int i = 0; i < r2; i++) {
                for (int j = 0; j < c2; j++) {
                    b[i][j] = sc.nextInt();
                }
            }
             int c[][] = new int[r1][c2];
            for (int i = 0; i < r1; i++) {
                for (int j = 0; j < c2; j++) {
                    c[i][j] = a[i][j]+b[i][j];
                    }
                }
            System.out.println("The resultant matrix c is:");
            for (int i = 0; i < r1; i++) {
                for (int j = 0; j < c2; j++) {
                    System.out.print(c[i][j] + " ");
                }
                System.out.println();
            }
        }
    }
}
