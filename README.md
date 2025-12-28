# Car-rental-system
import java.util.*;

public class Login {
    public static boolean login() {
        Scanner sc = new Scanner(System.in);
        String correctUsername = "admin";
        String correctPassword = "1234";
        System.out.println("--- Login ---");
        System.out.print("Enter Username: ");
        String username = sc.nextLine();
        System.out.print("Enter Password: ");
        String password = sc.nextLine();
        if (username.equals(correctUsername) && password.equals(correctPassword)) {
            System.out.println("Login successful!\n");
            return true;
        } else {
            System.out.println("Invalid username or password!\n");
            return false;
        }
    }
}

