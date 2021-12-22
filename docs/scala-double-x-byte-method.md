# Scala Double ==(x: Byte)方法

> 原文:[https://www.geeksforgeeks.org/scala-double-x-byte-method/](https://www.geeksforgeeks.org/scala-double-x-byte-method/)

在 Scala 中，double 是一个 64 位的浮点数，相当于 Java 的 Double 原语类型。如果该值等于 x，则使用 **==(x: Byte)** 方法返回真，否则返回假。

> **方法定义–**def = =(x:Byte):布尔值
> 
> **返回–**如果该值等于 x，则返回 true，否则返回 false。

**示例#1:**

```
// Scala program to explain the working 
// of Double ==(x: Byte) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ==(x: Byte) function
        val result = (12.00123.toDouble).==(12:Byte)

        // Displays output
        println(result)

    }
} 
```

**输出:**

```
false

```