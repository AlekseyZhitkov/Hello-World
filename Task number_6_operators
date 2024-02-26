public class Task_number_6_operators {
        public static void main(String[] args) {
          // 1. Пользователю предлагается на выбор ввести массу или расстояние. Пример:
            //> Выберите что переводить: 1 - масса, 2 - расстояние
            //> 2
            Scanner s = new Scanner(System.in);
            System.out.println("Выберите что переводить: 1 - масса, 2 - расстояние");
            int choice = s.nextInt();

            //2. Пользователю предлагается выбрать единицу измерения. Пример:
            //> Выберите единицу измерения: 1 - метр, 2 - миля, 3 - ярд, 4 - фут
            //> 1
            System.out.println("Выберите единицу измерения: 1 - метр, 2 - миля, 3 - ярд, 4 - фут");
            int unit = s.nextInt();


            //3. Пользователю предлагается ввести количество выбранных единиц:
            //> Введите число
            //> 10
            //> Результат:
            //> Метры: 10
            //> Мили: 0.006
            //> Ярды: 10.94
            //> Футы: 32.81
            System.out.println("Введите кол-во:");
            double quantity = s.nextInt();

            switch (unit){
                case 1:
                    double meters = quantity;
                    double miles = quantity * 0.000621371;
                    double yards = quantity * 1.09361;
                    double feet = quantity * 3.28084;
                    System.out.println("Результат:");
                    System.out.println("Метры: " + meters);
                    System.out.println("Мили: " + miles);
                    System.out.println("Ярды: " + yards);
                    System.out.println("Футы: " + feet);
                    break;
            }
        }
}
