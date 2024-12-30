---
title: Lớp và Đối Tượng Trong Java
date: 2024-12-30
tags: ["java", "lớp", "đối tượng"]
image: "/img/posts/img-71.jpg"
description: "Tìm hiểu về lớp và đối tượng trong Java - nền tảng của lập trình hướng đối tượng."
---

## Lớp và Đối Tượng Trong Java

Lớp (class) là một bản thiết kế cho các đối tượng. Đối tượng là một thực thể có dữ liệu và phương thức.

```java
public class Person {
    String name;
    int age;
    
    public void greet() {
        System.out.println("Hello " + name);
    }
}
