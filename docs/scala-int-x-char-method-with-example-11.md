# Scala Int > (x: Char)方法示例

> 原文:[https://www . geesforgeks . org/Scala-int-x-char-method-with-example-11/](https://www.geeksforgeeks.org/scala-int-x-char-method-with-example-11/)

如果指定的 int 值大于 Char 值，则使用 **> (x: Char)** 方法返回 true。这里的字符值是指定字符的 ASCII 值。

> **方法定义:** (Int_Value)。> (Char_Value)
> **返回类型:**如果指定的 int 值大于 Char 值，则返回 true。

**示例#1:**

```
// Scala program of Int >(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int >(x: Char) function
        val result = (66).>('A')

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
// Scala program of Int >(x: Char)
// method

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Applying Int >(x: Char) function
        val result = (50).>('A')

        // Displays output
        println(result)

    }
} 
```

**Output:**

```
false

```