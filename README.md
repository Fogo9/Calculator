# **CALCULATOR**

# Information

* **Making a calculator with the switch-case method.**

# Technologies Used

* **JAVA**

# Contents

* The variables **number1**, **number2** and **choose** is defined with int.

* Addition, Subtraction, Multiplication and Division operations are defined.

* Created a choose action that allows the user to perform any action.

* Transactions were printed on the screen with the Switch-Case method.

* If there is a selection other than 4, it will be printed as an error.

<br />

```Java

public class Calculator{

    public static void main(String[] args) {

        int number1, number2, choose;

        Scanner input = new Scanner(System.in);


```

```Java

        System.out.print("Enter The First Number :");

        number1 = input.nextInt();

        System.out.print("Enter The Second Number :");

        number2 = input.nextInt();


        System.out.println("1-Addition\n2-Subtraction\n3-Multiplication\n4-Division");

        System.out.print("Your Choose :");

        choose = input.nextInt();

```
```Java

        switch(choose){

            case 1:
            System.out.println("Addition :" + (number1 + number2));
            break;

            case 2:
            System.out.println("Subtraction :" + (number1 - number2));
            break;

            case 3:
            System.out.println("Multiplication :" + (number1 * number2));
            break;

            case 4:
                switch(number2){
                    case 0:
                    System.out.println("A number cannot be divided by 0");
                    break;

                    default:
                    System.out.println("Division :" + (number1 / number2));
                    break;
            }
            break;

            default:
            System.out.println("Wrong Choose! Try Again.");
            break;
        }
    }
}

```

```bash

        Enter The First Number :10
        Enter The Second Number :5
        1-Addition
        2-Subtraction
        3-Multiplication
        4-Division
        Your Choose :1
        Addition :15

```
```bash

        Enter The First Number :10
        Enter The Second Number :5
        1-Addition
        2-Subtraction
        3-Multiplication
        4-Division
        Your Choose :2
        Subtraction :5

```
```bash

        Enter The First Number :10
        Enter The Second Number :5
        1-Addition
        2-Subtraction
        3-Multiplication
        4-Division
        Your Choose :3
        Multiplication :50

```
```bash

        Enter The First Number :10
        Enter The Second Number :5
        1-Addition
        2-Subtraction
        3-Multiplication
        4-Division
        Your Choose :4
        Division :2

```
```bash

        Enter The First Number :10
        Enter The Second Number :0
        1-Addition
        2-Subtraction
        3-Multiplication
        4-Division
        Your Choose :4
        A number cannot be divided by 0

```
```bash

        Enter The First Number :10
        Enter The Second Number :5
        1-Addition
        2-Subtraction
        3-Multiplication
        4-Division
        Your Choose :5
        Wrong Choose! Try Again !

```
<br />

# LINK

* Click here https://github.com/Fogo9/Calculator.git to access the Github page for this project.

<br />

# LICENSE

* This software is licensed By Tuncay Demir under the MIT license.

<br />

>[Patika.dev](https://app.patika.dev/fogomurphy)

<br/>

| Name |  Email |
| ---- |  ----- |
| Tuncay | tuncaydemir682@gmail.com |
