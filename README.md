# *Simple File Explorer in C++ (Linux / WSL)*

*Student Name:* Ananya Dash

*Registration Number:* 2241004141

This project is a *command-line-based File Explorer* implemented in *C++* using the <filesystem> library.  
It allows users to manage files and directories through simple terminal commands such as listing, creating, deleting, copying, moving, searching, and changing file permissions.

---

## *Features*

| *Command* | *Description* | *Example* |
|--------------|------------------|--------------|
| **ls** | *List files and folders* | **ls** |
| **ls -l** | *Long list with permissions, size, timestamps* | **ls -l** |
| **cd <dir>** | *Change current directory* | **cd folder** |
| **create <file>** | *Create a file* | **create hello.txt** |
| **delete <file/dir>** | *Delete file or directory* | **delete hello.txt** |
| **copy <src> <dest>** | *Copy file/folder* | **copy a.txt b.txt** |
| **move <src> <dest>** | *Move or rename file/folder* | **move a.txt folder/** |
| **search <filename>** | *Search recursively by filename* | **search hello.txt** |
| **chmod <file> <octal>** | *Change permissions* | **chmod hello.txt 644** |
| **exit** | *Quit the program* | **exit** |

---

## *How to Compile & Run (WSL / Ubuntu)*

### *Step 1 — Install Build Tools*
bash
sudo apt update
sudo apt install -y g++ build-essential


### *Step 2 — Compile*
bash
g++ -std=gnu++17 main.cpp -o filex


Step 3 — Run
bash
./filex
