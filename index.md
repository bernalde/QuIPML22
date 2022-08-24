---
title: "47-779/785, 18-819F - Quantum Integer Programming and Quantum Machine Learning - CMU Fall 2022"
layout: home
menuItem: "Basic information"
menuPosition: 1
---
<h1>{{ site.courseName }}</h1>

<img src="{{ site.baseurl }}/style/Header2b.jpg" width="100%">

Mondays and Wednesdays 4:40 p.m. - 6:30 p.m. EST. Room 2701 Tepper Quad.

You can review our previous courses on Quantum Integer Programming Fall 2020 [here](https://bernalde.github.io/QuIP/) and Quantum Integer Programming and Machine Learning Fall 2021 [here](https://bernalde.github.io/QuIPML/).

Lecturers: Prof. Sridhar Tayur (4216 Tepper Quad), Prof. Elias Towe (Roberts Engineering Hall 147).

Guest lecturers: Dr. Davide Venturelli, and Dr. David Bernal.

Teaching Assistants:  Jiaqi Guo and Pruthviraj Gampalwar. 

## News

Our collaboration with USRA and Amazon Web Services was recently featured in [this news release](https://www.cmu.edu/tepper/news/stories/2020/october/quantum-computing-course.html) from the Tepper School of Business at Carnegie Mellon Univerity.
The article also mentions the motivation for creating this course, so enjoy the read!


## Objectives

This course is primarily designed for graduate students (and advanced undergraduates) across CMU campuses interested in integer programming (with non-linear objective functions) and the potential of near-term quantum computing for solving combinatorial optimization problems.
By the end of the semester, someone enrolled in this course should be able to:
- Identify the current status of quantum computing and its potential uses for integer programming
- Access and use quantum computing resources (such as DWave Quantum Annealers)
- Set up a given integer program to be solved with quantum computing 
- Work in groups collaboratively on a state-of-the-art project regarding applications of quantum computing and integer programming

This course is not going to focus on the following topics:
- Computational complexity theory
- Quantum Information Theory
- Analysis of speedup using differential geometry, algebraic topology.

Students with backgrounds in operations research, industrial engineering, chemical engineering, electrical engineering, physics, computer science, or applied mathematics are strongly encouraged to consider taking this course.
[Enroll here.](https://s3.andrew.cmu.edu/sio)

## Prerequisite classes and capabilities

Although this class has no explicit prerequisites, we consider a list of recommended topics and skills that the student should feel comfortable with.
An undergraduate-level understanding of probability, calculus, statistics, graph theory, algorithms, and linear algebra is assumed.
Knowledge of linear and integer programming will be helpful in this course.
Programming skills are strongly recommended.
Basic concepts in physics are recommended, but lack of prior knowledge is not an issue as pertinent ones will be covered in the lectures.
No particular knowledge in quantum mechanics or algebraic geometry is required.

<!-- 
## Basic course structure

**Weeks 1-2:** Review of Linear algebra for Quantum Mechanics and Quantum Machine Learning.

**Week 2:** Mathematical Programming basics (classical methods).

**Week 3-4:** Basic Classical Machine Learning, Ising, QUBO.

**Week 4:** Ising, QUBO (GAMA).

**Week 4:** Graver Augmented Multiseed algorithm (GAMA).

**Week 5:** Axioms of Quantum Mechanics, Quantum Measurements, Qubit Gate model of quantum computing. 

**Week 6:** Quantum methods for solving Ising/QUBO: Adiabatic Quantum Computing (AQC), Quantum Alternating (Approximate) Optimization Ansatz (Algorithm) (QAOA). Midterm Project Presentations.

**Week 7:** Break

**Week 8:** Midterm Project Presentations. 

**Week 9:** Specialized hardware for solving Ising/QUBO. Quantum Algorithms for future quantum processors; HHL; Grover's search algorithm. 

**Week 10:** Guest speakers. Term Project
Noise in quantum computing and quantum error correction.

**WeekS 11:** Recent advances and other topics. 

**WeekS 11-12-13:** Term Project

**Week 14:** Term Project Presentations. 
-->
## Grading
Weekly homework and quizzes (30%), Final Project (70%).
- There will be 4 quizzes to evaluate the concepts covered in class—each worth 10 points. Only the best 3 quizzes will count toward the 30%.
- The final project will be submitted in groups. It will require the implementation and solution of an integer programming instance using quantum computing resources. This final project deliverable will be a report and a presentation.

## Highlights
The specific skills that students will gain that will make them "quantum ready" for industry or further academic research in this course are:

A. Classical

1. Given a practical problem (from supply chain, physics, to anything else), formulate it as a non-linear integer program. We will provide a few practical problems, but we encourage you to suggest one that you are already working on or are interested in.
2. Solve such formulations via classical solvers.

B. Quantum

3. Reformulate the problem to be “quantum ready” by making it in the form of a QUBO. 
4. Solve the QUBO “brute force” through D-Wave or IBM (via QAOA).

C. Hybrid Quantum-Classical

5. Reformulate the problem again in the form suitable for GAMA.
6. Solve GAMA compatible formulation via D-Wave and/or via QAOA.

USRA Collaboration
- Access to D-Wave systems might be available via written proposals to the University Space Research Association (USRA). See [RIACS website](https://riacs.usra.edu/quantum/rfp) for terms and conditions. The course will discuss proposal preparation.
- Students of this course are encouraged to apply to the [Feynman Academy Internship program](https://riacs.usra.edu/quantum/qacademy) that sponsors research projects at NASA Ames Research Center.

Amazon Braket Collaboration
- Access to [D-Wave](https://aws.amazon.com/braket/hardware-providers/dwave/), [IonQ](https://aws.amazon.com/braket/hardware-providers/ionq/) and [Rigetti](https://aws.amazon.com/braket/hardware-providers/rigetti/ ) is also made possible through [Amazon Braket](https://aws.amazon.com/braket/).  

<!-- 
# Full Syllabus
The complete syllabus can be downloaded <a href="syllabus/QuIPML_Syllabus_2021.pdf" download>here.</a>
-->