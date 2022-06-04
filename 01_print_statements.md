### JavaScript

```
console.log('Hello World!');
console.log('X = ' + x);
console.log('A=' + y.toFixed(4));
console.log('SOMA = ' + z);
```

### Python

```
print('Hello World!')
print("X = {}".format(x))
print("A={:0.4f}".format(y))
print("SOMA = " + str(z))
```

### PHP

```
<?php
    echo "Hello World!", "\n";
    echo "X = $x", "\n";
    echo sprintf("A=%.4f", $y), "\n";
    echo "SOMA = ".strval($z), "\n";
?>
```

### Java

```
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World!");
	System.out.printf("X = %d%n", x);
	System.out.printf("A=%.4f%n", y); 
	System.out.printf("SOMA = %d%n", z);
    }	
}
```
