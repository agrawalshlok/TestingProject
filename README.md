# SegmentTree Project

## **Project Aim**

The aim of this project is to implement **Mutation Testing** on our custom implementation of a **Segment Tree** data structure. The project focuses on testing and ensuring the robustness of the Segment Tree implementation through unit and integration-level mutation testing.

---

## **Tools Used**

- **PIT Mutation Testing**: For mutation testing in Java.
- **JUnit**: For writing and executing unit test cases.
- **IntelliJ IDEA**: IDE for Java development.
- **Maven**: For project building and dependency management.

---

## **Mutation Operators Used**

### **Mutation Operators Used at Unit Level**

1. **Arithmetic Operator Replacement (AOR)**: Mutates arithmetic operators (`+`, `-`, `*`, `/`).
2. **Conditional Operator Replacement (COR)**: Mutates conditional operators (e.g., `&&`, `||`).
3. **Relational Operator Replacement (ROR)**: Mutates relational operators (e.g., `>`, `<`, `==`).
4. **Logical Operator Replacement (LOR)**: Mutates logical operators (`!`, `&&`, `||`).
5. **Assignment Operator Replacement (ASR)**: Mutates assignment operators (e.g., `+=`, `-=`, `*=`, `/=`).
6. **Constant Replacement (COI)**: Replaces constants with different values.

### **Mutation Operators Used at Integration Level**

1. **Integration Parameter Exchange (IPEX)**: Swaps parameters during method calls in integration tests.
2. **Integration Method Call Deletion (IMCD)**: Deletes calls to certain methods in integration scenarios.
3. **Integration Return Expression Modification (IREM)**: Alters return values of methods in integration testing.

---

## **Command to Execute Mutation Testing**

1. Clean and install the project:
```bash
mvn clean install 
```
2. Run mutation testing:
```bash
mvn org.pitest:pitest-maven:mutationCoverage
```

## **Contribution**
#### Shlok Agrawal
- Implemented methods for query operations like **maximum**, **minimum**, **sum**, and **quadrant queries** in the Segment Tree.
- Designed and tested the **Dynamic Segment Tree** for overlapping intervals.
- Developed utility functions for **query optimization** and **performance debugging**.

#### Madhav Sood
- Implemented methods for building **Flat Segment Tree** for non-overlapping intervals.
- Worked on **edge case handling**, including segment validation and error handling for overlapping segments.
- Designed and tested **utility functions** for **visualization** and **debugging** of the Segment Tree.


