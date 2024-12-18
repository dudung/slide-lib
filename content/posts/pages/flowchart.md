+++
title = 'flowchart'
date = 2024-12-17T05:25:04+07:00
type = 'xpage2'
draft = false
categories = ['pages']
tags = ['slide-lib']
authors = ['viridi']
+++
<!--more-->

+ A simple flowchart is as follow.
{{< mermaid >}}
flowchart LR
  B --> I --> C
  C --"Y"--> P1
  C --"N"--> P2
  P1 & P2 --> O --> E
  B(["Begin"])
  I[/"Input"/]
  C{"Condition"}
  P1["Process 1"]
  P2["Process 2"]
  O[/"Output"/]
  E(["End"])
{{< /mermaid >}}
+ Common shapes are Begin / End, Input / Output, Condition, and Process.