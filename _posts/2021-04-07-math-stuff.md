---
layout: blog-post
title: "Math stuff"
date: 2021-04-07 20:45:00 +1000
categories: [math, random]
description: Some math notes I've had lying around for a long time
---

## Set Theory

| Symbol        | Meaning                                                             | Example                                                       |
|---------------|---------------------------------------------------------------------|---------------------------------------------------------------|
| { }           | Set: a collection of elements                                       | {1, 2, 3, 4}                                                  |
| A ∪ B         | Union: in A or B (or both)                                          | C ∪ D = {1, 2, 3, 4, 5}                                       |
| A ∩ B         | Intersection: in both A and B                                       | C ∩ D = {3, 4}                                                |
| A ⊆ B         | Subset: every element of A is in B.                                 | {3, 4, 5} ⊆ D                                                 |
| A ⊂ B         | Proper Subset: every element of A is in B, but B has more elements. | {3, 5} ⊂ D                                                    |
| A ⊄ B         | Not a Subset: A is not a subset of B                                | {1, 6} ⊄ C                                                    |
| A ⊇ B         | Superset: A has same elements as B, or more                         | {1, 2, 3} ⊇ {1, 2, 3}                                         |
| A ⊃ B         | Proper Superset: A has B's elements and more                        | {1, 2, 3, 4} ⊃ {1, 2, 3}                                      |
| A ⊅ B         | Not a Superset: A is not a superset of B                            | {1, 2, 6} ⊅ {1, 9}                                            |
| A<sup>c</sup> | Complement: elements not in A                                       | D<sup>c</sup> = {1, 2, 6, 7} When `U` = {1, 2, 3, 4, 5, 6, 7} |
| A − B         | Difference: in A but not in B                                       | {1, 2, 3, 4} − {3, 4} = {1, 2}                                |
| a ∈ A         | Element of: a is in A                                               | 3 ∈ {1, 2, 3, 4}                                              |
| b ∉ A         | Not element of: b is not in A                                       | 6 ∉ {1, 2, 3, 4}                                              |
| ∅             | Empty set = {}                                                      | {1, 2} ∩ {3, 4} = Ø                                           |
|               |                                                                     |                                                               |
| \|            | Such that                                                           | { n \| n > 0 } = {1, 2, 3,...}                                |
| :             | Such that                                                           | { n : n > 0 } = {1, 2, 3,...}                                 |
| ∀             | For All                                                             | ∀ x > 1, 4*x > x                                              |
| ∃             | There Exists                                                        | ∃ x \| 4*x > x                                                |
|               |                                                                     |                                                               |
| `N`           | Natural numbers                                                     | {1, 2, 3,...} or {0, 1, 2, 3,...}                             |
| `Z`           | Integers Integers                                                   | {..., −3, −2, −1, 0, 1, 2, 3, ...}                            |
| `Q`           | Rational Numbers                                                    |                                                               |
| `A`           | Algebraic Numbers                                                   | Algebraic Numbers                                             |
| `R`           | Real Numbers                                                        |                                                               |
| `I`           | Imaginary Numbers                                                   | 3i                                                            |
| `C`           | Complex Numbers                                                     | 2 + 5i                                                        |
