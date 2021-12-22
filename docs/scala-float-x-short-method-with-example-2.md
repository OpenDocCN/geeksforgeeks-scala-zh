# Scala Float < =(x: Short)方法示例

> 原文:[https://www . geesforgeks . org/Scala-float-x-short-method-with-example-2/](https://www.geeksforgeeks.org/scala-float-x-short-method-with-example-2/)

如果浮点值小于或等于短值，则使用 **< =(x:短)**方法返回真，否则返回假。

> **方法定义:** (Float_Value)。< =(短值)
> 
> **返回类型:**如果浮点值小于或等于短值，则返回真，否则返回假。

**示例#1:**

```
// Scala program of Float <=(x: Short)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying <=(x: Short) function
        val result = (100.0).<=(50)

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
// Scala program of Float <=(x: Short)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying <=(x: Short) function
        val result = (50.0).<=(100)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```