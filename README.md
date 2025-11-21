# Process Management – Lab 5 Assignment

This repository contains a set of C programs demonstrating basic operating system concepts such as process creation, background jobs, signal handling, linking, and loading. The project also includes documentation, a Makefile, and a license file.

---

## Requirements

Before compiling or running the code, ensure your system has:

- Linux environment (Ubuntu, Debian, etc.)
- GCC compiler  
  Install with:  
  sudo apt install gcc

- ldd tool (usually installed by default on Linux)

---

## Project Structure

process_creation.c    → Demonstrates fork()  
file1.c               → Used in the linker example  
file2.c               → Used in the linker example  
simple_program.c      → Used to inspect loader behavior  
Makefile              → Builds all programs  
answers.txt           → Written answers and explanations  
LICENSE               → MIT License  
README.md             → Project documentation

---

## How to Compile

To compile all programs at once:
make

To compile specific programs:
make process_creation  
make linker_example  
make simple_program

To clean the project (remove compiled files):
make clean

---

## How to Run

Process creation program:
./process_creation

Linker example:
./linker_example

Loader example:
./simple_program

To inspect dynamic libraries:
ldd simple_program

---

## Makefile Usage Summary

- make → Build everything  
- make clean → Remove compiled executables  
- make process_creation → Build only the fork example  
- make linker_example → Build linking example  
- make simple_program → Build loader example  

---

## License

This project is released under the MIT License.  
See the LICENSE file for full details.

---

## Contributing

Contributions and suggestions are welcome.  
If you would like to improve something, feel free to open an issue or submit a pull request.

---

## Contact

For questions or clarifications, you may reach the project maintainer through GitHub.
