# 🚀 Compiler Design Toolkit

A practical collection of Compiler Design programs including Lexical Analysis, FIRST & FOLLOW computation, Predictive Parsing, and FLEX/Bison implementations.

---

## 🛠️ Tech Stack

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Flex](https://img.shields.io/badge/FLEX-Lexical%20Analyzer-blue?style=for-the-badge)
![Bison](https://img.shields.io/badge/Bison-Parser-orange?style=for-the-badge)

---

## 📚 Contents

- 🔹 Lexical Analyzer using FLEX  
- 🔹 Basic FLEX Programs  
- 🔹 Left Recursion & Left Factoring  
- 🔹 FIRST & FOLLOW Computation  
- 🔹 Predictive Parsing Table  
- 🔹 Calculator using FLEX & Bison  

---

## ⚙️ How to Run

### FLEX Program
```bash
flex file.l
gcc lex.yy.c -o output -lfl
./output
```

### FLEX + BISON Program
```bash
bison -d file.y
flex file.l
gcc file.tab.c lex.yy.c -o output -lfl
./output

