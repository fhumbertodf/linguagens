### JavaScript

```
var input = require('fs').readFileSync('/dev/stdin', 'utf8');
var lines = input.split('\n');
var a = parseInt(lines.shift());
var b = parseFloat(lines.shift());
var str = lines.shift();

var lista = lines.shift().split(' ');
lista[0], lista[1], lista[2];
```

### Python

```
a = int(input())
b = float(input())
str = input()

lista = input().split(" ")
lista[0], lista[1], lista[2];
```

### PHP

```
<?php
    $a = (int) trim(fgets(STDIN));
    $b = (float) trim(fgets(STDIN));
    $str = trim(fgets(STDIN));
    
    $lista = explode(" ", trim(fgets(STDIN)));
    $lista[0], $lista[1], $lista[2];
?>
```

### Java

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) throws IOException {
        Scanner leitor = new Scanner(System.in);
	int a = leitor.nextInt();
	double b = leitor.nextDouble();
	String str = leitor.next();
    }	
}
```
