# Amazon Interview Guide

> A free guide to the Amazon software engineer interview from [DesignGurus.io](https://www.designgurus.io/course/grokking-amazon-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme), created by Arslan Ahmad.

[![GitHub stars](https://img.shields.io/github/stars/design-gurus/amazon-interview-guide?style=social)](https://github.com/design-gurus/amazon-interview-guide/stargazers)
[![Last commit](https://img.shields.io/github/last-commit/design-gurus/amazon-interview-guide)](https://github.com/design-gurus/amazon-interview-guide/commits/main)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![PRs welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

Most companies give behavioral questions one interview. Amazon puts them in every interview. Each interviewer in the final stage, which Amazon calls the loop, asks a technical question and also questions about the Leadership Principles. The Leadership Principles are the 16 written statements that describe how Amazon expects its employees to decide and act. One interviewer, the Bar Raiser, comes from outside the hiring team and is commonly reported to hold a veto over the offer.

This repository is a short, free guide to that process for software development engineers (SDEs). It covers each stage, each kind of question, the levels from L4 to L8, and a four-week plan. Each page takes about three minutes to read. The guide is independent. It is not affiliated with Amazon and is not endorsed by Amazon, and the process details are commonly reported by candidates, not official.

## The loop at a glance

| Stage | Commonly reported length | What it measures | Guide page |
|---|---|---|---|
| Online assessment | About 90 minutes to 2 hours | Two coding questions and work style sections based on the principles | [Interview process](interview-process.md) |
| Phone screen | 30 to 60 minutes | One coding question and a few principle questions | [Interview process](interview-process.md) |
| Loop: coding interviews | 45 to 60 minutes each, usually 2 | Working code, cost analysis, and communication | [Coding interview](coding-interview.md) |
| Loop: system design | 45 to 60 minutes, 1 or 2 for SDE II and above | Requirements, scale, failure handling, and cost | [System design interview](system-design-interview.md) |
| Loop: Bar Raiser | 45 to 60 minutes | The hiring standard, mostly through principle questions | [Behavioral interview](behavioral-interview.md) |
| Debrief | A meeting without the candidate | The hire or no hire decision and the level | [Levels](levels.md) |

## Start here

| Your situation | Read this first |
|---|---|
| You received an online assessment invitation | [Interview process](interview-process.md) |
| You have a loop scheduled and need the outline | [Common mistakes](common-mistakes.md) |
| You have four weeks to prepare | [Four-week plan](four-week-plan.md) |
| You want practice questions | [Question bank](question-bank.md) |

## All pages

| Page | What it covers |
|---|---|
| [Interview process](interview-process.md) | Every stage from application to offer, and what each stage decides |
| [Coding interview](coding-interview.md) | The format, the four graded items, and the patterns commonly reported |
| [System design interview](system-design-interview.md) | Question types, Amazon product themes, and what a strong answer includes |
| [Behavioral interview](behavioral-interview.md) | How the Leadership Principles are used in the loop, and how to prepare stories |
| [Levels](levels.md) | The SDE ladder from L4 to L8, and how the interview changes by level |
| [Question bank](question-bank.md) | 52 coding, system design, and behavioral questions, with links to lessons |
| [Roles](roles.md) | Intern, new graduate, experienced SDE, and AWS solutions architect |
| [Four-week plan](four-week-plan.md) | A weekly schedule with a finish condition for each week |
| [Common mistakes](common-mistakes.md) | Ten mistakes that are specific to the Amazon loop |

## FAQ

### How many rounds are in an Amazon interview?

Most software engineering candidates are commonly reported to pass through five to seven stages. The loop itself has four to six interviews of 45 to 60 minutes each. Some people count three rounds: the screen, the loop, and the Bar Raiser interview. See the [interview process](interview-process.md).

### How hard is the Amazon interview?

The coding questions are commonly reported as mostly medium in difficulty. The difficulty comes from the format. Each interview combines a technical question with 10 to 25 minutes of behavioral questions, so there is less time to code. Weak answers on the Leadership Principles are the most commonly reported reason for rejection. See [common mistakes](common-mistakes.md).

### How long does the Amazon hiring process take?

Three to six weeks is the commonly cited range, and senior roles take longer. Candidates are told to expect a result about two business days after the phone screen and about five business days after the loop. Longer waits are reported when a team is comparing several candidates.

### What coding questions does Amazon ask?

Amazon asks standard data structure and algorithm questions on arrays, strings, hash maps, heaps, trees, and graphs. Many are written as stories about packages, warehouses, or delivery routes. The [question bank](question-bank.md) lists 26 coding questions with a lesson link for each.

### Does Amazon ask system design?

Yes, for SDE II and above. New graduates are more often given object-oriented design, which means designing the classes and methods of one small program. The questions often come from Amazon products such as ordering, Locker, and video streaming. See the [system design interview](system-design-interview.md).

### What is the Amazon Bar Raiser?

A Bar Raiser is a trained interviewer from a different team who does not need the role filled. This person checks that a new hire is stronger than half of the people already in similar roles. Candidates are not told which interviewer is the Bar Raiser. See the [behavioral interview](behavioral-interview.md).

## Go deeper

This repository gives the outline. The courses teach each round in full with worked solutions.

- [Grokking Amazon Coding Interview](https://www.designgurus.io/course/grokking-amazon-coding-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme): 14 problems that Amazon is reported to ask, each with a worked solution.
- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme): the method and the case studies for the design interviews.
- [Grokking Modern Behavioral Interview](https://www.designgurus.io/course/grokking-behavioral-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme): the STAR method, a story bank, and a chapter on the Amazon framework.
- Lesson: [Amazon Leadership Principles](https://www.designgurus.io/course-play/grokking-behavioral-interview/doc/amazon-leadership-principles?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme), in Grokking Modern Behavioral Interview
- Free article: [Amazon interview guide: process, questions, and how to prepare](https://www.designgurus.io/blog/amazon-interview-guide?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme)
- Free article: [Amazon online assessment guide](https://www.designgurus.io/blog/amazon-online-assessment-guide?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=readme)

Related free guides: [Amazon Leadership Principles](https://github.com/design-gurus/amazon-leadership-principles), [Software Engineer Levels](https://github.com/design-gurus/software-engineer-levels/blob/main/companies/amazon.md), [Grokking System Design](https://github.com/design-gurus/grokking-system-design), and [Grokking the Coding Interview](https://github.com/design-gurus/grokking-coding-interview).

## Contributing

Corrections, new questions, and reports of how an Amazon loop was run are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

## License

The content is licensed under [CC BY 4.0](LICENSE). See [NOTICE.md](NOTICE.md) for what the license covers and how to attribute.
