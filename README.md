# MapReduce Word Count Project

## Overview
This project demonstrates the **MapReduce** programming model, which is used to process large datasets in a distributed environment. The application performs a **Word Count**, where it counts how many times each word appears in one or more text files.

The project follows the MapReduce workflow:
1. **Mapper** – Reads input data and emits key-value pairs `(word, 1)`.
2. **Shuffle and Sort** – Groups identical words together.
3. **Reducer** – Sums the counts for each word and produces the final output.

---

## Features
- Counts the frequency of words in large text files.
- Demonstrates the MapReduce programming model.
- Scalable for processing large datasets.
- Handles multiple input files.
- Outputs the total count of each unique word.

---

## Project Structure
