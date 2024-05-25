# Dialy_DSA-100-days

## Daily Log

### Day 0 - 22-05-2024

**Today's Focus:** Setting up the environment and reviewing essential C++ concepts

**Resources Used:**
- 📖 <a href="https://www.learncpp.com/">Learn C++</a>
- 🌐 <a href="https://www.geeksforgeeks.org/c-plus-plus/">GeeksforGeeks - C++</a>
- 📖 <a href="https://www.amazon.com/Programming-Principles-Practice-Using-Second/dp/0321992784">Programming: Principles and Practice Using C++ by Bjarne Stroustrup</a>

**Activities:**
- 📝 Set up development environment (installed IDE, configured compilers, etc.).
- 📌 Reviewed essential C++ concepts:
  - 🔗 <a href="https://www.learncpp.com/cpp-tutorial/66-arrays-part-i/">Arrays</a>
  - 🔗 <a href="https://www.learncpp.com/cpp-tutorial/78-pointers-and-references/">Pointers and References</a>
  - 🔗 <a href="https://www.learncpp.com/cpp-tutorial/74-overview-of-functions/">Functions</a>

**Detailed Notes:**
- 📝 C++ Concepts:
  - **Arrays**: Arrays are used to store multiple values in a single variable.
  - **Pointers**: Pointers store the address of variables. They are used for dynamic memory allocation and are crucial for efficient programming.
  - **Reference Pointers**: References are aliases for existing variables, making it easier to manipulate data.
  - **Functions**: Functions are blocks of code that perform specific tasks and can be reused throughout the program.
## A Quick Illustartion on how Pointers are differed from References:
![image](https://github.com/ajaykr2712/Dialy_DSA-100-days/assets/112938234/c0e3a836-6f7a-4c6b-ba35-886798474f0a)

### Functionality of a Pointer:
![image](https://github.com/ajaykr2712/Dialy_DSA-100-days/assets/112938234/9450943d-5117-49ed-9b00-0eb970d4a715)


**Code Snippets:**
```cpp
// Example of using arrays in C++
#include <iostream>
using namespace std;

int main() {
    int arr[5] = {1, 2, 3, 4, 5};
    for (int i = 0; i < 5; i++) {
        cout << arr[i] << " ";
    }
    return 0;
}

// Example of using pointers in C++
#include <iostream>
using namespace std;

int main() {
    int var = 20;
    int *ptr;
    ptr = &var;

    cout << "Value at ptr = " << ptr << endl;
    cout << "Value at *ptr = " << *ptr << endl;

    return 0;
}

Reflections:

🤔 Setting up the development environment is crucial for a smooth workflow.
🚀 Understanding basic C++ concepts like arrays and pointers is fundamental before diving deeper into data structures and algorithms.
Next Steps:

🔜 Start with basic data structures: Arrays and Strings.
🔜 Practice basic problems on arrays from various coding platforms.
