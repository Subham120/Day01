#Day O1

// wap to check student fail , pass or distinaction
import java.util.*;
public class ques2 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int marks = sc.nextInt();
        if(marks>=75){
            System.out.print("distinaction");
        }
        else if(marks>=40 && marks<75){
            System.out.print("pass");
        }
        else{
            System.out.print("fail");
        }
    }
}
