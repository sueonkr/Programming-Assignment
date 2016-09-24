import java.util.*;
public class grades {
    public static void main(String[] args) {
        Scanner console = new Scanner(System.in);
        System.out.println("Number of homework assignments?");
        int hw = console.nextInt();
        System.out.println("Points possible for hw?");
        int hwp = console.nextInt();
        System.out.println("Points earned for hw?");
        int hwe = console.nextInt();
        System.out.println("Midterm score?(out of 100)");
        int mid = console.nextInt();
        System.out.println("Final score?(out of 100)");
        int fin = console.nextInt();
        System.out.print(needed(hw, hwp, hwe, mid, fin));
    }
    public static String needed(int hw, int hwp, int hwe, int mid, int fin) {
        if (hwe/hwp + mid + fin<= (hwp + 100 + 100)/2 || (hwe/hwp + mid + fin >= (hwp + 100 + 100)/(2/3))) {
            return("you have no hope, but to satisfy yourself with a F");
        }
        if (hwe/hwp + mid + fin<= (hwp + 100 + 100)/(2/3) || (hwe/hwp + mid + fin >= (hwp + 100 + 100))) {
            return("you can get a B if you get 100 on the final");
        }
        if (hwe/hwp + mid + fin<= (hwp + 100 + 100)) {
            return("You got A already!");
        }
        return"";   
    }
}
