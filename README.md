# SUPER-KEYWORD-VARIABLE-CALL

Author- Shakira Murshida 

class A {

    int x = 5;}

class B extends A {

    int x = 10;

    void display() {
        System.out.println(x);       // prints B's x
        System.out.println(super.x); // prints A's x
    }
}

class Main {

    public static void main(String[] args) {
        B b = new B();
        b.display();    }
}
