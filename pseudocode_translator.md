# Pseudocode Translator

## Overview
This is a comprehensive pseudocode translator that converts pseudocode into various programming languages. The goal is to help users understand how pseudocode can be translated into functional code.

## Structure of the Translator
- **Input**: Pseudocode string provided by the user.
- **Output**: Code in the specified programming language.

## Functionality:
1. **Identify the Programming Language**: Determine if the user wants the output in Python, Java, or C++.
2. **Translate the Pseudocode**: Convert the pseudocode into the corresponding programming language syntax.
3. **Output the Code**: Display the translated code to the user.

## Example of Pseudocode and its Translation:

### Example 1:
**Pseudocode**:
```
START
SET x = 10
IF x > 5 THEN
    PRINT "x is greater than 5"
ENDIF
END
```

**Python Translation**:
```python
x = 10
if x > 5:
    print("x is greater than 5")
```

**Java Translation**:
```java
public class Main {
    public static void main(String[] args) {
        int x = 10;
        if (x > 5) {
            System.out.println("x is greater than 5");
        }
    }
}
```

**C++ Translation**:
```cpp
#include <iostream>
using namespace std;

int main() {
    int x = 10;
    if (x > 5) {
        cout << "x is greater than 5";
    }
    return 0;
}
}
```

### Example 2:
**Pseudocode**:
```
START
WHILE x < 10 DO
    x = x + 1
ENDWHILE
END
```

**Python Translation**:
```python
while x < 10:
    x += 1
```

**Java Translation**:
```java
while (x < 10) {
    x++;
}
```

**C++ Translation**:
```cpp
while (x < 10) {
    x++;
}
```

## Conclusion
This pseudocode translator serves as a helpful tool for learning how to convert pseudocode into actual code. Users can improve their programming skills by understanding the syntax and structure of different programming languages. 
