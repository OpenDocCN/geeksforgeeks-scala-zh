# Scala SortedMap 带例取()方法

> 原文:[https://www . geesforgeks . org/Scala-sorted map-take-method-with-example/](https://www.geeksforgeeks.org/scala-sortedmap-take-method-with-example/)

利用 **take()** 方法选择 SortedMap 的前 n 个元素。

> **方法定义:** def take(n: Int): SortedMap[A，B]
> 
> **返回类型:**返回 SortedMap 的前 n 个元素。

**示例#1:**

```
// Scala program of take()
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating a SortedMap
        val m1 = SortedMap(3 -> "geeks", 4 -> "for", 2 -> "cs")

        // Applying take method
        val result = m1.take(2)

        // Displays output
        println(result)

    }
}
```

**Output:**

```
Map(2 -> cs, 3 -> geeks)

```

**例 2:**

```
// Scala program of take()
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating a SortedMap
        val m1 = SortedMap(3 -> "geeks", 4 -> "for", 2 -> "cs")

        // Applying take method
        val result = m1.take(4)

        // Displays output
        println(result)

    }
}
```

**Output:**

```
Map(2 -> cs, 3 -> geeks, 4 -> for)

```