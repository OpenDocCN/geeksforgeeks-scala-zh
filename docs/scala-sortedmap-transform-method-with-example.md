# Scala SortedMap 变换()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-sorted map-transform-method-with-example/](https://www.geeksforgeeks.org/scala-sortedmap-transform-method-with-example/)

**transform()** 方法用于将 SortedMap 的元素转换为可变的 SortedMap。

> **方法定义:** def 变换(f: (K，V)=>V:sorted map . this . type
> 
> **返回类型:**它转换 SortedMap 的所有元素，并将它们返回到一个可变的 SortedMap 中。

**示例#1:**

```
// Scala program of transform()
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

        // Applying transform method
        val result = m1.transform((key, value) => value.toUpperCase)

        // Displays output
        println(result)

    }
}
```

**Output:**

```
Map(2 -> CS, 3 -> GEEKS, 4 -> FOR)

```

**例 2:**

```
// Scala program of transform()
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

        // Applying transform method
        val result = m1.transform((key, value) => value.toUpperCase)

        // Displays output
        println(result)

    }
}
```

**Output:**

```
Map(3 -> GEEKS, 4 -> FOR)

```