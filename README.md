# [NVIDIA DLI - Advanced Technical Workshop: Fundamentals of Accelerated Computing with CUDA C/C++](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+C-AC-01+V1) - COMPLETED!

# NVIDIA Deep Learning Institute's (DLI) Fundamentals of Accelerated Computing with CUDA C/C++

This repository provides an overview of the **Fundamentals of Accelerated Computing with CUDA C/C++** course, offered by NVIDIA's Deep Learning Institute (DLI). The course is designed to teach developers how to accelerate and optimize existing C/C++ applications using CUDA to harness the immense computational power of GPUs.

## Learning Objectives

- Write, compile, and run C/C++ programs that utilize both CPU functions and GPU kernels.
- Parallelize serial code by refactoring loops to run on GPUs.
- Manage memory efficiently between the CPU and GPU using CUDA tools like Unified Memory.
- Optimize applications by exposing parallelism and leveraging CUDA streams for concurrency.
- Use command-line and visual profiling tools to assess and improve application performance.

## Overview of CUDA

CUDA (Compute Unified Device Architecture) is a parallel computing platform and programming model developed by NVIDIA. It allows developers to use NVIDIA GPUs for general-purpose processing (GPGPU), enabling massive parallelism that can significantly accelerate computational tasks.

### Key Concepts in CUDA

- **GPU Kernels**: Functions executed in parallel on the GPU.
- **Thread Hierarchy**: Organizing threads into blocks and grids for efficient parallel execution.
- **Memory Management**: Techniques like Unified Memory to manage data transfer between CPU and GPU memory.
- **Streams**: Mechanisms for asynchronous execution, allowing concurrent kernel execution and memory transfers.

## Hands-On Exercises

The course emphasizes practical experience through hands-on labs, where participants will:

1. Write and compile CUDA C/C++ programs that offload computations to the GPU.
2. Refactor serial loops to execute in parallel using GPU threads.
3. Optimize memory usage with CUDA Unified Memory, reducing overhead from manual memory transfers.
4. Use asynchronous streams to overlap computation with data transfers for improved performance.

### Key Tools, Libraries, and Frameworks

- **CUDA Toolkit**: A collection of tools, libraries, and APIs for developing GPU-accelerated applications.
- **Nsight Systems**: A performance analysis tool for optimizing CUDA applications.
- **nvprof & nsys**: Command-line profilers used to analyze kernel execution times and memory usage.

## Memory Management and Optimization

One major focus of the course is teaching how to manage memory efficiently between the CPU and GPU using **CUDA Unified Memory**, which simplifies memory allocation by automatically migrating data between host and device as needed. Participants will also learn how to optimize memory transfers using techniques like asynchronous prefetching.

### Key Benefits of Unified Memory:
- Simplifies memory management by eliminating manual data transfers.
- Reduces development time while maintaining high performance.
  
## Asynchronous Streaming for Concurrency

The course also covers how to use **CUDA streams** to enable asynchronous execution, allowing participants to overlap kernel execution with memory transfers. This results in better utilization of GPU resources and improved application performance.

### Benefits of Asynchronous Execution:
- Overlap computation with data transfers for better resource utilization.
- Execute multiple kernels concurrently for faster overall execution.

## End-to-End Workflow Acceleration

The course emphasizes building efficient workflows where every stage—from writing GPU kernels to optimizing memory usage—is optimized using profiling tools like Nsight Systems. By integrating these tools into their workflow, participants can achieve significant speedups compared to traditional CPU-based methods.

### Benefits of Optimized Workflows:
- Faster execution times due to parallelization on GPUs.
- Scalability across larger datasets without sacrificing performance.

## Final Project: Particle Simulation Acceleration

In the final project, participants will apply their knowledge by accelerating a fully functional CPU-only particle simulator. This project will involve:

- Writing GPU kernels to simulate particle interactions in parallel.
- Managing memory between the CPU and GPU efficiently using Unified Memory.
- Profiling the application using Nsight Systems to identify bottlenecks and improve performance.

## Prerequisites

Participants should have basic competency in C/C++, including familiarity with variable types, loops, conditional statements, functions, and arrays. No prior knowledge of CUDA programming is required.

Suggested preparation materials:
- Introductory C/C++ programming tutorials
- Basic understanding of parallel computing concepts

## Certificate

Upon successful completion of the course assessment, participants will receive an official **NVIDIA DLI certificate**, recognizing their subject matter competency in accelerated computing with CUDA C/C++.

## Conclusion

By completing this course, participants will gain hands-on experience in accelerating real-world applications using CUDA. The knowledge gained will enable them to:

- Refactor existing CPU-based applications for massive speedups using GPUs.
- Build new GPU-accelerated applications from scratch.
- Apply advanced optimization techniques like asynchronous streaming and memory management.

This course is ideal for developers who are familiar with C/C++ programming but want to explore how GPU acceleration can dramatically improve performance in computationally intensive tasks.


## Instructor-Led Workshop Outline:

<p style="text-align:center">
    <a href="https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+C-AC-01+V1" target="_blank">
    <img src="nvidia_cuda_portfolio/images/Workshop_Outline_FAC_CUDA_C_CPP.png" alt="NVIDIA-DLI-Fundamentals of Accelerated Computing with CUDA C/C++"  />
    </a>
</p>

## [Certificate Of Competency:](https://learn.nvidia.com/certificates?id=d747aca4c5f9467cb46d785ed401c6ea)

<p style="text-align:center">
    <a href="https://learn.nvidia.com/certificates?id=d747aca4c5f9467cb46d785ed401c6ea" target="_blank">
    <img src="nvidia_cuda_portfolio/images/CC_FAC_CUDA_C_CPP.png" alt="NVIDIA-DLI-Fundamentals of Accelerated Computing with CUDA C/C++"  />
    </a>
</p>
