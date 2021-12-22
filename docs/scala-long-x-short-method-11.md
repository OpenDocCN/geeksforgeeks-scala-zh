# Scala 长(x:短)法

> 原文:[https://www.geeksforgeeks.org/scala-long-x-short-method-11/](https://www.geeksforgeeks.org/scala-long-x-short-method-11/)

在 Scala 中，long 是 64 位有符号整数，相当于 Java 的 Long 基元类型。当给定的长值除以短值时，使用 **%(x:短)**方法返回余数。

> **方法定义–**def %(x:短)
> 
> **返回–**返回该值除以 x 的余数。

**示例#1:**

```
// Scala program to explain the working 
// of Long %(x: Short) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying %(x: Short) function
        val result = (165.toLong).%(13:Short)

        // Displays output
        println(result)

    }
}
```

**输出:**

```
9
```

**例 2:**

```
// Scala program to explain the working 
// of Long %(x: Short) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying %(x: Short) function
        val result = (65.toLong).%(13:Short)

        // Displays output
        println(result)

    }
}
```

**输出:**

```
0
```