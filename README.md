# PseudoScore Dataset

## Overview

PseudoScore is a dataset built from undergraduate course assessments, created to support research in educational algorithm grading and automated explanation generation. It pairs pseudocode-based programming questions with a large set of real student solutions, each manually graded and annotated with feedback.

## Dataset Composition

| Attribute | Detail |
|---|---|
| **Question Source** | Undergraduate course assessments |
| **Number of Questions** | 32 total (18 Level 1 + 14 Level 2) |
| **Number of Student Solutions** | 3,300 |
| **Answer Format** | Level 1: pseudocode translated from Python programs · Level 2: student-written pseudocode |
| **Educational Level** | Programming Fundamentals and Introduction to AI |
| **Algorithmic Difficulty** | Introductory–Intermediate |
| **Topics Covered** | Programming fundamentals, searching algorithms, sorting algorithms |

## Question Levels

- **Level 1 (18 questions):** Pseudocode translated from existing Python programs, providing a controlled format where the underlying logic is known and consistent.
- **Level 2 (14 questions):** Student-written pseudocode, capturing the natural variation in how students express algorithmic reasoning in their own words.

## Solution Quality & Annotations

- **Contains incorrect solutions:** Yes — the 3,300 student solutions span correct, partially correct, and incorrect responses, reflecting realistic classroom performance rather than only accepted/passing answers.
- **Human grades:** Yes, every solution has been manually graded.
- **Feedback:** Available alongside the grade for each solution.

## Evaluation Methodology

PseudoScore uses **manual rubric-based grading** rather than automated test-case execution. Because entries are pseudocode rather than runnable source code, rubric grading captures partial credit and reasoning quality in a way that pass/fail test execution cannot.

## Target Research Area

This dataset is intended to support work on:
- Automated / AI-assisted grading of student algorithmic reasoning
- Generation of feedback and explanations for student pseudocode

## Availability

This dataset is **publicly available**.

---

