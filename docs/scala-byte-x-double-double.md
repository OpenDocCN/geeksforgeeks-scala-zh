# Scala 字节%(x: Double): Double

> 原文:[https://www.geeksforgeeks.org/scala-byte-x-double-double/](https://www.geeksforgeeks.org/scala-byte-x-double-double/)

在 Scala 中，Byte 是一个 8 位有符号整数(相当于 Java 的字节基元类型)。方法% x:Double 方法用于返回该值除以 x 的余数

> **方法定义:**字节%(x: Double): Double
> **返回类型:**它返回这个值除以 x 的余数。

示例#1:

```
// Scala program of Byte %(x: Double)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte %(x: Double) function 
        val result = (100.toByte).%(3:Double) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
1
```

示例 2:

```
// Scala program of Byte %(x: Double)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte %(x: Double) function 
        val result = (167.toByte).%(3:Double) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
-2.0
```