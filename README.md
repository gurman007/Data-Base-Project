#  Graph-Based Vulnerability Detection: CWE-590 using Neo4j + Code Property Graph (CPG)

**Project ID: H366163304**  
**Topic:** Static Analysis of CWE-590 Vulnerabilities Through Graph Query Languages

---

##  What is CWE-590?

CWE-590: Free Memory Not on Heap occurs when stack-allocated memory is deallocated using heap deallocation (`delete[]`).  
It leads to undefined behavior and critical memory errors.

---

##  Project Setup

- **Source Code:** Juliet Test Suite (CWE-590)
- **Parser:** [Fraunhofer CPG](https://github.com/Fraunhofer-AISEC/cpg)
- **Database:** Neo4j (via Docker)
- **Language:** C++
- **Visualization:** Cypher queries in Neo4j browser

---

##  Pipeline
[C++ Code] → [CPG Parser] → [Neo4j Graph DB] → [Cypher Queries] → [Results]
