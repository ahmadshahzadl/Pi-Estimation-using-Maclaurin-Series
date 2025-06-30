# Pi Estimation using Sequential and Parallel Approaches

This project demonstrates the estimation of the value of π (Pi) using both **sequential (single-threaded)** and **parallel (multi-threaded)** implementations in C++. It also includes a detailed project report and visual illustrations of the implementation logic and threading.

## Contents

- `Project_Report.docx` – Detailed documentation explaining the objective, methodology, and results.
- `Sequential (Single Thread) Code.cpp` – C++ implementation of Pi estimation using a single thread.
- `Parallel (Multi Thread) Code.cpp` – C++ implementation of Pi estimation using multiple threads.
- `Sequential ( Single Thread ).png` – Visualization of the sequential implementation logic.
- `Parallel (MultiThread).png` – Diagram representing the multi-threaded logic.
- `Parallel Thread Function (calculate_pi).png` – Illustration of the parallel function for thread execution.

## Requirements

- C++ Compiler (e.g., `g++`)
- C++11 or higher (for threading support)
- Linux/Windows with `pthread` support (for multi-threading)

## How to Compile and Run

### Sequential Version

```bash
g++ -o pi_sequential "Sequential (Single Thread) Code.cpp"
./pi_sequential
```

### Parallel Version

```bash
g++ -o pi_parallel "Parallel (Multi Thread) Code.cpp" -pthread
./pi_parallel
```

## Summary

This project compares the performance and accuracy of estimating Pi:
- **Sequential approach**: Uses a simple loop with alternating signs to estimate Pi.
- **Parallel approach**: Splits computation across threads to improve performance.

The report provides an in-depth comparison between the two implementations in terms of execution time and efficiency.

## Author

*Ahmad Shahzad*