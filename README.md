public class Task_number_11_working_with_data {
    public static void main(String[] args) {
        // 1. Ввести первое число с клавиатуры и записать его в строковую переменную.
        Scanner s = new Scanner(System.in);

        String num1 = s.nextLine();

        // Преобразуем строковоую переменную в числовую
        Integer i1 = Integer.valueOf(num1);

        System.out.println("Вы ввели первое число  " + num1);

        // 2. Ввести второе число с клавиатуры и сохранить его в целочисленную переменную типа int.
        int num2 = s.nextInt();
        System.out.println("Вы ввели второе число " + num2);

        // 3. Сравнить 2 числа и вывести большее на экран
        if(i1>num2){
            System.out.println("Первое число " + i1 + " больше чем " + num2);
        }
        else if (i1<num2){
            System.out.println("Второе число " + num2 + " больше чем " + i1);
        }
        else {
            System.out.println("Наибольшее число не выявленно");
        }
        //4. Выведите также меньшее число на экран, предварительно переконвертировать его в тип double.
        if(i1>num2){
            System.out.println("Первое число " + i1 + " больше чем " + (double)num2);
        }
        else if (i1<num2){
            System.out.println("Второе число " + num2 + " больше чем " + (double)i1);
        }
        else {
            System.out.println("Наибольшее число не выявленно");
        }
    }
}
