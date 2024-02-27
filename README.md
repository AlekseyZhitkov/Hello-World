public class Task_number_7_cycles {
    public static void main(String[] args) {
        // 1. Пользователь вводит размер массива и данные с клавиатуры в массив
        Scanner s = new Scanner(System.in);

       // вводим размер массива
        int size = s.nextInt();
        int[] arr = new int[size];

       // вводим данные в ячейки массива
        for (int i = 0; i < size; i++) {
            arr[i] = s.nextInt();
        }
        // 2. Сравнить элементы массива с заранее заданными константами x, y, z.
        int x = 5; // пример значения константы x
        int y = 10; // пример значения константы y
        int z = 15; // пример значения константы z

        // 3. Если массив содержит хотя бы одну из констант, вывести текст "Данное значение имеется в константах".
        boolean containsConstant = false;
        for (int num : arr) {
            if (num == x || num == y || num == z) {
                containsConstant = true;
                break;
            }
        }
        if (containsConstant) {
            System.out.println("Данное значение имеется в константах");}
    }
}
