# java-DSA
first repository
import java.util.Scanner;
public class Name
 {
    public static void main(String args[]) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the size of array");
        int size=sc.nextInt();
        int number []=new int [size];

    System.out.println("enter input ");
    for( int i=0;i<size;i++)
    {
        number[i]=sc.nextInt();
    }
    System.out.println("enter the search element");
    int x=sc.nextInt();
    System.out.println("HEre the out put");
    for(int i=0;i<number.length;i++){
        if (number[i]==x)
        {
            System.out.println("x is found on "+i);
        }
    }
    System.out.println("length of array"+number.length);

    }
    
}
