A utility script that generates a combined text file representation of a script folder. It collects the main script and optional module files and outputs them into a single `.txt` file for inspection, sharing, or documentation.

---

# Features

- Accepts script name via argument or prompt
- Validates source directory
- Creates or clears output file on Desktop
- Appends module files first (if present)
- Appends main script content
- Simple and automated export workflow

---

# Expected Structure


~/Documents/Scripts/<script_name>/
├── <script_name>
└── modules/
├── module1
└── module2


---

# Usage

./script_to_text.sh myscript

Or interactively:

./script_to_text.sh

Output
~/Desktop/<script_name>.txt

Notes
Overwrites existing output file
Requires readable script directory

---

