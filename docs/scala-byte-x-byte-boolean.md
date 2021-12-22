# Scala Byte ！=（x： Byte）： 布尔值

> 原文:[https://www.geeksforgeeks.org/scala-byte-x-byte-boolean/](https://www.geeksforgeeks.org/scala-byte-x-byte-boolean/)

在 Scala 中，Byte 是一个 8 位有符号整数(相当于 Java 的字节基元类型)。方法！=(x:Byte)方法用于在值不等于指定值 x 时返回 true，否则返回 false。

> **方法定义:**字节！=(x: Byte): Boolean
> **返回类型:**如果值不等于指定值则返回 true，否则返回 false。

示例#1:

```
// Scala program of Byte !=(x: Byte) 
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte !=(x: Byte) function 
        val result = (100.toByte).!=(50:Byte) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
true
```

示例 2:

```
// Scala program of Byte !=(x: Byte) 
// method 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Applying Byte !=(x: Byte) function 
        val result = (100.toByte).!=(100:Byte) 

        // Displays output 
        println(result) 

    } 
} 
```

**输出:**

```
false
```