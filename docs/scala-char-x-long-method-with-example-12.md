# Scala Char ==(x: Long)方法示例

> 原文:[https://www . geesforgeks . org/Scala-char-x-long-method-with-example-12/](https://www.geeksforgeeks.org/scala-char-x-long-method-with-example-12/)

利用 **==(x: Long)** 方法查找所述字符值是否等于‘x’。而‘x’的类型必须是 Long。

> **方法定义:** def ==(x: Long):布尔值
> 
> **返回类型:**如果所述字符值等于“x”，则返回真，否则返回假。

**例:1#**

```
// Scala program of ==(x: Long)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ==(x: Long) method 
        val result = 'D'.==(100000L)

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
// Scala program of ==(x: Long)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying ==(x: Long) method
        val result = 'Z'.==(90)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```