# Scala Byte toFloat()方法

> 原文:[https://www.geeksforgeeks.org/scala-byte-tofloat-method/](https://www.geeksforgeeks.org/scala-byte-tofloat-method/)

在 Scala 中，Byte 是一个 8 位有符号整数(相当于 Java 的字节基元类型)。toFloat()方法用于将指定的数字转换为浮点数据类型值。

> **方法定义:**(数字)。toFloat
> 
> **返回类型:**返回转换后的浮点值。

**示例#1:**

```
// Scala program of Byte toFloat() 
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying toFloat method 
        val result = (13).toFloat

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
13.0

```

**例 2:**

```
// Scala program of Byte toFloat() 
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying toFloat method 
        val result = (123).toFloat

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
123.0

```