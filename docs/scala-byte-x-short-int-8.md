# Scala Byte +(x: Short): Int

> 原文:[https://www.geeksforgeeks.org/scala-byte-x-short-int-8/](https://www.geeksforgeeks.org/scala-byte-x-short-int-8/)

在 Scala 中，Byte 是一个 8 位有符号整数(相当于 Java 的字节基元类型)。方法+(x:Short)方法用于返回该值与 x 的和

> **方法定义:** Byte +(x: Short): Int
> **返回类型:**它返回这个值的和乘以 x。

示例#1:

```
// Scala program of Byte +(x: Short)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte +(x: Short) function 
        val result = (167.toByte).+(125:Short) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
36
```

示例 2:

```
// Scala program of Byte +(x: Short)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte +(x: Short) function 
        val result = (167.toByte).+(2:Short) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
-87
```