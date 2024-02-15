---
author: "Danushka"
title: "A Checklist when writing papers"
date: "2024-02-01"
description: "A Checklist when writing papers"
tags: []
hideMeta: false
searchHidden: false
ShowBreadCrumbs: true
draft: false
---

Here is a list of common errors encountered when revising paper drafts. Please check these when you write papers (before you send them for me to check).

- Write the abstract first. Think of the keywords that you want to include in the title. Then think of a few candidate titles for your paper. Discuss these with your co-authors.

- Introduction: List up the things that you want to mention in the intro (same goes for all sections). 
    *   What is the problem?
    *   Why is it important to solve it?
    *   What are the challenges?
    *   How does the proposed method overcome those? (briefly explain the proposed method and give pointers to the corresponding sections in the paper)
    *   What experiments did you do to evaluate the proposed method? How were the results?

- It is a good practice to end the introduction with a summary of the contributions. The Area Chair (AC) will use that to write a meta-review, if they want to accept your paper. 

- Run a spell-checker

- Use a single ~ (tilde) before \cite command such that you have a space between the opening bracket of a citation reference and the remainder of the sentence.

- Define all acronyms when you use them the first time. Second time onwards use the acronym you already defined. [Acronym package](https://ctan.org/pkg/acronym) is a handy tool for this.

- Check that the font size in your figures are not too small to read. It is a good practice to use the same (or at least similar) font types in your figures as the rest of the paper.

- Provide detailed and informative captions to your figures and tables such that the reader could understand what is shown in the figure/table even without having to read the body text of the paper. (bad example: Figure 1: Overview of the method)

- Use table, figure labels that are informative. For example, `tbl1` is a poor choice for referring to a Table (which might not be the first table in the paper after several edits). `tbl:similarity-results` is a better naming, which is more informative.

- Common word usage mistakes (`like` --> `such as`, `utilise` --> `use`)
  
- If you are performing any statistical significance tests to check whether your proposed method is `significantly` outperforms a previously proposed method (or a baseline), remember to mention the level of significane (i.e. alpha < 0.01 or 0.05 etc.) (or alternatively the confidence levels corresponding to 99% or 95%) as well as the name of the test you performed. If you do not do any statistical significance tests then do not mention the term `significant` in the paper.

- If you can spend an hour to revise a section, include a figure, a table etc. that would save 5mins of the reviewer/readers time spent on your paper, then do it!



