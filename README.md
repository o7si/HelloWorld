# HelloWorld

- 持有者
C++: shayuanshayuan(1, 2019-04-01)

C: lwlzh(1, 2019-04-01)

Java: chenshimeng(1, 2019-04-01)

Python: 43EVER(1, 2019-04-01)

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
