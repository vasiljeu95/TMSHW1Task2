# TMS HomeWork1 Task2
## Условие задачи:
Передаём через командную строку число. Если оно больше 0, но меньше 6,то вывести его строковое представление (one, two, three, four, five, six). В противном случае вывести "invalid". Операторы сравнения (>, <, == и т.д.) при этом использовать нельзя.
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
