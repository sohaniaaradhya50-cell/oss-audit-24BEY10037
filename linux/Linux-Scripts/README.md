Open Source Software Audit & Shell Scripting Project
Aaradhya sohani
Reg. No. - 24BEY10037
Software Focus: Python

Project Overview
Contains Bash scripts to perform a system audit and demonstrate core Linux shell scripting concepts. The project focuses on auditing a system where Python is the open-source software choice.

Script Descriptions
Script1. System Identity Report
Generates a  header showing the auditor's name, the chosen software and real-time system data including Kernel version and distribution details.
Concepts used: Variables, Command Substitution.

Script2. FOSS Package Inspector 
Queries the system package manager to verify the installation of Python. Provides versioning and licensing information.
Concepts: If-then-else logic, Case statements.

Script3. Disk and Permission Auditor
Iterates through critical system directories (/etc, /var/log, /usr/lib/python3) to report on disk usage and security permissions.
Concepts: For loops, awk, cut.

Script4. Log File Analyzer
Scans system logs line-by-line to identify and count specific keywords like "error" or "warning."
Concepts: While-read loops, Counters, Command-line arguments.

Script5. Open Source Manifesto Generator 
Collects user values regarding open-source philosophy and generates a personalized manifesto saved as a text file.
Concepts: User input (read), String concatenation, Output redirection.

How to Run
Ensure the scripts have execution permissions:
Bash
chmod +x *.sh

Run any script using:
Bash
./script_name.sh

License
This project is part of an academic audit. The Linux environment and scripts within are governed by the GNU General Public License (GPL) v2.
