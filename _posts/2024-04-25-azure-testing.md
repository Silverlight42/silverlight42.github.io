---
layout: post
title: "Azure Spark Databricks Long Title Testing"
date: 2024-04-25 00:00:00 -0000
categories: CATEGORY-1 Azure Spark
---

# Testing

Sample

```scala
class Point(var x: Int, var y: Int) {

  def move(dx: Int, dy: Int): Unit = {
    x = x + dx
    y = y + dy
  }

  override def toString: String =
    s"($x, $y)"
}

val point1 = new Point(2, 3)
println(point1.x)  // prints 2
println(point1)    // prints (2, 3)
```