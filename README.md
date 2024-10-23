
public class SimpleInterest {
    public static void main(String[] args) {
        double principal = 10000; // Principal amount
        double rate = 5; // Interest rate
        int time = 3; // Time period in years

        double simpleInterest = (principal * rate * time) / 100;
        System.out.println("Simple Interest: " + simpleInterest);
    }
}
