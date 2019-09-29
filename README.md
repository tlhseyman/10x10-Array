package sample;

public class TenByTenArray {

   public static void main(String[] args) {
        int[][] numbers = new int[10][10];
        int number = 1;
        int rowSum = 0;


   for(int i=0 ; i<10 ; i++){
            for (int j=0 ; j<10 ; j++){
                numbers[i][j] = number;
                number++;
                rowSum+=numbers[i][j];
                System.out.printf("%4d",numbers[i][j]);

   }
            System.out.println(" // Sum  for this line is : " + rowSum);
            System.out.println();
        }
        //Print sum of all numbers;

   int colSum = 0;
        for (int i=0; i<10; i++){
            for (int j=0;j<10;j++){
                colSum+=numbers[j][i];

   }
            colSum=0;

   }

   String[][] cities = {{"San Francisco", "San Antonio", "San Diego"},{"Austin", "Arlington", "Irvine"}};
        for (int q=0; q<cities.length; q++){
            for (int t=0; t<cities.length-1; t++){
                System.out.println(cities[q][t]);
            }
        }


    }
}
