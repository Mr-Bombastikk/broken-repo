# Assignment 1: Sensor Data Generator

## Description
This program is written in C++ and simulates a simple sensor data generation system. It generates random sensor readings and stores them in different files and directories. The program also creates log files, temporary files, cache data, and a fake executable file as part of demonstrating file handling operations in C++.

## What the Program Does
When executed, the program performs the following tasks:

1. Creates an `output/` directory (if it does not already exist).
2. Generates a file `output/sensor_data.txt` containing:
   - A sensor data log header
   - Five random sensor readings (0–99 units)
3. Appends execution time (UNIX timestamp) to `run.log`.
4. Creates a temporary file `temp.tmp` with a random value.
5. Creates a fake executable file named `program.exe`.
6. Creates a `cache/` directory and stores cached data in `cache/cache.data`.

## Output / Directory Explanation

After running the program, the following files and directories are created:

### 1. output/
- Contains `sensor_data.txt`
- Stores simulated sensor readings generated using random values

### 2. run.log (root directory)
- Keeps a record of program execution times
- Each run appends a new timestamp

### 3. temp.tmp (root directory)
- Stores temporary data generated during execution
- Used as a sample buffer file

### 4. program.exe (root directory)
- A dummy file created to simulate an executable artifact

### 5. cache/
- Contains `cache.data`
- Stores cached random values for simulation purposes

## Note
- Random values are generated using `rand()` seeded with current time.
- The program demonstrates file handling, directory creation, and basic system commands in C++.