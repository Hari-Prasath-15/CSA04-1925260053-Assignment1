# Operating Systems – Assignment 1
## Evaluate and Justify the Operating-System Design of a Smart Hospital

### Student Details
- **Name:** Hari Prasath V G
- **Register Number:** 1925260053
- **Course:** B.Tech – Artificial Intelligence and Machine Learning
- **Subject:** Operating Systems

### System Information
- **Operating System:** Ubuntu
- **OS Version:** Ubuntu 24.04 LTS
- **Compiler:** GCC
- **GCC Version:** 13.3.0

### Compilation Command
The following GCC command is used to compile the C programs:

```bash
gcc -std=c11 -Wall -Wextra -pthread filename.c -o output
```

Replace `filename.c` and `output` with the appropriate source filename and executable name. Use the exact command actually used for each program.

### Repository Structure

```text
CSA04-RegisterNumber-Assignment1/
│
├── Task05/
├── Task06/
├── Task07/
├── Task08/
├── Task09/
├── Task10/
├── Task11/
├── Task12
│
└── README.md
```

Each task folder contains its relevant source code, scripts, input files, output files and screenshots wherever applicable.

### Task Results

| Task | Description | Result |
|---|---|---|
| Task 1 | Requirements of Each Environment | Evaluated the operating-system requirements of the hospital environments. |
| Task 2 | Types of Operating Systems | Compared and selected suitable OS types for each hospital environment. |
| Task 3 | Operating-System Structures | Evaluated different OS structures and justified suitable choices. |
| Task 4 | Operating-System Services | Identified essential OS services for each environment. |
| Task 5 | System Calls | Studied system-call categories and the execution of system calls. |
| Task 6 | Cost of System Calls | Executed the file-copy program and compared system-call counts for different buffer sizes. |
| Task 7 | Process Control System Calls | Demonstrated process creation and management using fork(), exec() and waitpid(). |
| Task 8 | CPU States and Protection | Evaluated CPU modes, interrupts and hardware protection mechanisms. |
| Task 9 | Memory Hierarchy and I/O | Evaluated memory levels, data placement and I/O methods. |
| Task 10 | Measurement and Comparison | Measured and compared process, thread and system-call performance. |
| Task 11 | Final OS Recommendation | Recommended and justified a complete operating-system plan for the hospital. |
| Task 12 | Day-4 Design Challenge | Re-evaluated and adapted the hospital OS design for remote monitoring and cloud records. |

### How to Run the Programs

1. Open the required task folder.
2. Open a Linux terminal in that folder.
3. Compile the C program using the appropriate GCC command.
4. Run the generated executable.

Example:

```bash
gcc -std=c11 -Wall -Wextra program.c -o program
./program
```

For programs requiring additional libraries or command-line arguments, use the specific compilation and execution commands provided in that task's folder.

### Conclusion

This repository contains the work completed for Operating Systems Assignment 1, including task-wise analysis, C programs, execution results, measurements and supporting evidence for evaluating the operating-system design of a smart hospital.
