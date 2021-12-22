# 斯卡拉飘！=(x:短)方法，示例

> 原文:[https://www . geesforgeks . org/Scala-float-x-short-method-with-example-9/](https://www.geeksforgeeks.org/scala-float-x-short-method-with-example-9/)

**！=(x: Short)** 方法用于检查给定的 Float 和 Short 值是否相等。

> **方法定义:** (Float_Value)！=(x:短)
> 
> **返回类型:**如果给定的 Float 和 Short 值不相等，则返回 true，否则返回 false。

**示例#1:**

```
// Scala program of Float !=(x: Short)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying !=(x: Short) function
        val result = (65.0).!=(65.0)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```

**例 2:**

```
// Scala program of Float !=(x: Short)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying !=(x: Short) function
        val result = (65.0).!=(45)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```