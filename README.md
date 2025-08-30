🔒 File Integrity Checker

A beginner-friendly tool to verify file integrity using cryptographic hashing algorithms (MD5, SHA-256).  
It helps detect file tampering or corruption by comparing stored and current hash values.


 ✨ Features
- Generate file hashes using **MD5** and **SHA-256**
- Compare current file hash with an expected/stored hash
- Detect if a file is **tampered**, **corrupted**, or unchanged
- OOP design with **Encapsulation, Inheritance, Abstraction, and Polymorphism**


 🎯 Target Users
- **System Administrators** – verify critical files  
- **Developers** – check software builds and downloads  
- **Security Teams** – detect unauthorized modifications  
- **End Users** – verify downloaded files against published checksums  


🧩 OOP Concepts Used
- **Encapsulation** → File path is private inside FileHandler
- **Inheritance** → MD5Checker and SHA256Checker inherit from IntegrityChecker
- **Abstraction** → IntegrityChecker defines an abstract interface
- **Polymorphism** → Different algorithms override generate_hash() differently


🗂️ Project Structure
file-integrity-checker

├── src/

│ └── integrity_checker.java

├── docs/

│ └── file_integrity_checker_uml.png

├── tests/

│ └── test_placeholder.java

└── README.md
