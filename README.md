# Student Record Management System

**Document date:** 20 November 2023  

## Overview

This repository contains **Student Record Management System**, a command-line application developed as my **first C++ programming project** during **Semester 1** of my **diploma programme**. The program was implemented to consolidate introductory coursework in structured programming, console-based user interaction, and basic data handling by modelling a simple academic records workflow for a secondary school context.

The system allows an authorised user to maintain student information—including identification details, subject scores, attendance, and derived outcomes such as pass or fail—through a text-based menu. It was designed as a formative assessment piece to demonstrate logical control flow, input validation, and modular thinking before progressing to more advanced topics in later semesters.

## Platform

The executable included in this repository (`student_record_system`) was built for **macOS on Apple Silicon (arm64)**. It is intended for local demonstration on compatible Mac hardware.

## How to run

1. **Clone this repository** (or download and extract the project folder).

2. **Open a terminal** and change into the root folder of the cloned repository (the directory that contains `student_record_system` and this `README.md`).

3. **Ensure the program can be executed** (if needed):

   ```bash
   chmod +x student_record_system
   ```

4. **Run the application:**

   ```bash
   ./student_record_system
   ```

5. Follow the on-screen prompts. The program will ask for a teacher password, then present menu options to create, view, modify, or delete student records, consistent with the coursework scenario (including the sample school context used in the module brief).

### If execution is blocked

On recent versions of macOS, you may need to allow the binary under **System Settings → Privacy & Security** if Gatekeeper flags an unidentified developer. Use only binaries from sources you trust.

## Note on source code

Original C++ source files are not published in this repository; only the compiled macOS binary is provided here for archival and demonstration purposes. If you are assessing or reviewing this work and require source artefacts, please contact me.
