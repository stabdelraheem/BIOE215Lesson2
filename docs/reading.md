#### Sections 3-3.6.2 in [Chapter 3: Vectors](https://adv-r.hadley.nz/vectors-chap.html)

##### 3.1 Introduction

-   Vector data types

    -   Atomic vectors: all elements share the same data type

    -   Lists: data types can differ across elements

    -   Null is related but it's own thing - usually used as a 0-length vector

        ![](https://d33wubrfki0l68.cloudfront.net/2ff3a6cebf1bb80abb2a814ae1cfc67b12817713/ae848/diagrams/vectors/summary-tree.png){width="346"}

    -   Vector attributes = metadata

    -   Dimension + Class (date-time, factor, data frames, tibbles) attributes

    -   2D matrices and data frames are treated as vectors in R

    ##### QUIZ!

-   **What are the four common types of atomic vectors? What are the two rare types?**

-   **What are attributes? How do you get them and set them?**

-   **How is a list different from an atomic vector? How is a matrix different from a data frame?**

-   **Can you have a list that is a matrix? Can a data frame have a column that is a matrix?**

-   **How do tibbles behave differently from data frames?**

##### 3.2 Atomic Vectors

![](https://d33wubrfki0l68.cloudfront.net/eb6730b841e32292d9ff36b33a590e24b6221f43/57192/diagrams/vectors/summary-tree-atomic.png){width="295"}

#### Bryan 2018

-   The basic git commands are commit, push, and pull. Which commands change happen locally (i.e., on your computer)? Which happen remotely?

    -   Commit occurs locally. Push and Pull happen remotely.

-   Why do diffs work for source code (e.g., .R files) but not Word documents (i.e., .docx files)?

    -   Word and excel documents are binary files that are stored as a set of files on your computer that is then processed and displayed for the user using a GUI, and is therefore human-readable. Source code files (i.e. .txt, .md, .html, .Rmd, .csv) are smaller text files in which information is stored and configured much more simply. Although text files don't exist in a format that is "casually" readable, they are important and easier to track diffs than in large binary files.

-   Why is Markdown useful for GitHub repos?

    -   Markdown is a lightweight markup language that uses HTML conventions. The `index.md` file, if updated regularly, can serve as a homepage for a code project on GitHub with minimal effort to create auxiliary pages and structures. R Markdown also includes chunks of code embedded in explanations and is a great way to create interactive code projects that walk a user through beginning to end.
