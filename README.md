import java.util.*;
public class Main {
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int a=sc.nextInt();
        for(int i=5;i>=1;i--){
            for(int j=0;j<=i;j++)
            {
                System.out.print((char) (a+j) +" ");
            }
            System.out.println();
        }
        for(int i=0;i<=5;i++)
        {
            for(int j=0;j<=i;j++){
                System.out.print((char) (a+j)+" ");
            }
            System.out.println( );
        }
    }
    
}
