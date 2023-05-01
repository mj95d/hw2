# hw2

//abdulmajeed
// برنامج Java لحساب مجموع عددين صحيحين وإرجاع true إذا كان المجموع يساوي عددا صحيحا ثالثا

import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        Scanner input= new Scanner(System.in);
        int number1=5;
        int number2=10;
        int number3=15;
        System.out.println("please inter 2 integers:");
        number1=input.nextInt();
        number2=input.nextInt();
        number3=input.nextInt();
        int sum = number1+number2+number3;
        System.out.printf("%d + %d = %d", number1,number2,number3);







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

//الجمع

public class Main {
    public static void main(String[] args) {
        int x = 125;
        int y = 24;
        System.out.println(x + y);

    }
}
//الطرح

public class Main {
    public static void main(String[] args) {
        int x = 125;
        int y = 24;
        System.out.println(x - y);

    }
}








//الضرب

public class Main {
    public static void main(String[] args) {
        int x = 125;
        int y = 4;
        System.out.println(x * y);
    }
}





//القسمة

public class Main {
    public static void main(String[] args) {
        int x = 125;
        int y = 4;
        System.out.println(x / y);
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


//برنامج Java لقبول رقم وتحقق من أن الرقم زوجي أم لا. يطبع 1 إذا كان الرقم زوجيا أو 0 إذا كان الرقم فرديا. (استخدم بيان if)


import java.util.Scanner;

public class EvenOdd
{
    public static void main(String[] args)
    {
        int a;
        System.out.println("Please enter a number to check even or odd:");
        Scanner sc = new Scanner(System.in);
        a = sc.nextInt();

        if(a % 2 == 0)
        {
            System.out.println("Entered number is an even number");
        }
        else
        {
            System.out.println("Entered number is an odd number");
        }
    }
}
