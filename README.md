import java.util.Scanner;

class calculation{
  public static void main(String args[]){
    Scanner x= new Scanner (System.in);
    double num1, num2,answer;
    System.out.println("Enter first num: ")
    num1=x.nextDoube();
    System.out.println("Enter second num: ")
    num2=x.nextDoube();
    answer= num1 + num2;
    System.out.println(answer)
  }
}
