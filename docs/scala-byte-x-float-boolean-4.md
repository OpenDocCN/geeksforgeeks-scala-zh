# 斯卡拉字节

> 原文:[https://www.geeksforgeeks.org/scala-byte-x-float-boolean-4/](https://www.geeksforgeeks.org/scala-byte-x-float-boolean-4/)T5】

在 Scala 中，Byte 是一个 8 位有符号整数(相当于 Java 的字节基元类型)。如果该值小于 x，则使用方法

> **方法定义:**字节< (x: Float):布尔值
> **返回类型:**如果该值小于 x，则返回 true，否则返回 false。

示例#1:

```
// Scala program of Byte <(x: Float)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte <(x: Float) function 
        val result = (64.toByte).<(12:Float) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
false
```

示例 2:

```
// Scala program of Byte <(x: Float)
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte <(x: Float) function 
        val result = (25.toByte).<(111:Float) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
true
```