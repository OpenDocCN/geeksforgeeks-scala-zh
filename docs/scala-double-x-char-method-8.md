# Scala Double /(x: Char)方法

> 原文:[https://www.geeksforgeeks.org/scala-double-x-char-method-8/](https://www.geeksforgeeks.org/scala-double-x-char-method-8/)

在 Scala 中，double 是一个 64 位的浮点数，相当于 Java 的 Double 原语类型。 **/(x: Char)** 方法用于返回该值与给定值 x 的商。

> **方法定义–**def/(x:Char):Double
> 
> **返回–**返回该值与 x 的商。

**示例#1:**

```
// Scala program to explain the working 
// of Double /(x: Char) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying /(x: Int) function
        val result = (172.0021.toDouble)./('A':Char)

        // Displays output
        println(result)

    }
} 
```

**输出:**

```
2.646186153846154

```