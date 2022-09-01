# javaGbHomeWork1
package gbhomework;

public class HomeWorkApp {
    public static void main(String[] args){
        printThreeWords();
        checkSumSign();
        printColor();
        compareNumbers();
    }

    private static void compareNumbers() {
        int compareNumbersA = 3;
        int compareNumbersB = 2;
        if (compareNumbersA >= compareNumbersB) {
            System.out.println("a >= b");
        }
    }

    private static void printColor() {
            int value = 99;
            if (value <= 0) {
                System.out.println("Красный");
            }
            if (value <= 100) {
                System.out.println("Желтый");
            }
            if (value > 100) {
                System.out.println("Зеленый");
            }
    }

    private static void checkSumSign() {
        int checkSumSignA = 5;

        int checkSumSignB = -6;
        if (checkSumSignB <= 0) {
            System.out.println("Отрицательная");
        }
        System.out.println(checkSumSignA + checkSumSignB );


    }

    private static void printThreeWords() {
        System.out.println("Orange");
        System.out.println("Banana");
        System.out.println("Apple");
    }
}
