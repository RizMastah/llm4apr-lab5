# Lab 5: Research Gap Statement and RQ Proposal

韩子杰 (Raihan Aditito Bagastama), Student ID L25020030

Topic: complexity-dependent failure of multi-agent frameworks in repository-level issue resolution (LLM4APR).

## Files

- `Lab5_Research_Gap_Statement.pdf`: the two-page research gap statement with three research questions
- `gap_statement.tex`: LaTeX source of the PDF

## Summary

The gap statement follows the four-paragraph structure from the lab guide (background, gap, why existing approaches fail, proposed approach). It is based on the LLM4APR systematic literature review (Zhang et al., arXiv:2405.01466) and the MAGIS paper (Tao et al., arXiv:2403.17927).

Research questions:

1. How much does the resolution rate of multi-agent issue-resolution frameworks fall as the required change becomes more complex, and how much of the reported performance depends on being given the files to modify?
2. Does dependency-aware localization find the right files and lines more often than BM25 with summary filtering, and does this raise the resolution rate for multi-file issues?
3. How does the review method affect the resolution rate, the rate at which incorrect patches are approved, and the cost of each resolved issue?

The independent and dependent variables for each question are listed in Table 1 of the PDF.

## Building the PDF

The source uses a Chinese font for the author name, so it has to be compiled with XeLaTeX:

```
xelatex gap_statement.tex
```
