# Java-practise
public class javabasics{
    public static void main(String args[]){
        // int a = 10;
        // int b = 5;
        // System.out.println(a);
        // System.out.println(b);
        // a=b;
        // System.out.println(b);
        // 
        int a  =10;
        int b =15;
        int sum=a+b;
        System.out.print(sum);
    }
}

public class javabasics1{
    public static void main(String args[]){
       char a='a';
       char b='b';
       System.out.println((int)b);
       System.out.println((int)a);
       System.out.println(b-a);
    }
}
import java.util.*;
public class practise{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int c=sc.nextInt();
        int sum=a+b+c;
        int avg=sum/3;

        System.out.print("The average of 3 numbers is"+ avg);
        int side=sc.nextInt();
        int area=side*side;
        System.out.print("The area of the square is" +area );

        float pen=sc.nextFloat();
        float pencil=sc.nextFloat();
        float eraser=sc.nextFloat();
        float totalcost=pen+pencil+eraser;
        float newtotalcost=totalcost+(0.18f*totalcost);
        System.out.print("Total cost of all the items="+newtotalcost);

        all convert to double
        No, the statement will not give any error.NamesofvariablesarecalledidentifiersinJava.Identifierrulesays,identifierscanstartwithany alphabet or underscore (“_”) or dollar (“$”).According to the rule the given variable name is a valid identifier


    }
}
