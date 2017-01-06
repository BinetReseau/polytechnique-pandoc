---
title: Basic test for pandoc
subtitle: How well does it work ?
author: Clément Durand

numbersections: true
toc: true
...

# About titles

## My subtitle

Hello World

![A normal image](normal.jpg){width=70%}

Another line of text.

\clearpage

# Let's try that

## Lists {#lists}

### Simple

- first
- second
- third

1. first
2. second
3. third

### Composed

-   a
    -   aa
    -   ab
-   b

1.  a
    -   aa
    -   ab
        1.  aba
        1.  abb
        1.  abc
    -   ac
1.  b

## Tables

Left-aligned      Centered      Right-aligned
-------------   ------------   --------------
test            test           test
red             green          blue


| Left | *Center* | Right |
| :--- | :----:   | ----: |
| test | test     | test  |
| a    | b        | c     |

## References

The section [lists](#lists) tackles many issues.
