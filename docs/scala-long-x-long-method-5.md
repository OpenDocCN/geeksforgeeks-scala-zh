# 斯卡拉隆

T2】原文:[https://www.geeksforgeeks.org/scala-long-x-long-method-5/](https://www.geeksforgeeks.org/scala-long-x-long-method-5/)T5】

在 Scala 中，long 是 64 位有符号整数，相当于 Java 的 Long 基元类型。如果该值小于 x，则使用 **< (x:龙)**方法返回真，否则返回假。

> **方法定义–**定义< (x:长):布尔值
> 
> **返回–**如果该值小于 x，则返回真，否则返回假。

**示例#1:**

```
// Scala program to explain the working 
// of Long <(x: Long) method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying <(x: Long) function
        val result = (12.toLong).<(8:Long)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```