# Stakeholders, SDLC, Agile & DevOps Notes

---

## Stakeholders

**Stakeholders:** Stakeholders are people or organizations who are involved in or interested in the system.

### Examples:

- 🏫 **School System** → Students, Teachers, Parents, Principal, Management
- 🏦 **Banking System** → Customers, Employees, Managers, Management, Government/Regulators
- 💻 **IT Project** → Client, Developers, Testers, DevOps, Users, Management

### Who are the stakeholders in your project?

> "The stakeholders in our project include the client, users, developers, testers, DevOps team, and management."

---

# SDLC

**SDLC: Software Development Life Cycle**

**SDLC is a structured process used to design, develop, test, and deploy software.**

### Main goal:

**Deliver reliable software that meets customer requirements within time and budget.**

> **Reliable** means a system works correctly and consistently without frequent failures.

---

# Phases of SDLC

| Phase | Description |
|---|---|
| **Requirement Analysis** | Identify and document the requirements of the customer, client, and end users. |
| **Planning & System Design** | Plan the project and design the architecture, database, APIs, and UI. |
| **Implementation / Development** | Developers write the code. |
| **Testing** | Test the software and fix bugs. |
| **Deployment** | Release the software to users. |
| **Maintenance** | Monitor, support, and fix issues. |

---

# SDLC Models

- **Waterfall** → Linear, step-by-step development.
- **Agile** → Iterative and incremental development with frequent feedback and small releases.
- **Agile with DevOps** → Agile with DevOps focuses on continuous feedback and continuous improvement through automation.

---

# Waterfall vs Agile vs Agile with DevOps

Let's understand these concepts using a **School Management System example**.

---

# Waterfall Model — Traditional Year-End Examination

Imagine a school conducting examinations for students only once a year.

**Parents** → Paying fees  
**Students** → Studying  
**Teachers** → Teaching students

### Year-End Result

- **40% → Pass**
- **60% → Fail**

## Disadvantages

- The problem is identified only at the end of the year.
- By the time results are available, there is very little time to analyse the problems and improve student performance.

### Flow

**Teaching → Entire Year → Final Exam → Results → Analyse Problems**

---

# What is Waterfall Model?

**Waterfall is a linear, step-by-step software development model where each phase is completed before moving to the next phase.**

## Disadvantages

- Not flexible when requirements change.
- Problems are discovered late, usually during testing.
- Changes can be costly after a phase is completed.
- Feedback comes late from customers/users.
- Working software is delivered late.

---

# Agile — Continuous Assessment & Examination Model

Instead of conducting only one exam at the end of the year, the school conducts multiple exams throughout the year.

### Examination Flow

**Unit-Test-I → Unit-Test-II → Unit-Test-III → Unit-Test-IV → Unit-Test-V → Quarterly → Half-Yearly → Pre-Final → Final Exam**

This allows teachers to check student performance regularly and get feedback earlier.

---

# Unit-Test-I

## Preparation

**Teacher:** Completes the required syllabus before conducting the exam.

**Student:** Starts preparing before the exam, for example, one week in advance.

### Result

- **60% → Pass**
- **40% → Fail**

---

# Analyse the Results

The school now has time to:

- Analyse failing students' problems
- Understand why students are failing
- Conduct parent-student meetings
- Identify areas where students need improvement

### Improvement Flow

**Unit-Test-I → Results → Analyse Problems → Take Corrective Action**

---

# Unit-Test-II

After analysing the students' problems and taking corrective actions:

**Passing Percentage → 65%**

The result improves:

**60% → 65%**

This shows the benefit of **frequent feedback and improvement.**

### Continuous Improvement Flow

**Test → Analyse → Improve → Test Again → Better Result**

---

# Final Exam

After continuous assessments and improvements:

- **80% → Pass**
- **20% → Fail**

The school continuously improves student performance through **regular testing, feedback, analysis, and corrective action.**

---

# What is Agile?

**Agile is an iterative and incremental software development model where software is developed in small increments, tested frequently, and improved continuously based on feedback.**

### Agile Flow

**Develop → Test → Feedback → Improve → Repeat**

---

# Sprint

**A Sprint is a fixed time period in which the team develops and delivers a small part of the software.**

## Why do we use Sprints in Agile?

Sprints help divide a large application into small, manageable parts and develop them step by step within a fixed time period.

---

# Agile Advantages over Waterfall

- **Flexible to requirement changes**
- **Early defect detection**
- **Lower cost of changes**
- **Frequent customer feedback**
- **Early delivery of working software**

---

# Agile with DevOps — Targeted Improvement

After the Agile process, the school focuses specifically on the **20% of students who are still struggling.**

---

# Slip Tests

Conduct small tests regularly to identify specific problem areas.

- Multiple-choice questions
- Short-answer questions
- Around 10 questions per test
- Multiple tests throughout the process

### Flow

**Daily Slip Test → Analyse Results → Identify Problems → Corrective Action → Improve Performance**

Teachers analyse the results regularly and share the progress with parents.

Additional study hours and better learning methods can be introduced to help students improve.

### Continuous Improvement

**Test → Analyse → Fix Problems → Test Again → Monitor Progress**

---

# Example Final Result

**80% Pass → 20% Need Improvement → Targeted Practice → Improved Result**

**99% → Example Improved Result**

---

# What is Agile with DevOps?

**Agile with DevOps means developing software in small increments and continuously building, testing, deploying, monitoring, and improving it using automation.**

---

# Easy Difference

> **Agile = How we develop software**

> **DevOps = How we build, test, release, deploy, monitor, and continuously deliver software**

---

# What is DevOps?

**DevOps is a combination of Development and Operations that improves collaboration and automates the software delivery process.**

## Simple Explanation

**DevOps is the process of building, testing, scanning, deploying, monitoring, and improving software continuously.**

### EX:

For example, if developers write even a single line of code, it should be built, scanned, tested, deployed immediately, and feedback should be given to developers. This is called **DevOps.**

---

# DevOps Flow

**DevOps → Develop → Build → Test → Deploy → Monitor → Feedback**

### Development

**Code → Build → Test → Release**

### Operations

**Deploy → Monitor → Maintain**

---

# What is DevSecOps?

**DevSecOps extends DevOps by integrating security into the software delivery process.**

### Goal:

**Identify and fix security issues early in the development and delivery process.**

### DevSecOps Flow

**Develop → Build → Security Scan → Test → Deploy → Monitor → Feedback**

---

# Tools Used to Achieve DevOps

Different tools can be used to automate different stages:

| Tool | Purpose |
|---|---|
| **Git** | SCM (Source Code Management) |
| **Jenkins** | CI/CD |
| **Scanning Tools** | Security / Quality Checks |
| **Kubernetes** | Container Orchestration |
| **Cloud** | Scalability |

---

# Quick Revision

### Stakeholders

**People or organizations who are involved in or interested in the system.**

### SDLC

**Structured process used to design, develop, test, and deploy software.**

### Waterfall

**Linear, step-by-step development.**

### Agile

**Iterative and incremental development with frequent feedback and small releases.**

### DevOps

**Build → Test → Deploy → Monitor → Feedback**

### DevSecOps

**DevOps + Security**

### Sprint

**A fixed time period in which the team develops and delivers a small part of the software.**

### Agile with DevOps

**Develop → Build → Test → Deploy → Monitor → Improve continuously using automation.**
