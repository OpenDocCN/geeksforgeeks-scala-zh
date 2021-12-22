# Scala SortedMap 迭代器方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-sorted map-iterator-method-with-example/](https://www.geeksforgeeks.org/scala-sortedmap-iterator-method-with-example/)

利用**迭代器**方法给出一个迭代器。

> **方法定义:**定义迭代器:迭代器[(A，B)]
> 
> **返回类型:**为非空 SortedMap 返回非空迭代器，为空 SortedMap 返回空迭代器。

**示例#1:**

```
// Scala program of iterator
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating a SortedMap
        val m1 = SortedMap("geeks" -> 5, "for" -> 3, "cs" -> 2) 

        // Applying iterator method
        val result = m1.iterator

        // Displays output
        println(result)

    }
}
```

**Output:**

```
non-empty iterator

```

**例 2:**

```
// Scala program of iterator
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating a SortedMap
        val m1 = SortedMap( "cs" -> 2) 

        // Applying iterator method
        val result = m1.iterator

        // Displays output
        println(result)

    }
}
```

**Output:**

```
non-empty iterator

```