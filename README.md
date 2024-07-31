# fibanocci
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int n= sc.nextInt();
        int a=0;
        int b=1;
        System.out.print(a+" "+b+" ");
        if (n>2){
            for(int i=0;i<n-2;i++){
                int c=a+b;
                a=b;
                b=c;
                System.out.print(c+" ");
            }
        }
        
    }
}
