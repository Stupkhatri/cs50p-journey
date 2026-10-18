# cs50p-journey
# CS50P 20-Day Plan: From Zero to a CLI Tool

Free course: https://cs50.harvard.edu/python
Goal: finish core CS50P material, then build and publish one command-line tool on GitHub.

## Daily Routine (about 2 hours)

- Watch or skim lecture (30 to 40 min)
- Solve problem set item(s) (60 min)
- Commit to GitHub with a clear message (10 min)

## Repo Setup (Day 1)

- Create repo: `cs50p-journey`
- Folder layout:
  - `week-01-functions/`
  - `week-02-conditionals/`
  - ... one folder per topic
  - `final-project/` (the CLI tool)
- Add `NOTES.md` for daily learnings (one line per day is enough)

---

## Phase 1: Python Basics (Days 1 to 6)

### Day 1: Setup and Functions
- Install Python 3, pick an editor (VS Code or similar)
- Create GitHub account and repo, learn `git add`, `git commit`, `git push`
- Lecture topics: variables, `input`, `print`, functions, type conversion, f-strings
- Output: first commit

### Day 2: Practice Basics
- Solve Day 1 problem set items
- Write small programs: name greeter, unit converter, tip calculator
- Output: 3 scripts committed

### Day 3: Conditionals
- Lecture topics: `if`, `elif`, `else`, comparison operators, boolean logic
- Practice: write a number classifier (positive, negative, zero, even, odd)
- Output: committed script

### Day 4: Conditionals Practice
- Solve conditionals problem set
- Build: grade calculator (score to letter grade)
- Output: committed script

### Day 5: Loops
- Lecture topics: `while`, `for`, `range`, `break`, `continue`
- Practice: print patterns (triangle, grid)
- Output: committed script

### Day 6: Loops Practice
- Solve loops problem set
- Build: multiplication table generator
- Output: committed script, Phase 1 review in `NOTES.md`

---

## Phase 2: Structure and Reliability (Days 7 to 11)

### Day 7: Functions in Depth
- Lecture topics: `def`, parameters, `return`, scope, `main()` pattern
- Practice: refactor Days 3 to 6 scripts into functions
- Output: refactored scripts

### Day 8: Unit Tests
- Lecture topics: `pytest`, test functions, `assert`
- Practice: write tests for your Day 7 functions
- Output: `test_*.py` files committed

### Day 9: Exceptions
- Lecture topics: `try`, `except`, `ValueError`, input validation loops
- Practice: make grade calculator and number tools crash-proof
- Output: committed scripts

### Day 10: Libraries and Command-Line Arguments
- Lecture topics: `sys.argv`, `random`, `statistics`, installing packages with `pip`
- Practice: script that takes a filename or numbers from the command line
- Output: committed script

### Day 11: Phase 2 Review
- Re-run all tests
- Fix any failing or messy code
- Output: all tests passing, notes updated

---

## Phase 3: Files and Text Processing (Days 12 to 15)

### Day 12: File I/O
- Lecture topics: `open()`, `with`, read and write modes, `csv` module
- Practice: read a CSV and print a summary
- Output: committed script

### Day 13: File I/O Practice
- Solve file I/O problem set
- Build: script that counts lines, words, characters in a file (like `wc`)
- Output: committed script with a test

### Day 14: Regular Expressions
- Lecture topics: `re.search`, `re.sub`, `re.findall`, common patterns
- Practice: validate emails, phone numbers, and URLs
- Output: committed script with a test

### Day 15: Object-Oriented Programming
- Lecture topics: classes, `__init__`, methods, `__str__`
- Practice: build a `Task` class and a `TaskList` class
- Output: committed script with a test

---

## Phase 4: Build the CLI Tool (Days 16 to 20)

### Day 16: Plan the Tool
- Pick ONE idea from the list below
- Write the plan in `final-project/README.md`:
  - Purpose (2 sentences)
  - Commands (for example: `add`, `list`, `done`, `delete`)
  - Data storage (CSV or JSON file)
  - Folder structure
- Output: planning README committed

### Day 17: Core Logic
- Build data model (classes from Day 15)
- Build read and write to storage file
- Write at least 3 unit tests
- Output: core logic committed

### Day 18: Command-Line Interface
- Add command parsing with `sys.argv` or `argparse`
- Implement all commands from your plan
- Handle bad input with `try` and `except`
- Output: working CLI committed

### Day 19: Tests and Polish
- Add tests for every command
- Run `pytest`, fix failures
- Add `requirements.txt` if you use any packages
- Add `--help` output
- Output: tests passing

### Day 20: Publish
- Finish `final-project/README.md`:
  - Install steps
  - Usage examples (copy-paste commands with sample output)
  - Project structure
- Add a `.gitignore` (ignore `__pycache__/`, `.pytest_cache/`, data files)
- Tag a release `v1.0.0` on GitHub
- Optional: record a short terminal demo GIF and add it to the README
- Output: public repo with a finished CLI tool

---

## CLI Tool Ideas (pick one)

- Personal task manager (add, list, mark done)
- Expense tracker (add expense, monthly summary from CSV)
- Flashcard quiz (load cards from file, quiz, save score)
- Password strength checker (uses regex and tests)
- Habit tracker (log daily habits, show streaks)
- Markdown/transcript cleaner (CLI that formats text files)

## Done Checklist

- [ ] Repo public on GitHub
- [ ] Folders organized by week
- [ ] At least 1 test file per phase
- [ ] CLI runs with `python project.py --help`
- [ ] README explains install and usage
- [ ] Release tagged `v1.0.0`

## Rules

- Commit every day, even small progress
- If stuck more than 30 minutes, check the course's hints or search the error message
- Do not skip the final project; a working small tool beats an unfinished big one
