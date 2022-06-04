### JavaScript

```
var input = require('fs').readFileSync('/dev/stdin', 'utf8');
var lines = input.split('\n');
var a = parseInt(lines.shift());
```

### Python

```
a = int(input())
```

### PHP

```
<?php
    $a = (int) trim(fgets(STDIN));
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
    }	
}
```
