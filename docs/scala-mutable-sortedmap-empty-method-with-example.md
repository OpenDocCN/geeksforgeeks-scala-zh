# Scala 可变排序空()方法，示例

> 原文:[https://www . geesforgeks . org/Scala-mutatable-sorted map-empty-method-with-example/](https://www.geeksforgeeks.org/scala-mutable-sortedmap-empty-method-with-example/)

利用**清空()**方法清空 SortedMap。

> **方法定义:** def 空:SortedMap[A，B]
> 
> **返回类型:**返回空的 SortedMap。

**示例#1:**

```
// Scala program of empty()
// method
import scala.collection.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating a SortedMap
        val m1 = SortedMap("geeks" -> 5, "for" -> 3, "cs" -> 2)

        // Applying empty method
        val result = m1.empty

        // Displays output
        println(result)

    }
}
```

**Output:**

```
Map()

```

**例 2:**

```
// Scala program of empty()
// method
import scala.collection.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating an empty SortedMap
        val m1 = SortedMap("gopal" -> 10)

        // Applying empty method
        val result = m1.empty

        // Displays output
        println(result)

    }
}
```

**Output:**

```
Map()

```