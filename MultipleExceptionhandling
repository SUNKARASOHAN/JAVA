import java.io.*;
import java.util.*;
public class MultipleException{
    public static void main(String args[]){
        int a=5,b=0,c;
        int arr[]=new int[5];
        String str=null;
        try{
            c=a/b;
            System.out.println("Value of c is "+c);
            arr[10]=200;
            System.out.println("length of the string is "+str.length());
        }
        catch(ArithmeticException ae){
            System.out.println("Arithmetic Exception caught ");
        }
        catch(NullPointerException npe){
            System.out.println("NullPointer Exception caught");
        }
        catch(Exception e){
            System.out.println("Exception caught");
        }
    }
}
