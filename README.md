# Python-Formmative-Assesment

**Time Limit:** 90 Minutes
**Topic:** Python Fundamentals, Logic & Test Driven Development (TDD)

## 📋 Overview

Welcome to the **System Check** assessment. You have been tasked with building the logic for a Flight Ticket Parser and a Nuclear Reactor Safety Monitor.

This is an **invigilated assessment**. You are required to demonstrate not just your ability to write code, but your ability to write **tests** for that code.

## 📂 File Structure

* `system_check.py` 📝 **(EDIT THIS)**
    * This file contains the empty functions you need to complete.
    * **Do not rename** any functions or the file itself.
* `test_reactor.py` 🆕 **(CREATE THIS)**
    * You must create this file from scratch.
    * This file will contain the Unit Tests for Question 5.

## 🚀 Instructions

### Section A: Flight Data Parsing (Questions 1-3)
Open `system_check.py`. You will need to parse string data from flight tickets.
* **Warning:** The data is not always the same length! You cannot use fixed indices (e.g., `text[0:5]`). You must logically find the hyphens `-`.

### Section B: Algorithmic Logic (Question 4)
Implement the logic for determining a **Leap Year**. This requires nested or chained modulo (`%`) operators.

### Section C: The Reactor Monitor (Question 5)
**This section requires Test Driven Development (TDD).**

1.  Read the requirements for `reactor_status` in `system_check.py`.
2.  **BEFORE** you write the logic, create a new file named `test_reactor.py`.
3.  Implement the `TestReactor` class and write tests for all scenarios (Critical, Warning, Normal, etc.).
4.  Once your tests are written, go back to `system_check.py` and write the code to pass them.

## 🧪 How to Run Your Tests

To verify your Reactor Logic, run your test file:

```bash
python test_reactor.py
