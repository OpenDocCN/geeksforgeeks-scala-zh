# Scala SortedMap toArray()方法示例

> 原文:[https://www . geesforgeks . org/Scala-sorted map-to array-method-with-example/](https://www.geeksforgeeks.org/scala-sortedmap-toarray-method-with-example/)

**toArray()** 方法用于显示 Scala SortedMap 中的数组。

> **方法定义:**定义为数组:数组[(A，B)]
> 
> **返回类型:**从指定的 SortedMap 返回一个数组。

**示例#1:**

```
// Scala program of toArray()
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

        // Applying toArray method
        val result = m1.toArray

        for ( m5 <-result )
        {
           println(m5 )
        } 

    }
}
```

**Output:**

```
(3, geeks)
(4, for)

```

**例 2:**

```
// Scala program of toArray()
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

        // Applying toArray method
        val result = m1.toArray

        for ( m5 <-result )
        {
            // Display output
            println(m5 )
        } 

    }
}
```

**Output:**

```
(2, cs)
(3, geeks)
(4, for)

```