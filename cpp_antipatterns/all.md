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

# неинициализированные переменные

### -0.5 балла за неинициализированную переменную

```cpp
int main() {
    int a;
    int b;

    return 0;
}
```

### правильный вариант

```cpp
int main() {
    int a = 0;
    int b = 0;

    return 0;
}
```

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
