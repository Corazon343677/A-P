# неопределенные переменные

### -0.5 балла за неопределенную переменную

```cpp
#include <iostream>
int main() {
    int a;
    int b;

    cin >> a;
    cin >> b;

    cout << a << " " << b;

    return 0;
}
```

### правильный вариант

```cpp
int main() {
    int a = 0;
    int b = 0;

    cin >> a;
    cin >> b;

    cout << a << " " << b;

    return 0;
}
```
