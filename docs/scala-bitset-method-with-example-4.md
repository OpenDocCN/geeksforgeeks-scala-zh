# Scala BitSet & ~()方法示例

> 原文:[https://www . geeksforgeeks . org/Scala-bitset-method-with-example-4/](https://www.geeksforgeeks.org/scala-bitset-method-with-example-4/)

Scala 位集是由非负整数组成的集合，这些整数被表示为大小可变的位数组，这些位被打包成 64 位的字。&~()方法用于通过执行按位“与非”来计算该位集和另一位集的差。

> **方法定义:** def & ~()
> 
> **返回类型:**它返回一个新的位集，该位集由给定位集中不包含的所有元素组成。

**示例#1:**

```
// Scala program of Bitset &~
// method 
import scala.collection.immutable.BitSet 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        val b1: BitSet = BitSet(41, 12, 23, 43, 1, 72) 
        val b2: BitSet = BitSet(1, 100, 55, 32, 23) 

        // Applying BitSet &~() function 
        val bs1: BitSet = b1 &~ (b2)

        // Displays output 
        println(bs1) 

    } 
} 
```

**Output:**

```
BitSet(12, 41, 43, 72)

```

**例 2:**

```
// Scala program of Bitset &~
// method 
import scala.collection.immutable.BitSet 

// Creating object 
object GfG 
{ 

    // Main method 
    def main(args:Array[String]) 
    { 

        val b1: BitSet = BitSet(41, 12, 23, 43, 1, 72) 

        // Applying BitSet &~() function 
        val bs1: BitSet = b1 &~ BitSet(1, 100, 5, 12, 23) 

        // Displays output 
        println(bs1) 

    } 
} 
```

**Output:**

```
BitSet(41, 43, 72)

```