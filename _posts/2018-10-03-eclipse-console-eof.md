---
layout: post 
title: Не работает ctrl+d в консоли Eclipse
tags: [IDE, eclipse, macos]
---

Escape-символ для завершения ввода срабатывает в Eclipse через раз, а в терминале работает без проблем.

<!--more-->

Допустим, необходимо записать неопределенное количество строк с консоли в ArrayList. 
```java
// Считать карту с консоли
while (in.hasNext()) {
	mapList.add(in.nextLine());
}
```
Для того, чтобы завершить ввод, нужно перевести каретку на новую строку (`Enter`) и ввести escape-символ (`Ctrl+D`), но это не всегда срабатывает в Eclipse. 

**Решение проблемы:** кликните по области с кодом, а затем - по области консоли и еще раз нажмите `Ctrl+D`. Это все.