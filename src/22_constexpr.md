# constexpr

## Статическая и динамическая инициализация

```c++
int a = 42;
int f() {
    int result;
    std::cin >> result;
    return result;
}

int a = 42; // инициализируется в момент компиляции
int b = f(); // инициализируется
```

`a` инициализируется на этапе компиляции, под `b` просто резевируются 4 байта, а её инициализация происходит в момент старта программы. 
