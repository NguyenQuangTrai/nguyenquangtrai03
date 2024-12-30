---
title: Xử Lý Ngoại Lệ Trong Java
date: 2024-12-30
tags: ["java", "ngoại lệ"]
image: "/img/posts/img-91.jpg"
description: "Tìm hiểu cách xử lý ngoại lệ trong Java để ứng dụng của bạn trở nên ổn định và dễ bảo trì."
---

## Xử Lý Ngoại Lệ Trong Java

Xử lý ngoại lệ giúp bạn kiểm soát các lỗi xảy ra trong chương trình, giữ cho ứng dụng không bị dừng đột ngột.

```java
try {
    int result = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Error: " + e.getMessage());
}
