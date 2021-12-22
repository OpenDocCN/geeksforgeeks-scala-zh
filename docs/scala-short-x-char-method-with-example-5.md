# Scala Short %(x: Char)方法，示例

> 原文:[https://www . geesforgeks . org/Scala-short-x-char-method-with-example-5/](https://www.geeksforgeeks.org/scala-short-x-char-method-with-example-5/)

使用 **%(x: Char)** 方法来寻找所述短值除以 Char 类型的“x”的余数。

> **方法定义:** def %(x: Char): Int
> 
> **返回类型:**返回 Int。

**例:1#**

```
// Scala program of %(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying %(x: Char) method 
        val result = (1000).%('C')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
62

```

**例:2#**

```
// Scala program of %(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying %(x: Char) method
        val result = (1000).%('A')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
25

```