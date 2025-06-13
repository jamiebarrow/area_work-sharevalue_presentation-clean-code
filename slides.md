---
title: "S.O.L.I.D. Principles"
sub_title: (Clean Code)
author: James Barrow
date: 🎃 13 June 2025 👻
location: ShareValue, Gouda
theme:
    name: dark
---

# SOLID Principles

| when | who              | principle             |
| ---- | ---------------- | --------------------- |
| 1987 | Barbara Liskov   | Liskov Substitution   |
| 1988 | Bertrand Meyer   | Open Closed           |
| 1996 | Robert C. Martin | Dependency Inversion  |
| 2000 | Robert C. Martin | Single Responsibility |
| 2000 | Robert C. Martin | Interface Segregation |
| 2004 | Michael Feathers | SOLID acronym         |

- Single Resonsibility Principle (SRP)
    - a single reason to change
<!-- new_line -->
- Open Closed Principle (OCP)
    - open for extension
    - closed for modification
<!-- new_line -->
- Liskov Substitution Principle (LSP)
    - let Ø(x) be a property provable about objects x of type T
    - then Ø(y) should also be true for objects y of type S
    - where S is a subtype of T
    - sub-types should be substitutable for their base types
<!-- new_line -->
- Interface Segregation Principle (ISP)
    - clients should not be forced to depend on what they do not use
    - consumers should not be forced to depend on what they do not use
<!-- new_line -->
- Dependency Inversion Principle (DIP)
    - depend on abstractions and interfaces, not on concretions and implementation details

<!-- end_slide -->

# Other

- Object Orientation
  - cohesion
  - coupling
  - information hiding
  - inheritance
  - composition
  - polymorphism
- Design By Contract
  - pre-conditions, post-conditions, invariants
- Idempotency: repeatable without change in observable state, side-effect free
- Queries: do not mutate observable state
- Commands: mutate observable state, can invoke queries
- Command Query Responsibility Segregation (CQRS)
- Command Query Separation (CQS)
- Postels Law / Robustness Principle
  - be conservative in what you do, be liberal in what you accept from others
  - TCP: Be conservative in what you send and liberal in what you accept
  - criticism that is leads to less robustness and security
- Fail Fast
  - be as detailed as can be allowed
- Tony Hoare's billion dollar mistake - null
- Tester/Doer
- TryRead
- Maybe
- Clean Architecture
  - Onion Architecture
  - Hexagonal Architecture
  - Ports and Adapters
- Domain Driven Design

<!-- end_slide -->

# References

- [Clean Coder](http://www.cleancoder.com/)
<!-- new_line -->
- [SOLID Principles for C# Developers](https://app.pluralsight.com/library/courses/csharp-solid-principles); Steve Smith (@ardalis); Pluralsight; Mar 2024
- [SOLID course sample code](https://github.com/ardalis/SolidSample)
<!-- new_line -->
- [Encapsulation and SOLID](https://app.pluralsight.com/library/courses/encapsulation-solid); Mark Seeman; Pluralsight; Aug 2014
- https://github.com/louthy/language-ext
- https://github.com/vkhorikov/CSharpFunctionalExtensions
<!-- new_line -->
- Cheat sheets
  - [Clean Code](https://en.bbv.ch/insights/publications/practical-cheat-sheet-on-clean-code-principles-and-implementation/)
    - [PDF](https://en.bbv.ch/wp-content/uploads/2020/02/Clean-Code-Prinzipien-Umsetzung.pdf)
  - [Clean Architecture](https://en.bbv.ch/insights/publications/practical-cheat-sheet-on-clean-architecture-principles-and-methods/)
    - [PDF](https://en.bbv.ch/wp-content/uploads/2020/02/Software-Architektur-Clean-Architecture-Cheat-Sheet.pdf)
  - [Clean TDD/ATDD](https://en.bbv.ch/insights/publications/practical-cheat-sheet-on-clean-tdd-and-atdd/)
    - [PDF](https://en.bbv.ch/wp-content/uploads/2020/02/Software-Testing-Clean-TDD-ATDD.pdf)
- [Design Patterns and Refactoring](https://sourcemaking.com/)
<!-- new_line -->
- [Boolean Is Not Your Friend](https://www.youtube.com/watch?v=SVew0lXNCqQ); Zoran Horvat; YouTube; Aug 2024
- [Eliminate Data Clumps: Step-by-Step Refactoring Guide](https://www.youtube.com/watch?v=k1fIRmTsQMU); Zoran Horvat; YouTube; Nov 2024
