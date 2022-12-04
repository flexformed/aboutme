---
title: "Second post 2"
date: 2022-12-03T23:07:31+01:11
draft: false
mermaid: true
---

---mermaid

graph TD;
  A-->B;
  A-->C;
  B-->D;
  C-->D;

--- 

memo

<mermaid>
graph LR;
   A[sheets ream<sup>-1</sup> <br> 500] -->|-1| B[thickness <br> 10<sup>-2</sup>cm <br>] 
   C[thickness ream<sup>-1</sup> <br> 5cm] --> B
   B --> D[volume <br> 1cm<sup>3</sup>]
   E[height <br> 6cm] --> D
   F[width <br> 15cm] --> D
</mermaid>
