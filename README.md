# Python Lab Work

A collection of all my **Python programming** lab sheet solutions, from basic input/output and control flow to data structures, file handling and database programming with SQLite.

| | |
|---|---|
| **Name** | Shivani |
| **Roll No.** | CU26280050 |
| **Course** | MCA I Semester (Session 2026-2027), Python Programming |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)
![CSV](https://img.shields.io/badge/CSV-File%20Handling-green)

Only the Python standard library is used (`sqlite3`, `csv`, `os`). **Nothing extra needs to be installed.**

---

## Repository Structure

| Lab Sheet | Topic | Programs |
|-----------|-------|----------|
| [LabSheet01](./LabSheet01) | Basics: input/output, arithmetic, swapping, interest and BMI calculations, unit conversions, simple conditions, prime check | 30 |
| [LabSheet02](./LabSheet02) | Control flow and loops: grades, Armstrong, palindrome, factorial, Fibonacci, primes, HCF/LCM, number patterns, multiplication tables | 30 |
| [LabSheet03](./LabSheet03) | Strings and lists: palindrome, anagram, character frequency, word count, rotations, substrings, sorting, duplicates, second largest | 30 |
| [LabSheet04](./LabSheet04) | Lists and dictionaries: list operations, merge/sort/invert dictionaries, word frequency, nested dictionaries | 30 |
| [LabSheet05](./LabSheet05) | Tuples: creation, indexing, slicing, nesting, flattening, conversions, element-wise operations | 30 |
| [LabSheet06](./LabSheet06) | Sets: set operations, power set, Cartesian product, frozenset, anagram using sets | 30 |
| [LabSheet07](./LabSheet07) | File handling: text and CSV read/write/append, search, copy, merge, statistics | 30 |
| [LabSheet08](./LabSheet08) | Database management with SQLite: tables, CRUD, joins, aggregates, CSV import/export, menu-driven app | 30 |
| [LabSheet09](./LabSheet09) | CRUD operations using in-memory data, text files and a database | 20 |

Each program is a separate `.py` file named after the question (for example `Q7_reverse_string.py`).

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/Shivvani15/Shivani_Python_CU26280050.git
cd Shivani_Python_CU26280050
```

### Prerequisites

- **Python 3.8+** ([download](https://www.python.org/downloads/))

Check your version:

```bash
python --version
```

---

## How to Run

Open a terminal inside the lab sheet folder and run any program:

```bash
cd LabSheet01
python Q1_addition.py
```

On some systems the command is `python3` instead of `python`.

### Special instructions

**LabSheet07 (File Handling)**
- Run the programs **from inside the `LabSheet07` folder**, because they read and write files in the current directory.
- Some programs depend on files created by earlier ones. For example, program `21_create_csv.py` creates `students.csv`, which programs 22 to 30 use. Run the programs in numeric order (01 → 30) the first time.

**LabSheet08 (SQLite Database)**
- All 30 programs share one database file, `student_db.db`, which is **created automatically** in the same folder.
- Each program creates the tables and sample data it needs, so you can run any one of them on its own, or all of them in order.
- Keep `db_config.py` in the same folder, since every program imports it.
- Programs 16, 17 and 18 have constants at the top (`STUDENT_ID`, `NEW_MARKS`, ...) that you can edit.
- Detailed program list: see [LabSheet08/README.md](./LabSheet08/README.md).

**LabSheet09 (CRUD)**
- Programs 1 to 10 work with in-memory lists/dictionaries and text files.
- Programs 11 to 20 use SQLite (`student_db.db`) through the shared `db_config.py`.
- Many programs are menu-driven and ask for input in the terminal.

---

## Topics Covered

- Variables, data types, operators, user input and formatted output
- Conditional statements (`if / elif / else`) and loops (`for`, `while`)
- Strings, lists, tuples, sets and dictionaries
- Functions, modular code and exception handling (`try / except / finally`)
- Reading and writing text and CSV files
- SQLite database programming: `CREATE`, `INSERT`, `SELECT`, `UPDATE`, `DELETE`, `JOIN`, `GROUP BY`
- Parameterized queries (`?` placeholders) to prevent SQL injection
- Menu-driven console applications with full CRUD operations

---

## Notes

- Several programs use `input()`, so run them in a terminal and type the values when asked.
- Database programs use SQLite for convenience. To use MySQL instead, install `mysql-connector-python` and replace the `?` placeholders with `%s` (see the notes in `LabSheet08/README.md`).
- These programs are written for learning, and simple clarity is preferred over advanced optimisation.

---

## Author

**Shivani** (CU26280050)
MCA I Semester, Python Lab
