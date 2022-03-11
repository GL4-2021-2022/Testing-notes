# Testing-notes

## Fundamentals

### Software State

- Static : Test code for linting and style issues
- Dynamic : Test software functionality

### Importance of software testing

- No straight forward process
- Depends on software requirements
- Objectives :
  - prevents defects by evaluating requirements
  - verifies requirements fulfillment
  - verifies software behavior
  - find defects
  - comply with contract
- Tester roles :
  - review requirements and prevent ambiguity in definition
  - collaborate with dev to ensure requirements are understood and define tests
  - detect errors and report software readiness

### Error vs. Defect vs. Failure

- misunderstanding of a requirement , error -> invalid user story , defect -> wrong code, defect -> issues while running , failure
- error -> defect -> failure

### code defects

- Lack of skills
- Communication problems
- Time pressure
- Absence of clear test procedure

### Quality assurance QA vs Software testing

- Quality assurance, has as a process quality management, and within this quality management we can do software testing.
- Testing is part of QA

### FP & FN

- False positive : Tests fails due to an error unrelated to software like Data ( badly structured data ... ) , environment ( Wrong java version ... )
- False negative : Test is not detecting existing defects
- Input + Preconditions => Output , Defect related to Preconditions are hard to detect and reproduce

## Testing process and activities

### TDD

Test driven development :

- Write unit tests before components and work to comply with those tests

### Test levels

- Components test
  - Separate Unit / Module tests
  - Objectives :
    - verify module functionality
    - prevent regression
    - Assure component quality
    - prevent defects from escaping to higher level ( Snowball effect )
  - Objects ( Targets ):
    - Class
    - Module
    - Function
    - Data structure
  - Detected defects :
    - Incorrect logic
    - Edge cases
- Integration test
  - focuses on data flow between components
  - finds defect on interactions between system parts
- System test

  - Validates the complete and fully integrated software product
  - Black box testing : The testing software has no idea what's inside the system
  - Objectives :
    - evaluate the end-to-end system specifications
    - check compliance between input and outputs

- Acceptance tests
  - black box test
  - performed by clients
  - final phase
  - validates businesses procedure
  - as close as possible to production environment

### Test process context

- Product risk
- Business domain
- operation constraints
- External / Internal policies
- SDLC : Software development lifecycle
  - SDLC has a big impact of software testing
  - Types :
    - Sequential :
      - Waterfall :
        - Requirement analysis
        - design
        - coding
        - testing ![w](water.jpg)
      - V-Model : For every activity there's a test level ![v](vmodel.png)
  - Iterative / Agile
    - Incremental testing
    - test activities overlap
    - test targets / object have minor changes which catches defects faster

### Test Process

### Test activities
