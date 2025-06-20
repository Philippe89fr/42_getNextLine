## GetNextLine - 42

# Description:
Get Next Line is a function that reads and returns one line at a time from a file descriptor, making file reading more efficient and manageable. This project introduces the concept of static variables in C programming and focuses on buffer management. The function must handle various buffer sizes, work with multiple file descriptors, and properly manage memory while reading files line by line. 

# Context:
Part of 42 Common Core.

# Main Technologies / Skills Used:

- **Programming Languages: C**
- **Static Variables:** Understanding persistent state between function calls
- **Buffer Management:** Efficient reading and storing of file data with configurable buffer sizes
- **File Descriptor Management:** Low-level file handling using read() system call
- **Memory Management:** Dynamic allocation and proper memory cleanup to prevent leaks
- **String Manipulation:** Line parsing, concatenation, and newline character handling
- **Algorithm Design:** Efficient line extraction and buffer optimization strategies
- **Error Handling / Parsing:** Managing EOF conditions, read errors, and edge cases
- **Makefile Management:** Compilation with configurable buffer size flags
- **Edge Case Management:** Managing various file types, buffer sizes, and multiple file descriptors

# Installation and compilation
1. Clone this repository into your project:
```bash
git clone git@github.com:Philippe89fr/42_getNextLine.git
```
2. Run the following command:
```bash
make
```
3. with bonus:
```bash
make bonus
```
