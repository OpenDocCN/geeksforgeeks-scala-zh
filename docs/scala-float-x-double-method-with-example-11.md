# Scala Float > =(x: Double)方法示例

> 原文:[https://www . geesforgeks . org/Scala-float-x-double-method-with-example-11/](https://www.geeksforgeeks.org/scala-float-x-double-method-with-example-11/)

如果浮点值大于或等于指定的双精度值，则使用 **> =(x: Double)** 方法返回真。

> **方法定义:** (Float_Value)。> =(Double_Value)
> **返回类型:**如果浮点值大于或等于指定的双精度值，则返回 true。

**示例#1:**

```
// Scala program of Float >=(x: Double)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying >=(x: Double) function
        val result = (100.0).>=(60)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
true

```

**例 2:**

```
// Scala program of Float >=(x: Double)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying >=(x: Double) function
        val result = (10.0).>=(60)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```