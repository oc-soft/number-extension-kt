# Number extersion for kotlin

This is very simple number extension library for kotlin. 

## Stringify with width

You can control string width on intetger string output.

``` kotlin
import net.ocsoft.toString
fun main() {
    println(123.toString(16, 5))
}
```

You get the followings.

```
0007b
```
