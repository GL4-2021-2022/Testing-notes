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
