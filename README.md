class OperatorsDemo {
    public static void main(String[] args) {

        int a = 10, b = 3;
        System.out.println("Addition: " + (a + b));
        System.out.println("Subtraction: " + (a - b));
        System.out.println("Multiplication: " + (a * b));
        System.out.println("Division: " + (a / b));
        System.out.println("Modulus: " + (a % b));
        System.out.println("a > b: " + (a > b));
        System.out.println("a < b: " + (a < b));
        System.out.println("a == b: " + (a == b));
        System.out.println("a != b: " + (a != b));
        System.out.println("Logical AND: " + (a > 5 && b < 5));
        System.out.println("Logical OR: " + (a < 5 || b < 5));
        System.out.println("Logical NOT: " + !(a > b));
        
        int c = 5;
        c += 2;
        System.out.println("c += 2: " + c);

      
        int x = 5;
        System.out.println("Post-increment: " + (x++));
        System.out.println("After increment: " + x);
        System.out.println("Pre-increment: " + (++x));

        int max = (a > b) ? a : b;
        System.out.println("Largest: " + max);
        System.out.println("Bitwise AND: " + (a & b));
        System.out.println("Bitwise OR: " + (a | b));
        System.out.println("Bitwise XOR: " + (a ^ b));
    }
}
