# Scala TreeSet 克隆()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-treeset-clone-method-with-example/](https://www.geeksforgeeks.org/scala-treeset-clone-method-with-example/)

在 Scala `TreeSet class`中，**克隆()**方法用于创建给定树集的副本。

> **方法定义:** def 克隆():队列[A]
> 
> **返回类型:**它返回一个新的树集，它是给定树集的副本。

**示例#1:**

```
// Scala program of clone() 
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
        val t1 = TreeSet(2, 1, 3, 4, 5) 

        // Print the TreeSet
        println(t1) 

        // Applying clone() method  
        val result = t1.clone

        // Displays output 
        println("Clone of the TreeSet: " + result)

    } 
} 
```

**Output:**

```
TreeSet(1, 2, 3, 4, 5)
Clone of the TreeSet: TreeSet(1, 2, 3, 4, 5)

```

**例 2:**

```
// Scala program of clone() 
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
        val t1 = TreeSet("a", "e", "i", "o", "u") 

        // Print the TreeSet
        println(t1) 

        // Applying clone() method  
        val result = t1.clone

        // Displays output 
        println("Clone of the TreeSet: " + result)

    } 
} 
```

**Output:**

```
TreeSet(a, e, i, o, u)
Clone of the TreeSet: TreeSet(a, e, i, o, u)

```