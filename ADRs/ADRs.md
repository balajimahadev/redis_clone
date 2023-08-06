
## ADR-MYREDIS-001-08062023

### Title
Selecting the programming language for the purpose of building a REDIS clone

### Context
Selecting a programming language that will allow the implementation of a redis like clone. This mean the language should support a web server based protocol handler and allow an easy implementation of in-memory data structures ( e.g. AVL trees). Most server side programming languages support these basic requirements ( Java, Python, Rust, GoLang). Python was chosen for lower learnability curve.

### Decision
Made decision to use Python

### Status
Current

### Consequences
* Pros - meets your learning objectives
* Cons - Enterprises are most likely to choose C++, Java or Golang for this purpose. Hence this might not mimic a real world decision.