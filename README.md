#include <iostream>
#include <stdio.h>

int main ()
{
    int edad;
    std::cout << "ingrese su edad: ";
    std::cin >> edad;

    if(edad >=18) {
        std::cout << "Usted es mayor de edad." << std:: endl;    
    } else {
        std::cout << "Usted es menor de edad." << std:: endl;  
    }
    
    return 0;
    
}
