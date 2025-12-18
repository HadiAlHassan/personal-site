+++
date = 2025-12-17T01:14:54-08:00
draft = false
title = 'Why do we name our Loops i, j, and k?'
weight = 10
[params]
  author = 'Hadi Al Hassan'
+++

So I was tutoring someone for the programming 1 exam, and as I was explaining the concept of looping they asked me: "Why do we always name the variable for our loops i, j, and k?".

And I froze for a second, the only response I could give was: "because that's how it always been..."


Then I got to thinking, why out of all the possible names someone could choose when looping over something, why i? why not index? is i short for index? but then why j comes next, then k? is it alphabetical order?


So I did some digging and the answer was quite simple.

The original computer scientists where mathematicians, and in their proofs mathematicians used i,j, and k to represent summations, especially nested ones.

{{< katex >}}
\(\displaystyle \sum_{i=0}^{n} something\)

{{< katex >}}
\(\displaystyle \sum_{i=0}^{n} \sum_{j=0}^{n} \sum_{k=0}^{n}something\)

Additionally, vectors are represented using
{{< katex >}}
\(\vec{i}, \vec{j}, and \vec{k}\)

And have been since the 19th century.

And once programming languages came on, and people needed to loop, people resorted to the famous trio of letters (they are i,j, and k in case you were wondering) to represent the indices.

And according to additional info provided by gemini when asked about it:
> In early Fortran, variables starting with the letters I, J, K, L, M, and N were automatically treated as integers, which are the types of variables needed for indexing loops and summations.


So, I got to answer a question that probably everyone starting off programming wonders about, and go back to some of the origins of programming languages.
