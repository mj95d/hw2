# hw2

//abdulmajeed
// 

import java.util.Scanner;


public class Main {
    public static void main(String[] args) {

          int firstNumber = 125;
        int secondNumber = 24;
       int sum = firstNumber + secondNumber;
        int min = firstNumber - secondNumber;
        int mul = firstNumber * secondNumber;
        int div = firstNumber / secondNumber;
      int mod = firstNumber % secondNumber;
      System.out.println("sum is = " + sum + "\n" + "minus is = " + min + "\n"
               + "multiplication is = " + mul + "\n" + "division is = " + div + "\n" + "mod is = " + mod);







                Scanner myObj = new Scanner(System.in);

                System.out.println("Enter name, age and salary:");

                // String input
                String name = myObj.nextLine();

                // Numerical input
                int age = myObj.nextInt();
                double salary = myObj.nextDouble();

                // Output input by user
                System.out.println("Name: " + name);
                System.out.println("Age: " + age);
                System.out.println("Salary: " + salary);





            }
        }



// السلسلة

public class Main {
    public static void main(String[] args) {
        String originalStr = "Hello";
        String reversedStr = "";
        System.out.println("Original string: " + originalStr);

        for (int i = 0; i < originalStr.length(); i++) {
            reversedStr = originalStr.charAt(i) + reversedStr;
        }

        System.out.println("Reversed string: "+ reversedStr);
    }
}

import java.util.Scanner;

public class Arithmetic {

    public static void main(String[] args) {
     
        Scanner input = new Scanner(System.in);

       
        System.out.print("Input first number: ");
        int num1 = input.nextInt();
        System.out.print("Input second number: ");
        int num2 = input.nextInt();

       
        int sum = num1 + num2;
        int diff = num1 - num2;
        int prod = num1 * num2;
        int quot = num1 / num2;
        int rem = num1 % num2;

        System.out.println(num1 + " + " + num2 + " = " + sum);
        System.out.println(num1 + " - " + num2 + " = " + diff);
        System.out.println(num1 + " x " + num2 + " = " + prod);
        System.out.println(num1 + " / " + num2 + " = " + quot);
        System.out.println(num1 + " mod " + num2 + " = " + rem);

     
        input.close();
    }
}
//برنامج Java 



       System.out.println("Pls enter your role");
        String role = s.nextLine();
        if(role.equals("admin") || role.equals("superuser")){
            System.out.println("welcome " + role);
        }else{
            System.out.println("welcome " + role);
        }

      
        int firstNum = 10;
        int secondNum = 5;
        int thirdNum = 15;
        if(firstNum + secondNum == thirdNum){
            System.out.println("The result is:" + true);
        }else{
            System.out.println("The result is:" + false);
        }

  
        Scanner s = new Scanner(System.in);
        System.out.println("Pls enter firstNum");
        int firstNum = s.nextInt();
        System.out.println("Pls enter secondNum");
        int secondNum = s.nextInt();
        System.out.println("Pls enter thirdNum");
        int thirdNum = s.nextInt();

        if(firstNum > secondNum && firstNum > thirdNum) {
            System.out.println("The greatest:" + firstNum);
        }else if(secondNum > thirdNum) {
            System.out.println("The greatest:" + secondNum);
        }else{
            System.out.println("The greatest:" + thirdNum);
      }


        Scanner s = new Scanner(System.in);
        System.out.println("Input number");
        int num = s.nextInt();
        switch (num){
            case 1 :
                System.out.println("Monday");
                break;
            case 2 :
                System.out.println("Tuesday");
                break;
            case 3 :
                System.out.println("Wednesday");
                break;
            case 4 :
                System.out.println("Thursday");
                break;
            case 5 :
                System.out.println("Friday");
                break;
            case 6 :
                System.out.println("Saturday");
                break;
            case 7 :
                System.out.println("Sunday");
                break;
        }
    }
}
