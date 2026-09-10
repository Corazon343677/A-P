# return

### как не надо

```cpp
#include <iostream>

int main() {
    int a = 0;

    std::cout << a
}
```
### правильный вариант
```cpp  
#include <iostream>

int main() {
    int a = 0;

    std::cout << a

    return 0;
}
```
