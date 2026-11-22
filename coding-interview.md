# The Amazon Coding Interview

The Amazon coding interview is one problem in a shared editor, solved in working code while the interviewer watches. Two of the loop interviews are usually coding interviews, and each one also contains behavioral questions. The questions are commonly reported as mostly medium in difficulty, so the limited time is the main difficulty.

## Where coding appears

| Stage | Commonly reported format |
|---|---|
| Online assessment | Two questions in 70 to 90 minutes, graded automatically by test cases |
| Phone screen | One question in a shared editor |
| Loop | Usually two interviews of 45 to 60 minutes, one problem each |

Candidates report that behavioral questions take 10 to 15 minutes of each coding interview. Plan for about 30 to 40 minutes of coding, not a full hour.

## What is graded

Four items are commonly reported for the technical part of the interview.

| Item | What the interviewer looks for |
|---|---|
| Correctness | The code runs and handles the edge cases. An edge case is an input at the limit of what the question allows. |
| Cost | The time and memory cost, stated in big-O notation without being asked |
| Code quality | Clear names, small functions, and no unused code |
| Communication | Clarifying questions first, then the approach explained before any typing |

Amazon asks for code that compiles in a real programming language. Pseudo code is not accepted in the assessment and is a weak answer in the loop. The interview is also scored against the Leadership Principles, the 16 statements that describe how Amazon expects employees to act. A correct solution can therefore still receive a negative vote when the behavioral answers are weak.

## Patterns commonly reported

A pattern is a reusable way of solving many similar questions. The patterns below are reported for both the online assessment and the loop.

| Pattern | What it does | How the question may be written |
|---|---|---|
| Arrays and strings | One pass with a running result | The longest run of days with rising sales |
| Hash maps | Count or group items by a key | The number of packages in each weight class |
| Sliding window | Move a range across an array and update a total | The best k consecutive days of deliveries |
| Prefix sums | Store running totals so a range sum is one subtraction | The total load between two warehouse stops |
| Sorting and greedy | Sort, then take the best local choice at each step | The fewest trucks that carry all packages |
| Heaps for top k | Keep the k best items in a heap | The k most popular products |
| Graph search | Visit a grid or graph one neighbor at a time | The shortest route across a warehouse floor |
| Dynamic programming | Build an answer from answers to smaller inputs | The number of valid orderings of pickups and deliveries |

Many questions are written as stories about Amazon operations. The story does not change the algorithm. Write down the input, the output, and the size limits, and then name the data structure.

## How to practice

1. Practice by pattern, not by problem count. Solve three to five problems for each pattern in the table.
2. Time every problem at 30 minutes, because the interview leaves no more than that.
3. Say the approach aloud before writing code, and state the cost when the code is finished.
4. Test the code with a small input before the interviewer asks. Try an empty input, one item, and all items equal.
5. For the assessment, read both questions first and begin with the easier one. Keep the last 10 minutes for testing.

The [question bank](question-bank.md) lists 26 coding questions with a lesson for each. Good first lessons are [Longest Common Prefix](https://www.designgurus.io/course-play/grokking-amazon-coding-interview/doc/longest-common-prefix-easy?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview) for strings and [Number of Islands](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/number-of-islands-easy?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview) for graph search.

## Go deeper

- [Grokking Amazon Coding Interview](https://www.designgurus.io/course/grokking-amazon-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview): 14 problems that Amazon is reported to ask, from easy to hard, each with a worked solution.
- [Grokking the Coding Interview](https://www.designgurus.io/course/grokking-the-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview): the full set of coding patterns, with problems grouped by pattern.
- Lesson: [Count the Number of Good Subarrays](https://www.designgurus.io/course-play/grokking-amazon-coding-interview/doc/count-the-number-of-good-subarrays-medium?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview), in Grokking Amazon Coding Interview
- Lesson: [Introduction to Top 'K' Elements Pattern](https://www.designgurus.io/course-play/grokking-the-coding-interview/doc/introduction-to-top-k-elements-pattern?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview), in Grokking the Coding Interview
- Free article: [The top 20 coding questions to pass the Amazon interview](https://www.designgurus.io/blog/top-20-amazon-coding-interview-questions?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=coding-interview)
- Free guide: [Grokking the Coding Interview](https://github.com/design-gurus/grokking-coding-interview), the coding patterns on GitHub
