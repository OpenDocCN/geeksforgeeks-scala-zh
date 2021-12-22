# Scala Int ^(x: Char)方法示例

> 原文:[https://www . geesforgeks . org/Scala-int-x-char-method-with-example-17/](https://www.geeksforgeeks.org/scala-int-x-char-method-with-example-17/)

**^(x:字符)**方法用于返回一个值，该值是 int 和指定字符值的按位异或运算的结果。这里的字符值是指定字符的 ASCII 值。

> **方法定义:** (Int_Value)。^(Char_Value)
> **返回类型:**它返回一个值，该值是 int 和指定 Char 值按位异或运算的结果。

**示例#1:**

```
// Scala program of Int ^(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int ^(x: Char) function
        val result = (15).^('A')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
78

```

**例 2:**

```
// Scala program of Int ^(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int ^(x: Char) function
        val result = (15).^('B')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
77

```