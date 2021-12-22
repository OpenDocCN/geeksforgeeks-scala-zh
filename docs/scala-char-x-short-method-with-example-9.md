# Scala Char ==(x: Short)方法示例

> 原文:[https://www . geesforgeks . org/Scala-char-x-short-method-with-example-9/](https://www.geeksforgeeks.org/scala-char-x-short-method-with-example-9/)

使用 **==(x: Short)** 方法来查找所述字符值是否等于“x”。“x”的类型必须是“短”。

> **方法定义:** def ==(x: Short):布尔值
> 
> **返回类型:**如果所述字符值等于“x”，则返回真，否则返回假。

**例:1#**

```
// Scala program of ==(x: Short)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ==(x: Short) method 
        val result = 'D'.==(10000)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```

**例:2#**

```
// Scala program of ==(x: Short)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ==(x: Short) method
        val result = 'D'.==(68)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```