# Scala SortedMap toList()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-sorted map-to list-method-with-example/](https://www.geeksforgeeks.org/scala-sortedmap-tolist-method-with-example/)

利用 **toList()** 方法显示列表中 SortedMap 的元素。

> **方法定义:**定义为列表:列表[A]
> 
> **返回类型:**返回列表中 SortedMap 的所有元素。

**示例#1:**

```
// Scala program of toList()
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

        // Applying toList method
        val result = m1.toList

        // Displays output
        println(result)

    }
}
```

**Output:**

```
List((2, cs), (3, geeks), (4, for))

```

**例 2:**

```
// Scala program of toList()
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating a SortedMap
        val m1 = SortedMap(3 -> "geeks", 4 -> "for", 4 -> "for")

        // Applying toList method
        val result = m1.toList

        // Displays output
        println(result)

    }
}
```

**Output:**

```
List((3, geeks), (4, for))

```