---
title: Kế Thừa Trong Java
date: 2024-12-30
tags: ["java", "kế thừa"]
image: "/img/posts/img-81.jpg"
description: "Khám phá tính năng kế thừa trong Java và cách sử dụng để tái sử dụng mã."
---

## Kế Thừa Trong Java

Kế thừa cho phép một lớp kế thừa các thuộc tính và phương thức từ một lớp khác.

```java
public class Animal {
    public void makeSound() {
        System.out.println("Some sound");
    }
}

public class Dog extends Animal {
    @Override
    public void makeSound() {
        System.out.println("Bark");
    }
}
