## SIZE COMPARISON
# EXPERIMENT 3
# AIM
To study and implement C++ Program Structure 

# THEORY
The sizeof operator in C++ shows the size in bytes of a data type or variable. It's evaluated at compile-time, returns a size value, and is commonly used for:

Checking data type sizes,
Memory allocation,
Array size calculations.

It works with variables, types, and expressions. The size can vary across platforms. It's particularly useful for low-level memory management and ensuring code portability.

# CODE
```

//experiment 3
#include <iostream>
using namespace std;
int main() {
     int a1;
     float a2;
      char a3;
      short int a4;
      long int a5;
      double a6;
    

    std::cout << "Size of a1: " << sizeof(a1) << "byte"<< std::endl;
    std::cout << "Size of a2: " << sizeof(a2) << "byte"<< std::endl;
    std::cout << "Size of a3: " << sizeof(a3) << "byte"<< std::endl;
    std::cout << "Size of a4: " << sizeof(a4) << "byte"<< std::endl;
    std::cout << "Size of a5: " << sizeof(a5) << "byte"<< std::endl;
    std::cout << "Size of a6: " << sizeof(a6) << "byte"<< std::endl;
    
    return 0;
}

/*Size of a1: 4byte
Size of a2: 4byte
Size of a3: 1byte
Size of a4: 2byte
Size of a5: 4byte
Size of a6: 8byte*/
```

# OUTPUT 
![image](https://github.com/user-attachments/assets/bfc108a3-f132-46b2-a588-2ab3830037e7)


# CONCLUSION

LEARNT HOW TO CHECK THE SIZE OF ANY OPERATOR IN C++.
