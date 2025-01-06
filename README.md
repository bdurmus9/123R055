
# 123R055 - Chaotic System-Based Binary Datasets

This repository contains binary datasets generated from chaotic systems using three different data purification techniques. These datasets were prepared to evaluate their randomness and statistical properties using the NIST Statistical Test Suite, as described in our paper.

## Repository Structure

  - `METHOD 1/`: Datasets generated using the first five decimal places.
  - `MWTHOD 2/`: Datasets generated using the first six decimal places.
  - `METHOD 3/`: Datasets generated using all decimal places.

## Data Purification Techniques

1. **Method 1:**
   - Extracted the first five decimal places from each chaotic value (**x**, **y**, **z**).
   - Applied a modulo 256 operation to constrain values within the 8-bit range.
   - Converted the results into 8-bit binary strings.

2. **Method 2:**
   - Similar to Method 1 but used the first six decimal places for finer granularity.
   - Followed the same steps of modulo 256 and binary conversion.

3. **Method 3:**
   - Used all decimal places of each chaotic value.
   - Applied a modulo 256 operation and converted the results into binary strings.


