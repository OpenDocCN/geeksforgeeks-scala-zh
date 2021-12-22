# Scala Int abs()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-int-ABS-method-with-example/](https://www.geeksforgeeks.org/scala-int-abs-method-with-example/)

利用 **abs()** 方法返回给定整数值的绝对值。任何数的绝对值都是该数的大小，即没有任何符号。

> **方法定义:**(有符号 _ 整数 _ 值)。abs
> **返回类型:**返回给定有符号整数值的绝对值。

**示例#1:**

```
// Scala program of Int abs()
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying abs method
        val result = (-5).abs

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
5

```

**例 2:**

```
// Scala program of Int abs()
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying abs method
        val result = (+65).abs

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
65

```