# The Art of Writing Efficient Programs

An advanced programmer's guide to efficient hardware utilization and compiler optimizations using C++ examples

(*这是一本高级程序员指南，使用C*++的例子介绍如何高效利用硬件和优化编译器*)

* 作者：Fedor G. Pikus

* 译者：陈晓伟

* 首次发布时间：2021年10月22日([来源](https://www.amazon.com/Art-Writing-Efficient-Programs-optimizations/dp/1800208111/ref=sr_1_1?crid=3TMU5SFAS6D5M&keywords=The+Art+of+Writing+Efficient+Programs&qid=1643976993&sprefix=%E7%BE%8E%E5%9B%BD%E4%BA%9A%E9%A9%ACthe+art+of+writing+efficient+programs%E9%80%8A%2Caps%2C657&sr=8-1))

> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

*Get to grips with various performance improvement techniques such as concurrency, lock-free  programming, atomic operations, parallelism, and memory management.*

The great free lunch of "performance taking care of itself" is over. Until recently, programs got faster by themselves as CPUs were upgraded, but that doesn't happen anymore. The clock frequency of new processors has almost peaked. New architectures provide small improvements to existing programs, but this only helps slightly. Processors do get larger and more powerful, but most of this new power is consumed by the increased number of processing cores and other "extra" computing units. To write efficient software, you now have to know how to program by making good use of the available computing resources, and this book will teach you how to do that.

The book covers all the major aspects of writing efficient programs, such as using CPU resources and memory efficiently, avoiding unnecessary computations, measuring performance, and how to put concurrency and multithreading to good use. You'll also learn about compiler optimizations and how to use the programming language (C++) more efficiently. Finally, you'll understand how design decisions impact performance.

By the end of this book, you'll not only have enough knowledge of processors and compilers to write efficient programs, but you'll also be able to understand which techniques to use and what to measure while improving performance. At its core, this book is about learning how to learn.

#### 关键特性

- Understand the limitations of modern CPUs and their performance impact
- Find out how you can avoid writing inefficient code and get the best optimizations from the compiler
- Learn the tradeoffs and costs of writing high-performance programs

#### 内容纲要

- Discover how to use the hardware computing resources in your programs effectively
- Understand the relationship between memory order and memory barriers
- Familiarize yourself with the performance implications of different data structures and organizations
- Assess the performance impact of concurrent memory accessed and how to minimize it
- Discover when to use and when not to use lock-free programming techniques
- Explore different ways to improve the effectiveness of compiler optimizations
- Design APIs for concurrent data structures and high-performance data structures to avoid inefficiencies



## 适读人群

This book is for experienced developers and programmers who work on performance-critical projects and want to learn different techniques to improve the performance of their code. Programmers who belong to algorithmic trading, gaming, bioinformatics, computational genomics, or computational fluid dynamics  communities can learn various techniques from this book and apply them in their domain of work.

Although this book uses the C++ language, the concepts demonstrated in the book can be easily transferred or applied to other compiled languages such as C, Java, Rust, Go, and more.

## 作者简介

Fedor G Pikus is a Chief Engineering Scientist in the Design to Silicon division of Mentor Graphics Corp (Siemens business). His earlier positions included a Senior Software Engineer at Google and a Chief Software Architect for Calibre PERC, LVS, DFM at Mentor Graphics. He joined Mentor Graphics in 1998 when he made a switch from academic research in computational physics to the software industry. Fedor is a recognized expert on high-performance computing and C++, he presented his works at CPPCon, SD West, DesignCon, in Software Development Journal, and is also an O'Reilly author. His responsibilities as a Chief Scientist include planning the long-term technical direction of Calibre products, directing and training the engineers who work on these products, design, and architecture of the software, and research in the new design and software technologies. Fedor has over 25 patents and over 100 papers and conference presentations on physics, EDA, software design, and C++ language.

> I want to thank my wife, Galina, and my sons, Aaron and Benjamin, who supported and encouraged me and never lost faith in me, and my cat, Pooh, for cheering me up when I needed it.
>
> <p align="right"> —Fedor G. Pikus</p>

## 审评者介绍

**Sergey Gomon** started his journey in IT 12 years ago at Belarus State University of Informatics and Radioelectronics, in the Artificial Intelligence department. He has about 8 years of industrial programming experience using C++ in several fields, including network programming, information security, and image processing. He currently works at N-able and is an activist in the CoreHard C++ community.



## 本书相关

* github翻译地址：
* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html 

