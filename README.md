A utility script that generates a combined text file representation of a script folder. It collects the main script and optional module files and outputs them into a single `.txt` file for inspection, sharing, or documentation.   

_Note: This is a personal tool created for myself (free to use)_  

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


~/Documents/Scripts/_name_/  
├── _name_ 
└── modules/  
├── module1  
└── module2  


---

# Usage

./scrappend _myscript_

Or interactively:  

./scrappend  

Output
~/Desktop/_script_name_.txt  

Notes  
Overwrites existing output file   
Requires readable script directory  

---

