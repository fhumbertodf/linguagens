### JavaScript

```
if (valor1 > valor2 && valor1 > valor3) {
	console.log(valor1 + ' eh o maior');
} else if (valor2 > valor3) {
	console.log(valor2 + ' eh o maior');
} else {
	console.log(valor3 + ' eh o maior');
}
```

### Python

```
if valor1 > valor2 and valor1 > valor3:
	print(str(valor1) + " eh o maior")
elif valor2 > valor3:
	print(str(valor2) + " eh o maior")
else:
	print(str(valor3) + " eh o maior")
```

### PHP

```
<?php
    if ($valor1 > $valor2 && $valor1 > $valor3) {
		echo strval($valor1)." eh o maior", "\n";
	} elseif ($valor2 > $valor3) {
		echo strval($valor2)." eh o maior", "\n";
	} else { 
        echo strval($valor3)." eh o maior", "\n"; 
    }
?>
```

### Java

```
import java.io.IOException;
import java.util.Scanner;

public class Main {
    public static void main(String[] args) throws IOException {
        if (valor1 > valor2 && valor1 > valor3) {
        	System.out.printf("%d eh o maior%n", valor1);
        } else if (valor2 > valor3) {
        	System.out.printf("%d eh o maior%n", valor2);
        } else {
        	System.out.printf("%d eh o maior%n", valor3);
        }
    }	
}
```
