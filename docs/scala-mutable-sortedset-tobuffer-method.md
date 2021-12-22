# Scala 可变排序集 toBuffer()方法

> 原文:[https://www . geesforgeks . org/Scala-mutatable-sorted set-to buffer-method/](https://www.geeksforgeeks.org/scala-mutable-sortedset-tobuffer-method/)

在 Scala 可变集合中，SortedSet **toBuffer()** 方法用于返回由 SortedSet 的所有元素组成的缓冲区。

> **方法定义:**def to Buffer【B】>:A:Buffer【B】
> 
> **返回类型:**它返回由 SortedSet 的所有元素组成的缓冲区。

**示例#1:**

```
// Scala program of toBuffer() 
// method 
import scala.collection.mutable.SortedSet 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 
        // Creating a SortedSet 
        val s1 = SortedSet(1, 2, 3, 4, 5) 

        // Applying toBuffer method 
        val result = s1.toBuffer

        // Display output
        for (elem <- result)
            println(elem)

    } 
} 
```

**Output:**

```
1
2
3
4
5

```

**例 2:**

```
// Scala program of toBuffer() 
// method 
import scala.collection.mutable.SortedSet 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 
        // Creating a SortedSet 
        val s1 = SortedSet(41, 12, 23, 43, 1, 72) 

        // Applying toBuffer method 
        val result = s1.toBuffer

        // Display output
        for (elem <- result)
            println(elem)

    } 
} 
```

**Output:**

```
1
12
23
41
43
72

```