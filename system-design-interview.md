# The Amazon System Design Interview

The Amazon system design interview is an open question about building a large service, discussed for 45 to 60 minutes. It is commonly reported for SDE II and above, with one or two design interviews in the loop. New graduates are more often given object-oriented design, which means designing the classes and methods of one small program.

## Format

| Part | Commonly reported time | What happens |
|---|---|---|
| Behavioral questions | 10 to 25 minutes | Questions on two or three Leadership Principles |
| Requirements | About 5 minutes | The candidate asks about features, scale, and limits |
| High-level design | 5 to 10 minutes | The main components and the flow of data between them |
| Detailed design | 10 to 15 minutes | One or two components in depth, such as the database or the cache |
| Scale and failure | About 5 minutes | Behavior under heavy load and when a component fails |

The Leadership Principles are the 16 statements that describe how Amazon expects employees to act. The design discussion is scored against them as well as against technical skill.

## Questions commonly reported

Many reported questions are built on Amazon products.

| Area | Example questions |
|---|---|
| Retail | An e-commerce platform, an order processing system, inventory across many warehouses |
| Delivery | Amazon Locker, an order tracking system |
| Media | A video streaming service like Prime Video |
| Cloud services | A storage service like S3, a key-value database like DynamoDB, a publish and subscribe messaging service |
| Data | A product recommendation service, a log analysis system |
| Devices | A management system for smart devices |
| General | A URL shortening service, a web crawler, a chat application |

## What the products imply

- **Peak traffic.** Retail traffic rises sharply during sales events, so order systems need queues and a plan for sudden load.
- **Correct inventory.** Two customers must not buy the last item, so expect questions on concurrent updates and consistency. Consistency means that every reader sees the same data.
- **High availability.** A shopping cart must accept writes when one server or one data center fails. Replication, which means keeping copies of data on several machines, is a frequent topic.
- **Cost.** Frugality is one of the principles. State what the design costs to run and where money can be saved.
- **Operations.** Amazon engineers run the services they build. Say how the service is monitored and what the on-call engineer sees when it fails.

## What a strong answer includes

1. Functional requirements, and non-functional requirements such as latency and availability, stated before any drawing.
2. Numbers: the request rate, the storage per year, and the size of one record.
3. A simple design first, with each added component justified by a requirement.
4. Trade-offs stated aloud, such as a relational database against a NoSQL database.
5. Failure cases. For Amazon Locker, say what happens when every locker is full and when nobody collects a package.
6. A link from a design decision to a customer effect, which is how Customer Obsession appears in a design answer.

Useful worked designs are [Design Amazon Shopping Cart](https://www.designgurus.io/course-play/system-design-interview-crash-course/doc/design-amazon-shopping-cart?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview) and [Design Amazon S3](https://www.designgurus.io/course-play/system-design-interview-crash-course/doc/design-amazon-s3?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview) in the System Design Interview Crash Course.

## Object-oriented design for SDE I and SDE II

Reported questions include a parking lot, an elevator system, and a locker service. The interviewer expects classes, interfaces, and the relationships between them, not servers and databases. [Design a Parking Lot](https://www.designgurus.io/course-play/grokking-the-object-oriented-design-interview/doc/design-a-parking-lot?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview) in Grokking the Object Oriented Design Interview shows the expected form of an answer.

## Go deeper

- [Grokking the System Design Interview](https://www.designgurus.io/course/grokking-the-system-design-interview?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview): the step-by-step method and the classic case studies.
- Lesson: [Designing Youtube or Netflix](https://www.designgurus.io/course-play/grokking-the-system-design-interview/doc/designing-youtube-or-netflix?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview), in Grokking the System Design Interview
- Lesson: [Design a Key-Value Store (like Dynamo and Cassandra)](https://www.designgurus.io/course-play/system-design-interview-crash-course/doc/design-a-keyvalue-store-like-dynamodb?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview), in System Design Interview Crash Course
- Lesson: [Design Amazon - Online Shopping System](https://www.designgurus.io/course-play/grokking-the-object-oriented-design-interview/doc/design-amazon-online-shopping-system?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview), in Grokking the Object Oriented Design Interview
- Free article: [Amazon system design interview: 6 sample questions and how to solve them](https://www.designgurus.io/blog/system-design-interview-amazon?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview)
- Free answer: [What interviewers look for during a system design round at Amazon](https://www.designgurus.io/answers/detail/what-interviewers-look-for-during-system-design-round-at-amazon?utm_source=github&utm_medium=repo&utm_campaign=amazon-interview-guide&utm_content=system-design-interview)
