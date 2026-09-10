# неопределенные переменные

### -0.5 балла за неопределенную переменную

```cpp
#include <iostream>

int main() {
    int a;
    int b;

    std::cin >> a;
    std::cin >> b;

    std::cout << a << " " << b;

    return 0;
}
```

### правильный вариант

```cpp
#include <iostream>

int main() {
    int a = 0;
    int b = 0;

    std::cin >> a;
    std::cin >> b;

    std::cout << a << " " << b;

    return 0;
}
```
