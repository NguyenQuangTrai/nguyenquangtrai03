
---
title: Các Loại Vòng Lặp Trong Java
date: 2024-12-30
tags: ["java", "vòng lặp"]
image: "/img/posts/img-4.jpg"
description: "Tìm hiểu về các vòng lặp trong Java, bao gồm for, while và do-while."
---

## Các Loại Vòng Lặp

Java cung cấp 3 loại vòng lặp cơ bản:

1. **for loop**: Thích hợp cho các tình huống lặp với số lần xác định.
2. **while loop**: Thích hợp khi bạn không biết trước số lần lặp.
3. **do-while loop**: Chạy ít nhất một lần, ngay cả khi điều kiện không thỏa mãn.

```java
for(int i = 0; i < 5; i++) {
    System.out.println(i);
}
