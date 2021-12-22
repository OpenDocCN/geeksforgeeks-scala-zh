# Scala Char ^(x: Char)方法示例

> 原文:[https://www . geesforgeks . org/Scala-char-x-char-method-with-example-2/](https://www.geeksforgeeks.org/scala-char-x-char-method-with-example-2/)

**^(x:字符)**方法用于在自变量列表中找到所述字符和给定类型字符“x”的逐位异或。

> **方法定义:** def ^(x: Char): Int
> 
> **返回类型:**返回指定字符和给定字符类型“x”的逐位异或。

**例:1#**

```
// Scala program of ^(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ^(x: Char) method 
        val result = 'B'.^('D')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
6

```

**例:2#**

```
// Scala program of ^(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ^(x: Char) method
        val result = 'B'.^('b')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
32

```