// fibonacci.cpp
#include <iostream>

int main() {
    // Make an array to hold Fibonacci numbers up to F(59)
    int fib[60];
    
    // First two terms are given
    fib[0] = 0;
    fib[1] = 1;
    
    // Compute all the following Fibonacci numbers iteratively
    for (int i = 2; i < 60; i++) {
        fib[i] = fib[i-1] + fib[i-2];
    }
    
    // Print all Fibonacci numbers from F(0) to F(59)
    for (int i = 0; i < 60; i++) {
        std::cout << fib[i] << std::endl;
    }
    
    // Program comment about numbers approaching two billions
    /*
        As the Fibonacci sequence progresses, the numbers grow exponentially. When using a 32-bit signed integer (int),
        the maximum value it can hold is 2,147,483,647 (2^31 - 1). As we approach Fibonacci numbers that are close to
        this limit, adding the last two numbers in the sequence can result in integer overflow. This means the computed
        value wraps around to negative due to the limit of the data type, causing the numbers to diverge from what they
        should be. This behavior is observed as the numbers approach two billion, demonstrating the importance of choosing
        the appropriate data type for the problem domain to prevent overflow and ensure accurate calculations.
    */
    
    return 0;
}
