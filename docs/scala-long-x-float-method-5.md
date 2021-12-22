# Scala Long +(x: Float)方法

> 原文:[https://www.geeksforgeeks.org/scala-long-x-float-method-5/](https://www.geeksforgeeks.org/scala-long-x-float-method-5/)

在 Scala 中，long 是 64 位有符号整数，相当于 Java 的 Long 基元类型。 **+(x: Float)** 方法用于返回该值与给定值 x 之和。

> **方法定义–**def+(x:Float):Float
> 
> **返回–**返回该值与 x 之和。

**示例#1:**

```
// Scala program to explain the working 
// of Long +(x: Float) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying +(x: Float) function
        val result = (12.0021.toLong).+(8:Float)

        // Displays output
        println(result)

    }
} 
```

**输出:**

```
20.0

```