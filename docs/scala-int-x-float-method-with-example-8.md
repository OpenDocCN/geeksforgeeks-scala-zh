# 斯卡拉国际

T2】原文:[https://www . geeksforgeeks . org/Scala-int-x-float-method-with-example-8/](https://www.geeksforgeeks.org/scala-int-x-float-method-with-example-8/)

如果指定的 int 值小于 Float 值，则使用 **< (x: Float)** 方法返回 true，否则返回 false。

> **方法定义:** (Int_Value)。< (Float_Value)
> **返回类型:**如果指定的 int 值小于 Float 值，则返回 true，否则返回 false。

**示例#1:**

## 斯卡拉

```
// Scala program of Int <(x: Float)
// method

// Creating object
object GfG
{

    // Main method
    def main(args:Array[String])
    {

        // Applying Int <(x: Float) function
        val result = (100).<(110.0)

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

## 斯卡拉

```
// Scala program of Int <(x: Float)
// method

// Creating object
object GfG
{

    // Main method
    def main(args:Array[String])
    {

        // Applying Int <(x: Float) function
        val result = (50).<(10.0)

        // Displays output
        println(result)

    }
}
```

**Output:** 

```
false
```