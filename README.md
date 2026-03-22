# HumanHasWeight-
У каждого человека есть рост и вес. Класс Human реализует соответствующие интерфейсы. Но, похоже, в такой реализации закралась ошибка. Обрати внимание на вывод программы. Исправь ошибки в интерфейсах (подсказка: переименуй методы, согласно требований к задаче) и, соответственно, в остальном коде. На экран должны быть выведены рост и вес человека (любые положительные целые числа).

package com.java.task.task15.task1505;

/* 
ООП - исправь ошибки в интерфейсах
*/

public class Solution {
    public interface HasWeight {
        int getValue();
    }

    public interface HasHeight {
        int getValue();
    }

    public static class Human implements HasWeight, HasHeight {
        @Override
        public int getValue() {
            return 0;
        }
    }

    public static void main(String[] args) {
        Human human = new Human();
        System.out.println(human.getValue());
        System.out.println(human.getValue());
    }
}

