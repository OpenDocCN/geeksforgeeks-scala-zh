# 合并字节*(x:字节):Int

> 哎哎哎:# t0]https://www . geeksforgeeks . org/scale-byte-x-byte-int-2/

在 Scala 中，Byte 是一个 8 位有符号整数(相当于 Java 的字节基元类型)。方法*(x:Byte)用于返回这个值和 x 的乘积。

> **方法定义:** Byte *(x: Byte): Int
> **返回类型:**它返回这个值和 x 的乘积。

示例#1:

```
// Scala program of Byte *(x: Byte)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte *(x: Byte) function 
        val result = (64.toByte).*(12:Byte) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
768
```

示例 2:

```
// Scala program of Byte *(x: Byte)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte *(x: Byte) function 
        val result = (125.toByte).*(11:Byte) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
1375
```