---
title: ArrayList vs LinkedList — What I Actually Understood
description: A simple explanation of the difference between ArrayList and LinkedList in Java collections.
publishDate: 2026-08-02
tags:
  - Java
  - Collections
draft: true
---

I have been learning Java recently and one thing I find confusing is the difference between ArrayList and LinkedList.

Both are used to store multiple objects but the way they work is different. ArrayList uses an array inside so when we add more things it can increase its size. LinkedList uses nodes and each node is connected with another node.

I first thought LinkedList is always faster because it dont need to move elements but this is not completely true. For example if we want to get element from middle ArrayList is usually faster because it can directly go to that index. Linkedlist has to go through nodes one by one which can take more time.

But when inserting and removing elements, LinkedList can be better in some situations. Still I think we should not just say LinkedList is faster. It depends on what our program is doing and how frequently we access or modify the data.

This was something I understood while learning Java collections and I think understanding the reason behind the difference is more useful than just remembering which one is faster.

Also there are many other collection classes in Java and I want to learn them properly instead of just using them without knowing what happens internally.
