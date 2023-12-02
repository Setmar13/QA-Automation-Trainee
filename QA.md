import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Введите число: ");
        int number = scanner.nextInt();

        if (number > 7) {
            System.out.println("Привет");
        }
    }
}
/* Этот алгоритм предполагает использование класса Scanner для чтения числа с клавиатуры.
Затем происходит проверка условия: если введенное число больше 7, то выводится строка "Привет". 
Если число меньше или равно 7, то ничего не происходит. */

