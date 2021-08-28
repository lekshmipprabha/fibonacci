# fibonacci
java fibonacci
public class Fibonacci {

    /**
     * @param args
     */
    public static void main(String[] args) {
        
        int number = 5;

        System.out.println("Fibonacci series upto " + number + " numbers : ");
        
        // printing Fibonacci series up to "number" of times
        for (int i = 1; i <= number; i++) {
            System.out.print(fibonacci(i) + " ");
        }
    }

