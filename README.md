# HelloWorld

#### - C HelloWorld 模板
```C   
#include <stdio.h>

int main(int argc, char *argv[])
{
    printf("%d -> Hello World\n", 0x0000);
    return 0;
}
```

#### - C++ HelloWorld 模板
```C++
#include <iostream>

int main(int argc, char *argv[])
{
    std::cout << 0x0000 << " -> Hello World" << std::endl;
    return 0;
}
```

#### - Golang HelloWorld 模板
```Golang
package main

import "fmt"

func main() {
    fmt.Printf("%d -> Hello World\n", 0x0000);
}
```

#### - Java HelloWorld 模板
```Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println(0x0000 + " -> Hello World");
    }
}
```

#### - Scheme HelloWorld 模版
```Scheme
(begin
    (display (string-append (number->string #x0000) " -> Hello World" ))
    (newline)
)
```

#### - Python HelloWorld 模板
```Python
print(0x0000, " -> Hello World", sep='', end='\n')
```

#### - Haskell HelloWorld 模板
```Haskell
putStrLn $ show(0x0000) ++ " -> Hello World"
```

#### - JavaScript HelloWorld 模板
```JavaScript
console.log(0x0000 + " -> Hello World");
```
