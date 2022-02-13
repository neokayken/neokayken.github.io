---
layout: single
title:  "코드블록 테스트 마크다운"
---

#코드블록 테스트 하기

마크다운에서의 코드 블록 테스트 입니다.

먼저 파이썬

```python
print('Hello!')
```

다음은 C언어 입니다

```cpp
#include <stdio.h>
 
int main()
{
    printf("Hello World!\n");
 
    return 0;
}
```

C++은 C언어와 같습니다.

```cpp
#include <iostream>

using namespace std;

int main() {
    
    cout << "Hello World!" << endl;
    
    return 0;
}

```


다음은 자바입니다

```java
package com;

public class Main {

    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}

```

```javascript
console.log("Hello World")
```

html은 다음과 같습니다.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Hello World!</h1>
</body>
</html>
```

기본 코드블록인데도 디자인이
생각보다 괜찮은 것 같습니다.
역시 인생을 코드에 바친 커뮤니티가
깃허브니까 코드에 대해서는
확실히 느낌이 다릅니다.
