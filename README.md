# interview-prep

## Getting started

TODO:

- One Topic at a time
- Bunch of leetcode problems: Easy then Medium
- Once all topics done, then just do random shuffled problems

## Resume

- Name, Phone, Email
- Education
- Employment
  - Break down projects and responsibilities into bullets
  - Bullets should cover:
    1. What you did
    2. How you did it
    3. The outcome of it
    - Example: Developed customer facing serverless API with quotas, reducing hosting costs by 90% and downtime by 98%
- Technologies / Skills
- Projects
- Awards / Achievements (if any)

## Behavioral

TODO

## Technical

### Habits

Pneumonic Device: **TATE ABS**

- Write _**Tests**_ - simple, corner
- Talk _**Aloud**_
- Write High Level _**TODOs**_ - for design problems only
- _**Expect**_ Hurdles
- Create _**Abstractions**_ - for readability
- _**Brute Force**_ First
- _**Solve**_ By Hand First

### Topics

Ordered based on importance and growing complexity

#### Data Structures

##### Standard

- Arrays
- Strings
- Singly Linked Lists, Doubly Linked Lists
- Hash Tables
- Stacks
- Heaps & Priority Queues
- Binary Trees, Binary Search Trees
- Graphs
- Tries
- Balancing Trees: AVL, Red-Black

##### Custom

- Caches: LRU, LFU
- Min Stack
- Peeking Iterator

#### Algorithms

- Hash
- Recursion
- Sort:
  - Merge
  - Quick
  - Heap
- Search:
  - Binary
  - Breadth-First
  - Depth-First
- Greedy
- Backtracking
- Dynamic Programming
- Topological Sort
- Dijkstra's (familiarity only)

#### Tips and Tricks

##### Language

Know the programming language you choose very well!
If the role requires a particular skill, use that technology. For example, JavaScript or TypeScript for React roles. In every other case, I suggest Python:

- It has minimal syntax, so it is fast to write and easy to read
- Has negative indexing
- Has clear complexity requirements and a standard data structures and algorithms library (unlike its common counterpart JavaScript)
  - For example, if you need to use a priority queue in your solution, you can just use `heapq` in Python. Where as in JavaScript you might be forced to implement your own on the spot.

##### Data Structures & Algorithms

- Know by heart both iteratively and recursively:
  - BFS
  - DFS
  - Binary Search
  - Reversing Linked List
- BFS: Queue
- DFS: Stack / Call-Stack
- "Find Path": Backtracking
- "Find Kth Largest/Smallest": Heap
- Graphs Problems: Typically O(N + E) runtime, where N is nodes and E is edges
- Dynamic Programming:
  - Usually asking for number of _**ways**_ to get somewhere, not number of _**steps**_ (Ex: Climbing Stairs Problem)
  - Breakdown into sub-problems
  - Bottom-Up approach is usually easier than Top-Down

#### Design Basics - High Level

These are only suggestions. Don't feel like you need to know all of these, or any of them in depth.
Typically you're in control of the design discussion and should lead it towards your strengths.
The sub-bullets are non-comprehensive examples.

- Back of Envelope Calculations:
  - 1 char (UTF-8): 1 byte
  - Giga: 1 Billion: 10 ^ 9
  - CPU: ~4GHz
- Programming Design Patterns:
  - Composition
  - Event Queues / Triggers
  - Object-Oriented:
    - Encapsulation
    - Abstraction
    - Inheritance
    - Polymorphism
- Networking:
  - DNS
  - TCP
  - UDP
  - HTTP
  - MQTT
  - RPC
- Messaging:
  - SNS
  - SQS
  - Pub/Sub
  - Kafka
- Caching:
  - CDN
  - Memcached
  - Redis
- Load Balancing:
  - Nginx
  - Internal
  - External
- Security:
  - Onion Routing
  - Reverse Proxy
  - Kubernetes Ingress
- Parallelism:
  - Multi-Deployment
  - Multi-Threaded
  - Concurrent
- Distributed Systems:
  - Gossip Protocol: Paxos
  - BitTorrent
- Storage:
  - Cache
  - Databases: SQL, NoSQL, Sharding
  - Blob
- SQL:
  - Data Types
  - Actions
  - Types of JOIN
- DevOps
  - Git
  - CI/CD
  - Containerization: Docker, Kubernetes
  - Infrastructure as Code: Terraform
  - Monitoring: Datadog
