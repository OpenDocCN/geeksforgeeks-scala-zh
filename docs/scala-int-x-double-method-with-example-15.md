# Scala Int ^(x: Double)方法示例

> 原文:[https://www . geesforgeks . org/Scala-int-x-double-method-with-example-15/](https://www.geeksforgeeks.org/scala-int-x-double-method-with-example-15/)

**^(x: Double)** 方法用于返回一个值，该值是 int 和指定 Double 值的按位 XOR 运算的结果。

> **方法定义:** (Int_Value)。^(Double_Value)
> **返回类型:**它返回一个值，该值是 int 和指定的 Double 值的按位 XOR 运算的结果。

**示例#1:**

```
// Scala program of Int ^(x: Double)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int ^(x: Double) function
        val result = (15).^(2)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
13

```

**例 2:**

```
// Scala program of Int ^(x: Double)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int ^(x: Double) function
        val result = (15).^(3)

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
12

```