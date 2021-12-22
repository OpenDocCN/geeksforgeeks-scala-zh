# Scala SortedMap min()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-sorted map-min-method-with-example/](https://www.geeksforgeeks.org/scala-sortedmap-min-method-with-example/)

利用 **min()** 方法寻找排序地图的最小元素。

> **方法定义:** def min: (A，B)
> 
> **返回类型:**返回 SortedMap 的最小元素。

**示例#1:**

```
// Scala program of min()
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating SortedMap
        val m1 = SortedMap("geeks" -> 5, "for" -> 3, "cs" -> 2)

        // Applying min method 
        val result = m1.min

        // Displays output
        println(result)
    }
}
```

**Output:**

```
(cs, 2)

```

正如我们在上面的例子中看到的 **cs** 是 SortedMap 中最小的元素。
**例 2:**

```
// Scala program of min()
// method
import scala.collection.immutable.SortedMap

// Creating object
object GfG
{ 

    // Main method
    def main(args:Array[String])
    {

        // Creating SortedMap
        val m1 = SortedMap("geeks" -> 5, "for" -> 3, "for" -> 6)

        // Applying min method 
        val result = m1.min

        // Displays output
        println(result)
    }
}
```

**Output:**

```
(for, 6)

```