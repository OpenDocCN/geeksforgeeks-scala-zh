# Scala TreeSet max()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-treeset-max-method-with-example/](https://www.geeksforgeeks.org/scala-treeset-max-method-with-example/)

利用 **max()** 方法返回树集中最大的方法。

> **方法定义:** def 最大值:A
> 
> **返回类型:**返回树集中最大的元素。

**示例#1:**

```
// Scala program of max() 
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
        val q1 = TreeSet(1, 2, 3, 4, 5)  

        // Print the TreeSet 
        println(q1) 

        // Applying max method  
        val result = q1.max  

        // Displays output  
        print("Largest element in the TreeSet: " + result) 

    } 
} 
```

**Output:**

```
TreeSet(1, 2, 3, 4, 5)
Largest element in the TreeSet: 5

```

**例 2:**

```
// Scala program of max() 
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
        val q1 = TreeSet("u", "a", "i", "o", "e")  

        // Print the TreeSet 
        println(q1) 

        // Applying max method  
        val result = q1.max  

        // Displays output  
        print("Largest element in the TreeSet: " + result) 

    } 
} 
```

**Output:**

```
TreeSet(a, e, i, o, u)
Largest element in the TreeSet: u

```