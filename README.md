MiniGit - CLI Version Control System

This is a simplified version of Git called MiniGit, built using C++. It allows basic version control functionalities through a command-line interface.

Features

- `init` – Initializes a new MiniGit repository
- `add <filename>` – Stages files for commit
- `commit -m "<message>"` – Saves changes to the repository
- `log` – Displays commit history
- `branch <name>` – Creates a new branch
- `checkout <branch>` – Switches to the specified branch
- `merge <branch>` – Merges another branch into the current branch
- `diff <commit1> <commit2>` – Compares differences between two commits
- `exit` – Exits the program

Data Structures Used

- `unordered_set` – To manage staged files
- `vector` – To hold commit file lists
- `unordered_map` – To simulate references
- `struct Commit` – To store commit information
- `std::string` – For handling paths and content

 How to Use

1. Clone the repository
2. Compile using any C++ compiler
3. Run the `main.cpp` and use the CLI to type commands like `init`, `add`, etc.

Limitations

- Only works on plain text files
- No real hash functions (uses a basic sum for demo purposes)
- No rollback or delete functionality

Future Improvements

- Use real SHA-1 hashes
- Add rollback/reset features
- Handle file renaming and deletion
- Improve conflict handling during merges


