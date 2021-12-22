# Scala Char *(x: Short)方法，示例

> 原文:[https://www . geesforgeks . org/Scala-char-x-short-method-with-example-14/](https://www.geeksforgeeks.org/scala-char-x-short-method-with-example-14/)

利用 ***(x: Short)** 方法求所述字符值与 Short 类型的‘x’的乘积。

> **方法定义:** def *(x: Short): Int
> 
> 返回类型:返回 Int。

**示例:1#**

```
// Scala program of *(x: Short)
// method

// Creating object
object GfG
{  

// Main method
def main(args:Array[String])
{

// Applying *(x: Short) method 
val result = 'E'.*(1000)

// Displays output
println(result)

   }
} 
```

**输出:**

```
69000

```

**示例:2#**

```
// Scala program of *(x: Short)
// method

// Creating object
object GfG
{  

// Main method
def main(args:Array[String])
{

// Applying *(x: Short) method
val result = 'A'.*(-1000)

// Displays output
println(result)

   }
} 
```

**输出:**

```
-6500

```