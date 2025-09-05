---
layout: default
---

## Links
* [Jupyter Notebook](https://github.com/arongabrielbscs/CSST101-3A-AY2526/blob/main/exercises/Propositional%20Logic/CSST101-MP1.ipynb)
* [CSV File](https://github.com/arongabrielbscs/CSST101-3A-AY2526/blob/main/exercises/Propositional%20Logic/logic_results.csv)
* [Short Report](https://docs.google.com/document/d/13q3f6MidBzDT9akt328jdz-8ZVLampGzVmH4aFi_dWw/edit?usp=sharing)

# Assessment Task: Applying Propositional Logic in Real-World Scenarios through a Mini Expert System

This report examines the implementation of a university logic rule system that demonstrates the practical application of propositional logic through a mini expert system. The system showcases how logical reasoning can be automated to make decisions in academic administrative scenarios.

## Rules Implemented

The expert system implements several fundamental rules that govern university operations, each following specific logical structures:

### Rule 1: Attendance Rule
**Logic:** IF The student is late THEN They should bring an excuse letter  
**Format:** P → Q  
**Application:** This rule establishes a conditional requirement for late students, ensuring accountability through documentation.

### Rule 2: Grading Rule
**Logic:** IF The student's grade is >= 75 THEN The student passes  
**Format:** P → Q  
**Application:** Sets a clear threshold for academic success, automatically determining pass/fail status based on numerical performance.

### Rule 3: Login System Rule
**Logic:** IF The password is correct THEN Access is granted  
**Format:** P → Q  
**Application:** Implements basic security protocol, demonstrating how logical conditions control system permissions.

### Rule 4: Attendance Bonus System
**Logic:** IF The student has regular attendance THEN The bonus is eligible  
**Format:** P → Q  
**Application:** Incentivizes consistent attendance by linking it to bonus point eligibility.

All initial rules follow the simple conditional implication structure (P → Q), where a single condition leads to a single outcome.

## New Rule Added (Graduation Rule)

**Logic:** IF (The student passes AND The student completes the final project) THEN The student graduates  
**Format:** (P ∧ Q) → R

Where:
- P = Student Passes
- Q = Final Project Submitted  
- R = The Student Graduates

## Conclusion

The evolution from simple P → Q rules to the more complex (P ∧ Q) → R structure demonstrates how propositional logic can model increasingly sophisticated real-world scenarios. The graduation rule exemplifies how expert systems can capture the nuanced requirements of institutional policies, making automated decision-making more robust and reflective of actual operational complexities.

This mini expert system serves as a foundation for understanding how logical reasoning can be systematically applied to automate decision-making processes in educational and administrative contexts.

## Images of the Program Running
![Alt text](/assets/images/pl/ss1.jpg "Image title")
![Alt text](/assets/images/pl/ss2.jpg "Image title")
![Alt text](/assets/images/pl/ss3.jpg "Image title")
![Alt text](/assets/images/pl/ss4.jpg "Image title")
![Alt text](/assets/images/pl/ss5.jpg "Image title")