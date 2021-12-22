# Scala Int < =(x: Int)方法，示例

> 原文:[https://www . geesforgeks . org/Scala-int-x-int-method-with-example-7/](https://www.geeksforgeeks.org/scala-int-x-int-method-with-example-7/)

如果指定的第一个 int 值小于或等于第二个 Int 值，则使用 **< =(x: Int)** 方法返回 true，否则返回 false。

> **方法定义:** (First_Int_Value)。< =(秒 _Int_Value)
> 
> **返回类型:**如果指定的第一个 int 值小于或等于第二个 int 值，则返回 true，否则返回 false。

**示例#1:**

```
// Scala program of Int <=(x: Int)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int <=(x: Int) function
        val result = (10).<=(100)

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
// Scala program of Int <=(x: Int)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int <=(x: Int) function
        val result = (500).<=(100)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```