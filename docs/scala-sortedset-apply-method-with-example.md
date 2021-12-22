# Scala SortedSet apply()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-sorted set-apply-method-with-example/](https://www.geeksforgeeks.org/scala-sortedset-apply-method-with-example/)

**apply()** 方法用于测试排序集中是否存在某些元素。

> **方法定义:**定义应用(元素:A)
> 
> **返回类型:**如果 SortedSet 中存在某些元素，则返回 true，否则返回 false。

**示例#1:**

```
// Scala program of apply()
// method
import scala.collection.immutable.SortedSet 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Creating SortedSets 
        val s1 = SortedSet(1, 2, 3, 4, 5) 

        // Applying apply method 
        val result = s1.apply(3) 

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
// Scala program of apply()
// method
import scala.collection.immutable.SortedSet 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Creating SortedSets 
        val s1 = SortedSet(1, 2, 3, 4, 5) 

        // Applying apply method 
        val result = s1.apply(10) 

        // Displays output 
        println(result) 

    } 
} 
```

**Output:**

```
false

```