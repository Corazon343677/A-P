# неинициализированные переменные

### -0.5 балла за неинициализированную переменную

```cpp
#include <iostream>

int main() {
    int a;
    int b;

    return 0;
}
```

### правильный вариант

```cpp
#include <iostream>

int main() {
    int a = 0;
    int b = 0;

    return 0;
}
```
