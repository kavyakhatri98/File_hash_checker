# Hash_checker
File Hash Checker 

A beginner-friendly cybersecurity project built with Python that calculates SHA-256 hashes and checks file integrity.

Features

- Calculates SHA-256 file hashes
- Supports text files, PDFs, images, and other file types
- Reads files in chunks for memory efficiency
- Compares calculated hashes with a supplied reference hash
- Handles missing files and common file-access errors

Requirements

- Python 3
- No external libraries required

Folder Structure

Keep "hash_checker.py" and the file you want to hash in the same folder for easy access.

Example:

File-Hash-Checker/
├── hash_checker.py
├── sample.txt
└── README.md

How to Run

1. Open the "File-Hash-Checker" folder in VS Code.

2. Create or place the file you want to hash inside that same folder.

3. Open the terminal in VS Code.

4. Run the command:
   
   "python hash_checker.py"

5. When prompted for the file path, enter only the filename, for example:
   
   "sample.txt"(You can also add a .jpg file)
   
   You do not need to type the full file path, such as "C:\Users\YourName\Desktop\File-Hash-Checker\sample.txt", as long as the terminal is running in the project folder.

6. The program will display the file's SHA-256 hash.

7. Optionally, enter a trusted reference hash to compare it with the calculated hash.

Example Use Cases

- Verifying backup integrity
- Learning digital forensics fundamentals
- Understanding cryptographic hashing

Security Note

A matching hash indicates that the file matches the supplied reference hash. Only compare against a trusted reference. A hash alone does not establish that a file is safe.

Technologies

- Python
- hashlib
- pathlib
