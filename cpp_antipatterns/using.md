# using объявления в C++

### -0.5 балла за их использование

```cpp
#include <iostream>

using std::cout;
using std::cin;

int main() {
    int a = 0;
    int b = 0;

    cin >> a;
    cin >> b;

    cout << a << " " << b;

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
