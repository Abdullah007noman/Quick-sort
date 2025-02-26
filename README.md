
# Quicksort Algorithm Implementation

This repository contains various implementations of the Quicksort algorithm in Python, with a focus on different pivot selection strategies and performance benchmarking.

## Overview

Quicksort is a divide-and-conquer sorting algorithm that works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays according to whether they are less than or greater than the pivot. The sub-arrays are then sorted recursively.

This repository explores:
- In-place and non-in-place implementations
- Different pivot selection strategies
- Performance benchmarking across best, worst, and average cases

## Files in this Repository

1. `Random_pivot_Quick_sort.ipynb` - Implementation of quicksort with random pivot selection
2. `Non_random_pivot_Quick_sort.ipynb` - Implementation of quicksort with various deterministic pivot selection strategies
3. `Quicksort_benchmarking.ipynb` - Comprehensive benchmarking for quicksort with visualizations

## Implementations

### Random Pivot Selection

- **Non-in-place quicksort** with random pivot selection
- **In-place quicksort** with random pivot selection

### Non-Random Pivot Selection

- **First element** as pivot (non-in-place)
- **Last element** as pivot (non-in-place)
- **Middle element** as pivot (non-in-place)
- **Median-of-three** as pivot (non-in-place)
- **In-place quicksort** with last element as pivot

## Benchmarking

The benchmarking notebook provides performance analysis across:

1. **Best Case Scenarios** - Input arrays that produce the optimal performance for quicksort
2. **Worst Case Scenarios** - Input arrays that produce the worst performance for quicksort
3. **Average Case** - Randomly generated arrays from a uniform distribution

All benchmarks are run on multiple array sizes to demonstrate algorithmic complexity.

## Performance Analysis

The repository includes visualizations showing:
- Time complexity comparisons between different pivot selection strategies
- Performance differences between best, worst, and average cases
- Verification of the theoretical time complexity (O(n log n) for average case, O(n²) for worst case)

## How to Run

1. Clone the repository
2. Open the notebooks in Google Colab or any Jupyter notebook environment
3. Run the cells to see the implementations and benchmark results

## Results

The benchmarking results demonstrate:
- How random pivot selection helps avoid worst-case scenarios
- The effectiveness of median-of-three pivot selection compared to simpler strategies
- The performance impact of in-place vs. non-in-place implementations

## Dependencies

- Python 3.x
- NumPy (for generating test arrays)
- Matplotlib (for plotting benchmark results)
- Jupyter/Google Colab (for running notebooks)
