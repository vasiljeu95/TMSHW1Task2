# TMS HomeWork1 Task1
## Условие задачи:
Передаём через командную строку одно число. Надо вывести на экран сколько в этом числе цифр и положительное оно или отрицательное. Например, "this is a single digit number" и "this is a positive number". Достаточно будет определить, является ли число однозначным, двузначным или трехзначным и более. Учтите, что 0 не является положительным или отрицательным числом.
### Дополнительно:
с помощью операторов "/" (деление) и "%" (модуль) определить количество цифр в числе даже если оно 4-значное и более.
## My code is:
```java
package com.github.vasiljeu95.tmshw1.task2;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();

        switch (num) {
            case 1:
                System.out.println("one");
                break;
            case 2:
                System.out.println("two");
                break;
            case 3:
                System.out.println("three");
                break;
            case 4:
                System.out.println("four");
                break;
            case 5:
                System.out.println("five");
                break;
            case 6:
                System.out.println("six");
                break;
            default:
                System.out.println("invalid");
        }
    }
}
```
