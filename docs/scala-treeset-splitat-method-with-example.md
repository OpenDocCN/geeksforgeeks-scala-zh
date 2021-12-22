# Scala TreeSet splitAt()方法示例

> 原文:[https://www . geesforgeks . org/Scala-treeset-splitat-method-with-example/](https://www.geeksforgeeks.org/scala-treeset-splitat-method-with-example/)

**splitAt()** 方法用于在指定位置将给定的树集合分割成树集合的前缀/后缀对。

> **方法定义:**def splitAt(n:Int):(TreeSet[A]，TreeSet[A])
> 其中，n 是我们需要拆分的位置。
> 
> **返回类型:**它返回一对由这个 TreeSet 的前 n 个元素和其他元素组成的 TreeSet。

**示例#1:**

```
// Scala program of splitAt() 
// method 

// Import TreeSet
import scala.collection.mutable._

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Creating TreeSet
        val t1 = TreeSet(3, 1, 5, 2, 4)  

        // Print the TreeSet 
        println(t1) 

        // Applying splitAt method  
        val result = t1.splitAt(2)

        // Displays output  
        print(result) 

    } 
} 
```

**Output:**

```
TreeSet(1, 2, 3, 4, 5)
(TreeSet(1, 2), TreeSet(3, 4, 5))

```

**例 2:**

```
// Scala program of splitAt() 
// method 

// Import TreeSet
import scala.collection.mutable._

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        // Creating TreeSet
        val t1 = TreeSet(3, 1, 5, 2, 4)  

        // Print the TreeSet 
        println(t1) 

        // Applying splitAt method  
        val result = t1.splitAt(3)

        // Displays output  
        print(result) 

    } 
} 
```

**Output:**

```
TreeSet(1, 2, 3, 4, 5)
(TreeSet(1, 2, 3), TreeSet(4, 5))

```