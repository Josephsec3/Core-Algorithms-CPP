# Efficient Odd Number Counter in C++

## 🚀 Overview
This repository contains a highly optimized C++ solution designed to count the number of odd integers within a given array or sequence across multiple test cases.

## 🛠️ Performance Optimizations
The code utilizes advanced input/output competitive programming practices to reduce execution time constraints:
* `ios_base::sync_with_stdio(false);`: Disables the synchronization between the C and C++ standard streams, significantly speeding up standard I/O operations.
* `cin.tie(nullptr);`: Unties `cin` from `cout`, ensuring that input operations do not cause unnecessary flushing of the output buffer.

## 💻 Logic & Analogy
The program reads $t$ test cases. For each case, it processes $n$ numbers dynamically on the fly:
```cpp
done += curr % 2;
