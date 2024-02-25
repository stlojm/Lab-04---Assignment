# Lab-04---Assignment
//Function to print "Hello World" n times recursively
void print HelloWorld(int n) {
    if (n <= 0) {
        return;
    }
    System.out.println("Hello World");
    printHelloWorld(n - 1);
}
