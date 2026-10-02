# CMPS 2200 Assignment 3
## Answers

**Name:**_________________________


Place all written answers from `assignment-03.md` here for easier grading.


**1: Searching Unsorted Lists**

- **1b.** Work and span of `isearch` implementation
Work: O(n)
Span: O(n)

- **1d.** Work and span of `rsearch` implementation
Work: O(n)
Span: O(log n) (parallelization)

- **1e.** Work and span of `rsearch` using `ureduce`
Work: O(n)
Span: O(log n) (parallelization)

**3: Parenthesis Matching**

- **3b.** Recurrences and Big-Oh solutions for `parens_match_iterative`
Work: W(n) = W(n-1) + O(1) = O(n)
Span: S(n) = S(n-1) + O(1) = O(n)


- **3d.** Work and Span for `parens_match_scan`
Work: O(n)
Span: O(log n)

map's work is O(n) and it's span is O(1)
scan's work is O(n) and it's span is O(log n)
reduce's work is O(n) and it's span is O(log n)

adding them up and accounting for the more contributing components provided me my final answer


- **3f.** Recurrences and Big-Oh solutions for `parens_match_dc_helper`
Work: W(n) = 2W(n/2) + O(1) = O(n)
Span: S(n) = S(n/2) + O(1) = O(log n)