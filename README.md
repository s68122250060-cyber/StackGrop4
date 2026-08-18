# Stack Algorithm - Group 04
## Expression Processor: Infix and Postfix

Java project for the Stack algorithm group assignment.

### Run
```bash
javac -d out $(find src -name "*.java")
java -cp out group4.Main
```

Performance experiment:
```bash
java -cp out group4.ExperimentRunner
```

### Repository contents
- `src/` Java source code
- `test/` mandatory test cases
- `results/` experiment results
- `diagrams/` flowchart and class diagram
- `report/` final report
- `presentation/` presentation files
- `group-members.md` member contributions

### Algorithms
- Algorithm A: Infix -> Postfix -> Evaluation
- Algorithm B: Direct Infix Evaluation with two stacks

Both algorithms are O(n) time and O(n) auxiliary space. Algorithm B is expected to have a smaller practical constant factor for one-shot evaluation.
