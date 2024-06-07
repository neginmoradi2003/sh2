# sh2
public class SumCalculator { public static void main(String[] args) { Static scanner = new Scanner(System.in);

    System.out.print("Enter the number of elements: ");
    int n = scanner.nextInt();
    int sum = 0;
    int sumOfSquares = 0;
    int sumOfCubes = 0;
    for (int i = 1; i <= n; i++) {
        System.out.print("Enter number " + i + ": ");
        int number = scanner.nextInt();
        sum += number;
        sumOfSquares += number * number;
        sumOfCubes += number * number * number;
    }
    System.out.println("Sum: " + sum);
    System.out.println("Sum of squares: " + sumOfSquares);
    System.out.println("Sum of cubes: " + sumOfCubes);
}
}
