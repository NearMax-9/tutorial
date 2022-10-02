import java.util.*;
public class MultiplyFloatingNumbers {
   public static void main(String args[]){
      Scanner sc = new Scanner(System.in);
      System.out.println("Enter first floating point number.");
      float flt1 = sc.nextFloat();

      System.out.println("Enter second floating point number.");
      float flt2 = sc.nextFloat();

      float product = flt1*flt2;
      System.out.println("Product of given floating point numbers ::"+product);
   }
}
