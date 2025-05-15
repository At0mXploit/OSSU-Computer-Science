# OSSU
Computer Science Notes, Projects and Log.
<div align="center" style="text-align: center">

<h3>Open Source Society University</h3>
<p>
  Path to a free self-taught education in Computer Science!
</p>
<p>
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg"
  ></a>
  <a href="https://github.com/ossu/computer-science">
    <img alt="Open Source Society University - Computer Science" src="https://img.shields.io/badge/OSSU-computer--science-blue.svg"
  ></a>
</p>
</div>

# Contents

- [Curriculum](#curriculum)


# Curriculum

- [Prerequisites](#prerequisites)
- [Intro CS](#intro-cs)
- [Core CS](#core-cs)
  - [Core programming](#core-programming)
  - [Core math](#core-math)
  - [CS Tools](#cs-tools)
  - [Core systems](#core-systems)
  - [Core theory](#core-theory)
  - [Core security](#core-security)
  - [Core applications](#core-applications)
  - [Core ethics](#core-ethics)
- [Advanced CS](#advanced-cs)
  - [Advanced programming](#advanced-programming)
  - [Advanced systems](#advanced-systems)
  - [Advanced theory](#advanced-theory)
  - [Advanced information security](#advanced-information-security)
  - [Advanced math](#advanced-math)
- [Final project](#final-project)

---

## Prerequisites

- [Core CS](#core-cs) assumes the student has already taken [high school math](https://ossu.dev/precollege-math), including algebra, geometry, and pre-calculus.
- [Advanced CS](#advanced-cs) assumes the student has already taken the entirety of Core CS
and is knowledgeable enough now to decide which electives to take.
- Note that [Advanced systems](#advanced-systems) assumes the student has taken a basic physics course (e.g. AP Physics in high school).

## Intro CS

This course will introduce you to the world of computer science and programming. This course gives you a flavor of the material to come. If you finish the course wanting more, Computer Science is likely for you!

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`and more`

Courses | Duration | Effort | Status | Notes / Projects 
:-- | :--: | :--: | :--: | :--: |
[Introduction to Computer Science and Programming using Python](coursepages/intro-cs/README.md) | 14 weeks | 6-10 hours/week | Not Done | 

## Core CS

All coursework under Core CS is **required**, unless otherwise indicated.

### Core programming
**Topics covered**:
`functional programming`
`design for testing`
`program requirements`
`common design patterns`
`unit testing`
`object-oriented design`
`static typing`
`dynamic typing`
`ML-family languages (via Standard ML)`
`Lisp-family languages (via Racket)`
`Ruby`
`and more`

Courses | Duration | Effort | Status | Notes / Projects
:-- | :--: | :--: | :--: | :--:
[Systematic Program Design](coursepages/spd/README.md) | 13 weeks | 8-10 hours/week | none | chat: [part 1](https://discord.gg/RfqAmGJ) / [part 2](https://discord.gg/kczJzpm)
[Class-based Program Design](https://course.ccs.neu.edu/cs2510sp22/index.html) | 13 weeks | 5-10 hours/week | Systematic Program Design, High School Math | [chat](https://discord.com/channels/744385009028431943/891411727294562314)
[Programming Languages, Part A](https://www.coursera.org/learn/programming-languages) | 5 weeks | 4-8 hours/week | Systematic Program Design ([Hear instructor](https://www.coursera.org/lecture/programming-languages/recommended-background-k1yuh)) | [chat](https://discord.gg/8BkJtXN)
[Programming Languages, Part B](https://www.coursera.org/learn/programming-languages-part-b) | 3 weeks | 4-8 hours/week | Programming Languages, Part A | [chat](https://discord.gg/EeA7VR9)
[Programming Languages, Part C](https://www.coursera.org/learn/programming-languages-part-c) | 3 weeks | 4-8 hours/week | Programming Languages, Part B | [chat](https://discord.gg/8EZUVbA)
[Object-Oriented Design](https://course.ccs.neu.edu/cs3500f19/) | 13 weeks | 5-10 hours/week | Class Based Program Design | [chat](https://discord.com/channels/744385009028431943/891412022120579103)
[Software Architecture](https://www.coursera.org/learn/software-architecture) | 4 weeks | 2-5 hours/week | Object Oriented Design | [chat](https://discord.com/channels/744385009028431943/891412169638432788)

### Core math
Discrete math (Math for CS) is a prerequisite and closely related to the study of algorithms and data structures. Calculus both prepares students for discrete math and helps students develop mathematical maturity.

**Topics covered**:
`discrete mathematics`
`mathematical proofs`
`basic statistics`
`O-notation`
`discrete probability`
`and more`

Courses | Duration | Effort | Notes | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--: | :--:
[Calculus 1A: Differentiation](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.1x+2T2019/about) ([alternative](https://ocw.mit.edu/courses/mathematics/18-01sc-single-variable-calculus-fall-2010/index.htm)) | 13 weeks | 6-10 hours/week | The alternate covers this and the following 2 courses | [high school math](https://ossu.dev/precollege-math) | [chat](https://discord.gg/mPCt45F)
[Calculus 1B: Integration](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.2x+3T2019/about) | 13 weeks | 5-10 hours/week | - | Calculus 1A | [chat](https://discord.gg/sddAsZg)
[Calculus 1C: Coordinate Systems & Infinite Series](https://openlearninglibrary.mit.edu/courses/course-v1:MITx+18.01.3x+1T2020/about) | 6 weeks | 5-10 hours/week | - | Calculus 1B | [chat](https://discord.gg/FNEcNNq)
[Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about) ([alternative](https://ocw.mit.edu/courses/6-042j-mathematics-for-computer-science-fall-2010/)) | 13 weeks | 5 hours/week | [2015/2019 solutions](https://github.com/spamegg1/Math-for-CS-solutions) [2010 solutions](https://github.com/frevib/mit-cs-math-6042-fall-2010-problems) [2005 solutions](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2005/assignments/). | Calculus 1C | [chat](https://discord.gg/EuTzNbF)


### CS Tools
Understanding theory is important, but you will also be expected to create programs. There are a number of tools that are widely used to make that process easier. Learn them now to ease your future work writing programs.

**Topics covered**:
`terminals and shell scripting`
`vim`
`command line environments`
`version control`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[The Missing Semester of Your CS Education](https://missing.csail.mit.edu/) | 2 weeks | 12 hours/week | - | [chat](https://discord.gg/5FvKycS)

### Core systems

**Topics covered**:
`procedural programming`
`manual memory management`
`boolean algebra`
`gate logic`
`memory`
`computer architecture`
`assembly`
`machine language`
`virtual machines`
`high-level languages`
`compilers`
`operating systems`
`network protocols`
`and more`

Courses | Duration | Effort | Additional Text / Assignments| Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--: | :--:
[Build a Modern Computer from First Principles: From Nand to Tetris](https://www.coursera.org/learn/build-a-computer) ([alternative](https://www.nand2tetris.org/)) | 6 weeks | 7-13 hours/week | - | C-like programming language | [chat](https://discord.gg/vxB2DRV)
[Build a Modern Computer from First Principles: Nand to Tetris Part II ](https://www.coursera.org/learn/nand2tetris2) | 6 weeks | 12-18 hours/week | - | one of [these programming languages](https://user-images.githubusercontent.com/2046800/35426340-f6ce6358-026a-11e8-8bbb-4e95ac36b1d7.png), From Nand to Tetris Part I | [chat](https://discord.gg/AsUXcPu)
[Operating Systems: Three Easy Pieces](coursepages/ostep/README.md) | 10-12 weeks | 6-10 hours/week | - | Nand to Tetris Part II | [chat](https://discord.gg/wZNgpep)
[Computer Networking: a Top-Down Approach](http://gaia.cs.umass.edu/kurose_ross/online_lectures.htm)| 8 weeks | 4–12 hours/week | [Wireshark Labs](http://gaia.cs.umass.edu/kurose_ross/wireshark.php) | algebra, probability, basic CS | [chat](https://discord.gg/MJ9YXyV)

### Core theory

**Topics covered**:
`divide and conquer`
`sorting and searching`
`randomized algorithms`
`graph search`
`shortest paths`
`data structures`
`greedy algorithms`
`minimum spanning trees`
`dynamic programming`
`NP-completeness`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Divide and Conquer, Sorting and Searching, and Randomized Algorithms](https://www.coursera.org/learn/algorithms-divide-conquer) | 4 weeks | 4-8 hours/week | any programming language, Mathematics for Computer Science | [chat](https://discord.gg/mKRS7tY)
[Graph Search, Shortest Paths, and Data Structures](https://www.coursera.org/learn/algorithms-graphs-data-structures) | 4 weeks | 4-8 hours/week | Divide and Conquer, Sorting and Searching, and Randomized Algorithms | [chat](https://discord.gg/Qstqe4t)
[Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming](https://www.coursera.org/learn/algorithms-greedy) | 4 weeks | 4-8 hours/week | Graph Search, Shortest Paths, and Data Structures | [chat](https://discord.gg/dWVvjuz)
[Shortest Paths Revisited, NP-Complete Problems and What To Do About Them](https://www.coursera.org/learn/algorithms-npcomplete) | 4 weeks | 4-8 hours/week | Greedy Algorithms, Minimum Spanning Trees, and Dynamic Programming | [chat](https://discord.gg/dYuY78u)

### Core security
**Topics covered**
`Confidentiality, Integrity, Availability`
`Secure Design`
`Defensive Programming`
`Threats and Attacks`
`Network Security`
`Cryptography`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Cybersecurity Fundamentals](https://www.edx.org/course/cybersecurity-fundamentals) | 8 weeks | 10-12 hours/week | - | [chat](https://discord.gg/XdY3AwTFK4)
[Principles of Secure Coding](https://www.coursera.org/learn/secure-coding-principles)| 4 weeks | 4 hours/week | - | [chat](https://discord.gg/5gMdeSK)
[Identifying Security Vulnerabilities](https://www.coursera.org/learn/identifying-security-vulnerabilities) | 4 weeks | 4 hours/week | - | [chat](https://discord.gg/V78MjUS)

Choose **one** of the following:

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Identifying Security Vulnerabilities in C/C++Programming](https://www.coursera.org/learn/identifying-security-vulnerabilities-c-programming) | 4 weeks | 5 hours/week | - | [chat](https://discord.gg/Vbxce7A)
[Exploiting and Securing Vulnerabilities in Java Applications](https://www.coursera.org/learn/exploiting-securing-vulnerabilities-java-applications) | 4 weeks | 5 hours/week | - | [chat](https://discord.gg/QxC22rR)

### Core applications

**Topics covered**:
`Agile methodology`
`REST`
`software specifications`
`refactoring`
`relational databases`
`transaction processing`
`data modeling`
`neural networks`
`supervised learning`
`unsupervised learning`
`OpenGL`
`ray tracing`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Databases: Modeling and Theory](https://www.edx.org/course/modeling-and-theory)| 2 weeks | 10 hours/week | core programming | [chat](https://discord.gg/pMFqNf4)
[Databases: Relational Databases and SQL](https://www.edx.org/course/databases-5-sql)| 2 weeks | 10 hours/week | core programming | [chat](https://discord.gg/P8SPPyF)
[Databases: Semistructured Data](https://www.edx.org/course/semistructured-data)| 2 weeks | 10 hours/week | core programming | [chat](https://discord.gg/duCJ3GN)
[Machine Learning](https://www.coursera.org/specializations/machine-learning-introduction)| 11 weeks | 9 hours/week | Basic coding | [chat](https://discord.gg/NcXHDjy)
[Computer Graphics](https://www.edx.org/course/computer-graphics-2) ([alternative](https://cseweb.ucsd.edu/~viscomp/classes/cse167/wi22/schedule.html))| 6 weeks | 12 hours/week | C++ or Java, [Basic Linear Algebra](https://ossu.dev/precollege-math/coursepages/precalculus) | [chat](https://discord.gg/68WqMNV)
[Software Engineering: Introduction](https://www.edx.org/learn/software-engineering/university-of-british-columbia-software-engineering-introduction) ([alternative](https://github.com/ubccpsc/310/blob/main/resources/README.md)) | 6 weeks | 8-10 hours/week | Core Programming, and a [sizable project](FAQ.md#why-require-experience-with-a-sizable-project-before-the-Software-Engineering-courses) | [chat](https://discord.gg/5Qtcwtz)

### Core ethics

**Topics covered**:
`Social Context`
`Analytical Tools`
`Professional Ethics`
`Intellectual Property`
`Privacy and Civil Liberties`
`and more`

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Ethics, Technology and Engineering](https://www.coursera.org/learn/ethics-technology-engineering)| 9 weeks | 2 hours/week | none | [chat](https://discord.gg/6ttjPmzZbe)
[Introduction to  Intellectual Property](https://www.coursera.org/learn/introduction-intellectual-property)| 4 weeks | 2 hours/week | none | [chat](https://discord.gg/YbuERswpAK)
[Data Privacy Fundamentals](https://www.coursera.org/learn/northeastern-data-privacy)| 3 weeks | 3 hours/week | none | [chat](https://discord.gg/64J34ajNBd)

## Advanced CS

After completing **every required course** in Core CS, students should choose a subset of courses from Advanced CS based on interest.
Not every course from a subcategory needs to be taken.
But students should take *every* course that is relevant to the field they intend to go into.

### Advanced programming

**Topics covered**:
`debugging theory and practice`
`goal-oriented programming`
`parallel computing`
`object-oriented analysis and design`
`UML`
`large-scale software architecture and design`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Parallel Programming](https://www.coursera.org/learn/scala-parallel-programming)| 4 weeks | 6-8 hours/week | Scala programming
[Compilers](https://www.edx.org/course/compilers) | 9 weeks | 6-8 hours/week | none
[Introduction to Haskell](https://www.seas.upenn.edu/~cis194/fall16/)| 14 weeks | - | -
[Learn Prolog Now!](https://www.let.rug.nl/bos/lpn//lpnpage.php?pageid=online) ([alternative](https://github.com/ossu/computer-science/files/6085884/lpn.pdf))*| 12 weeks | - | -
[Software Debugging](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkxK63TiT88oEe-AIBhr96A)| 8 weeks | 6 hours/week | Python, object-oriented programming
[Software Testing](https://www.youtube.com/playlist?list=PLAwxTw4SYaPkWVHeC_8aSIbSxE_NXI76g) | 4 weeks | 6 hours/week | Python, programming experience

(*) book by Blackburn, Bos, Striegnitz (compiled from [source](https://github.com/LearnPrologNow/lpn), redistributed under [CC license](https://creativecommons.org/licenses/by-sa/4.0/))

### Advanced systems

**Topics covered**:
`digital signaling`
`combinational logic`
`CMOS technologies`
`sequential logic`
`finite state machines`
`processor instruction sets`
`caches`
`pipelining`
`virtualization`
`parallel processing`
`virtual memory`
`synchronization primitives`
`system call interface`
`and more`

Courses | Duration | Effort | Prerequisites | Notes
:-- | :--: | :--: | :--: | :--:
[Computation Structures 1: Digital Circuits](https://learning.edx.org/course/course-v1:MITx+6.004.1x_3+3T2016) [alternative 1](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/) [alternative 2](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2009/) | 10 weeks | 6 hours/week | [Nand2Tetris II](https://www.coursera.org/learn/nand2tetris2) | Alternate links contain all 3 courses.
[Computation Structures 2: Computer Architecture](https://learning.edx.org/course/course-v1:MITx+6.004.2x+3T2015) | 10 weeks | 6 hours/week | Computation Structures 1 | - 
[Computation Structures 3: Computer Organization](https://learning.edx.org/course/course-v1:MITx+6.004.3x_2+1T2017) | 10 weeks | 6 hours/week | Computation Structures 2 | -

### Advanced theory

**Topics covered**:
`formal languages`
`Turing machines`
`computability`
`event-driven concurrency`
`automata`
`distributed shared memory`
`consensus algorithms`
`state machine replication`
`computational geometry theory`
`propositional logic`
`relational logic`
`Herbrand logic`
`game trees`
`and more`

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Theory of Computation](https://ocw.mit.edu/courses/18-404j-theory-of-computation-fall-2020/) ([alternative](https://www.youtube.com/playlist?list=PLEE7DF8F5E0203A56)) | 13 weeks | 10 hours/week | [Mathematics for Computer Science](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+6.042J+2T2019/about), logic, algorithms
[Computational Geometry](https://www.edx.org/course/computational-geometry) | 16 weeks | 8 hours/week | algorithms, C++
[Game Theory](https://www.coursera.org/learn/game-theory-1) | 8 weeks | 3 hours/week | mathematical thinking, probability, calculus

### Advanced Information Security

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Web Security Fundamentals](https://www.edx.org/course/web-security-fundamentals) | 5 weeks | 4-6 hours/week | understanding basic web technologies
[Security Governance & Compliance](https://www.coursera.org/learn/security-governance-compliance) | 3 weeks | 3 hours/week | -
[Digital Forensics Concepts](https://www.coursera.org/learn/digital-forensics-concepts) | 3 weeks | 2-3 hours/week | Core Security
[Secure Software Development: Requirements, Design, and Reuse](https://www.edx.org/course/secure-software-development-requirements-design-and-reuse) | 7 weeks | 1-2 hours/week | Core Programming and Core Security
[Secure Software Development: Implementation](https://www.edx.org/course/secure-software-development-implementation) | 7 weeks | 1-2 hours/week | Secure Software Development: Requirements, Design, and Reuse
[Secure Software Development: Verification and More Specialized Topics](https://www.edx.org/course/secure-software-development-verification-and-more-specialized-topics) | 7 weeks | 1-2 hours/week | Secure Software Development: Implementation

### Advanced math

Courses | Duration | Effort | Prerequisites | Discussion
:-- | :--: | :--: | :--: | :--:
[Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | - | - | [high school math](https://ossu.dev/precollege-math) | [chat](https://discord.gg/m6wHbP6)
[Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | 14 weeks | 12 hours/week | corequisite: Essence of Linear Algebra | [chat](https://discord.gg/k7nSWJH)
[Introduction to Numerical Methods](https://ocw.mit.edu/courses/mathematics/18-335j-introduction-to-numerical-methods-spring-2019/index.htm)| 14 weeks | 12 hours/week | [Linear Algebra](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/) | [chat](https://discord.gg/FNEcNNq)
[Introduction to Formal Logic](https://forallx.openlogicproject.org/) | 10 weeks | 4-8 hours/week | [Set Theory](https://www.youtube.com/playlist?list=PL5KkMZvBpo5AH_5GpxMiryJT6Dkj32H6N) | [chat](https://discord.gg/MbM2Gg5)
[Probability](https://projects.iq.harvard.edu/stat110/home) | 15 weeks | 5-10 hours/week | [Differentiation and Integration](https://www.edx.org/course/calculus-1b-integration) | [chat](https://discord.gg/UVjs9BU)

## Final project

Part of learning is doing.
The assignments and exams for each course are to prepare you to use your knowledge to solve real-world problems.

After you've completed Core CS and the parts of Advanced CS relevant to you,
you should identify a problem that you can solve using the knowledge you've acquired.
You can create something entirely new, or you can improve some tool/program that you use and wish were better.

Students who would like more guidance in creating a project may choose to use a series of project oriented courses.
Here is a sample of options
(many more are available, at this point you should be capable of identifying a series that is interesting and relevant to you):

Courses | Duration | Effort | Prerequisites
:-- | :--: | :--: | :--:
[Fullstack Open](https://fullstackopen.com/en/) | 12 weeks | 15 hours/week | programming
[Modern Robotics (Specialization)](https://www.coursera.org/specializations/modernrobotics) | 26 weeks | 2-5 hours/week | freshman-level physics, linear algebra, calculus, [linear ordinary differential equations](https://www.khanacademy.org/math/differential-equations)
[Data Mining (Specialization)](https://www.coursera.org/specializations/data-mining) | 30 weeks | 2-5 hours/week | machine learning
[Big Data (Specialization)](https://www.coursera.org/specializations/big-data) | 30 weeks | 3-5 hours/week | none
[Internet of Things (Specialization)](https://www.coursera.org/specializations/internet-of-things) | 30 weeks | 1-5 hours/week | strong programming
[Cloud Computing (Specialization)](https://www.coursera.org/specializations/cloud-computing) | 30 weeks | 2-6 hours/week | C++ programming
[Data Science (Specialization)](https://www.coursera.org/specializations/jhu-data-science) | 43 weeks | 1-6 hours/week | none
[Functional Programming in Scala (Specialization)](https://www.coursera.org/specializations/scala) | 29 weeks | 4-5 hours/week | One year programming experience
[Game Design and Development with Unity 2020 (Specialization)](https://www.coursera.org/specializations/game-design-and-development) | 6 months | 5 hours/week | programming, interactive design

