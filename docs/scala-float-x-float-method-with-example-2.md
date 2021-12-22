# Scala Float < =(x: Float)方法示例

> 原文:[https://www . geesforgeks . org/Scala-float-x-float-method-with-example-2/](https://www.geeksforgeeks.org/scala-float-x-float-method-with-example-2/)

如果第一个浮点值小于或等于第二个浮点值，则使用 **< =(x: Float)** 方法返回真，否则返回假。

> **方法定义:** (First_Float_Value)。< =(秒 _ 浮动 _ 值)
> 
> **返回类型:**如果第一个浮点值小于或等于第二个浮点值，则返回 true，否则返回 false。

**示例#1:**

```
// Scala program of Float <=(x: Float)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying <=(x: Float) function
        val result = (100.0).<=(50.0)

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
// Scala program of Float <=(x: Float)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying <=(x: Float) function
        val result = (50.0).<=(100.0)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```