# Ejemplos de Pseudocódigo y Traducciones

## Ejemplo 1: Sumar dos números

### Pseudocódigo:
```
Inicio
  Leer num1
  Leer num2
  suma = num1 + num2
  Escribir suma
Fin
```

### Traducción a Python:
```python
num1 = int(input())
num2 = int(input())
suma = num1 + num2
print(suma)
```

### Traducción a JavaScript:
```javascript
let num1 = parseInt(prompt());
let num2 = parseInt(prompt());
let suma = num1 + num2;
console.log(suma);
```

### Traducción a Java:
```java
import java.util.Scanner;

public class Suma {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    int num1 = scanner.nextInt();
    int num2 = scanner.nextInt();
    int suma = num1 + num2;
    System.out.println(suma);
    scanner.close();
  }
}
```

## Ejemplo 2: Encontrar el mayor de dos números

### Pseudocódigo:
```
Inicio
  Leer num1
  Leer num2
  Si num1 > num2 Entonces
    mayor = num1
  Sino
    mayor = num2
  Fin Si
  Escribir mayor
Fin
```

### Traducción a Python:
```python
num1 = int(input())
num2 = int(input())
mayor = num1 if num1 > num2 else num2
print(mayor)
```

### Traducción a JavaScript:
```javascript
let num1 = parseInt(prompt());
let num2 = parseInt(prompt());
let mayor = num1 > num2 ? num1 : num2;
console.log(mayor);
```

### Traducción a Java:
```java
import java.util.Scanner;

public class Mayor {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
    int num1 = scanner.nextInt();
    int num2 = scanner.nextInt();
    int mayor = (num1 > num2) ? num1 : num2;
    System.out.println(mayor);
    scanner.close();
  }
}
```
