# 🎓 University of Maryland, College Park Course Projects Portfolio
A curated list of course projects from my time at the University of Maryland, College Park, covering Computer Science coursework.

---

## CMSC 330: Organization of Programming Languages

---

### ⚙️ Regular Expression Engine
**🔗 Repo:** [cmsc330-regex-engine]()  
**📝 Language:** OCaml

Built a full regex engine in OCaml, implementing:
- Simulation of NFAs (`accept`)
- Subset construction algorithm to convert NFAs to DFAs (`nfa_to_dfa`)
- Regex to NFA conversion (`regex_to_nfa`)

This modular architecture allowed chaining these conversions to interpret regular expressions via finite automata. 

---

### 🔤 Lexer, Parser, and Evaluator for SmallC
**🔗 Repo:** [cmsc330-smallc-parser]() 
**📝 Language:** OCaml

Implemented a lexer and parser for a simplified C-like language (SmallC). The lexer tokenizes input strings into SmallC tokens, while the parser converts them into an abstract syntax tree (AST).  
- Full grammar handling for expressions and statements
- Robust exception handling (`InvalidInputException`) for malformed input

This project solidified my skills in syntax processing and recursive-descent parsing, key for compiler construction.

---

## 🔧 Optimizer and Type Checker for SmallC
**🔗 Repo:** [cmsc330-smallc-typecheck-opt]()  
**📝 Language:** OCaml

Expanded the SmallC language pipeline by building:
- An **optimizer** (constant folding, propagation, and loop unrolling)
- A **type inference engine** to assign types to untyped variables
- A **type checker** to ensure program correctness before runtime

This project demonstrated how high-level language semantics are enforced and how performance can be enhanced through static transformations.

---

## 🗑️ Garbage Collector Implementations
**🔗 Repo:** [cmsc330-garbage-collector]()  
**📝 Language:** Rust

Implemented three core memory management techniques:
- **Reference Counting**
- **Mark and Sweep**
- **Stop and Copy**

Each collector mimics real-world garbage collection strategies, highlighting their tradeoffs in time/space complexity and memory safety. Gave me a solid foundation in how high-level runtimes manage memory behind the scenes.

---





## CMSC 335: Web Application Development with Javascript


