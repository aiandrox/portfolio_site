---
title: "JS Sequence Diagram support"
date: 2018-11-18T12:00:06+09:00
description: "ふにゃった感じの応答のビジュアル図"
draft: false
enableToc: false
enableTocContent: false
tags:
-
series:
-
libraries:
- msc
image: images/feature2/transfer.png
series:
- Themes Guide
---

```msc
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

```msc
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow
```
