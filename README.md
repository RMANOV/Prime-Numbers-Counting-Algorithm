# Prime Numbers of the Form p² + 4q² Finder

## Overview
This project implements a highly optimized algorithm for finding prime numbers that can be expressed in the form p² + 4q², where both p and q are also prime numbers. Based on the groundbreaking research by Ben Green (Oxford) and Mehta Sohni (Columbia University), this implementation provides both high-performance computation and mathematical elegance.

## Technical Highlights
- **Advanced Algorithmic Approach**: Utilizes a sophisticated combination of number theory and modern computing techniques
- **Multi-threaded Processing**: Implements parallel computation for optimal performance on multi-core systems
- **NumPy Vectorization**: Leverages numpy's powerful array operations for enhanced computational speed
- **Memory Optimization**: Employs smart caching strategies with @lru_cache decorator
- **Flexible Architecture**: Offers both batch processing and streaming capabilities

## Key Features
- **Parallel Processing Engine**: Efficiently distributes workload across multiple CPU cores
- **Smart Prime Generation**: Uses optimized Sieve of Eratosthenes with numpy arrays
- **Caching System**: Implements intelligent memoization for repeated calculations
- **Stream Generator**: Provides infinite sequence generation capability
- **Benchmarking Tools**: Includes performance measurement utilities

## Performance
The implementation achieves remarkable efficiency through:
- Vectorized operations reducing computational overhead
- Parallel processing enabling near-linear scaling with CPU cores
- Optimized prime number generation and primality testing
- Smart memory management and caching strategies

## Mathematical Significance
This implementation tackles a significant mathematical problem, proving the infinity of primes of the form p² + 4q². The algorithm represents a practical application of advanced number theory concepts, including:
- Prime number distribution patterns
- Quadratic forms in number theory
- Computational number theory optimization

## Usage
The code supports both high-performance batch processing for specific ranges and continuous generation of special prime numbers, making it suitable for both research and practical applications.

## Implementation Details
Written in Python 3.8+, the code combines modern language features with high-performance computing practices:
- Type hints for better code reliability
- Generator expressions for memory efficiency
- Multiprocessing for parallel computation
- NumPy for optimized numerical operations

This project demonstrates how theoretical mathematics can be transformed into efficient, practical code while maintaining mathematical rigor and computational performance.
