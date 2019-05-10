# HelloWorld

#### - C HelloWorld 模板
```C   
#include <stdio.h>

int main(int argc, char *argv[])
{
    printf("%d -> HelloWorld\n", 0x0000);
    return 0;
}
```

#### - C++ HelloWorld 模板
```C++
#include <iostream>

int main(int argc, char *argv[])
{
    std::cout << 0x0000 << " -> HelloWorld" << std::endl;
    return 0;
}
```

#### - Go HelloWorld 模板
```Go
package main

func main() {
    println(0x0000, "-> HelloWorld")
}
```

#### - Java HelloWorld 模板
```Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println(0x0000 + " -> HelloWorld");
    }
}
```

#### - Python HelloWorld 模板
```Python
print(0x0000, " -> HelloWorld", sep='', end='\n')
```

#### - Scheme HelloWorld 模版
```Scheme
(begin
  (display (string-append (number->string #x0000) " -> HelloWorld" ))
  (newline)
)
```

#### - Haskell HelloWorld 模板
```Haskell
 putStrLn $ show(0x0000) ++ " -> HelloWorld"
```
