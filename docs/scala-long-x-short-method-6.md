# Scala 长+(x:短)法

> 原文:[https://www.geeksforgeeks.org/scala-long-x-short-method-6/](https://www.geeksforgeeks.org/scala-long-x-short-method-6/)

在 Scala 中，long 是 64 位有符号整数，相当于 Java 的 Long 基元类型。 **+(x:短)**方法用于返回该值与给定值 x 之和。

> **方法定义–**def+(x:短):长
> 
> **返回–**返回该值与 x 之和。

**示例#1:**

```
// Scala program to explain the working 
// of Long +(x: Short) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying +(x: Short) function
        val result = (12.0021.toLong).+(13:Short)

        // Displays output
        println(result)

    }
} 
```

**输出:**

```
25

```