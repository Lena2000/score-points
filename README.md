package prog1;

import java.util.Scanner;

/**
 *
 * @author LENOVO
 */
public class Prog1 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        System.out.println("Input your bal");
        Scanner sc = new Scanner(System.in);
        int bal = sc.nextInt();
        System.out.println("my bal="+bal);
        if (bal>=0 && bal<60)System.out.println("neyd");
        else if (bal>=60 && bal<75) System.out.println("ydovl");
        else if (bal>=75 && bal<90) System.out.println("horosho");
        else if(bal>=90 && bal<=100) System.out.println("otlichno");
        else  System.out.println("Error");
    
}
}
