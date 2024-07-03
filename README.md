# check-if-number-is-odd-or-even
import java.util.Scanner;

public class loops {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.println("enter the number");
        int x = s.nextInt();
        int y = x % 2;
        if(y == 0){
            System.out.println("the numnber is even");
        }
        else{
            System.out.println("the number is odd");
        }

    }
}
