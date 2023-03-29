Nachos Operating System Project
This repository contains a modified version of the Nachos educational operating system, which has been enhanced with new features and system calls to showcase its capabilities.

Nachos is a simple operating system designed for educational purposes, created at the University of California, Berkeley. It is mainly used to teach operating system concepts, such as process management, memory management, file systems, and networking.

Prerequisites
To build and run the Nachos project, you need the following software installed on your system:

A C++ compiler (such as g++ or clang++)
GNU Make
A MIPS cross-compiler (such as mips-elf-gcc)
Cygwin or WSL (for Windows users)
Installation
Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/nachos.git
Navigate to the cloned repository:

bash
Copy code
cd nachos/code
Build the Nachos project:

go
Copy code
make
Usage
To run the Nachos project, use the following command:

bash
Copy code
./nachos <options>
Replace <options> with the appropriate command-line options for your specific task. Some common options include:

-x <program>: Executes the specified user program
-rs <seed>: Sets the random seed for process execution
-d <flags>: Enables the specified debug flags
For a complete list of command-line options, consult the Nachos documentation or the source code.

Implemented Features
The following features and system calls have been added to the Nachos project:

MySystemCall: A custom system call that demonstrates how to implement a new system call in Nachos.
Multithreading: Added support for multithreading and thread synchronization using semaphores.
Virtual Memory: Implemented a basic demand-paging system with page replacement policies.
Testing
This repository includes a set of test programs to verify the functionality of the implemented features. To run the test programs, follow these steps:

Navigate to the code/test directory:

bash
Copy code
cd test
Compile the test programs:

go
Copy code
make
Navigate back to the code directory:

bash
Copy code
cd ..
Run the test programs with Nachos:

bash
Copy code
./nachos -x <path_to_test_program>
Replace <path_to_test_program> with the path to the specific test program you want to run (e.g., ../test/halt).

Contributing
If you would like to contribute to this project, please submit a pull request with your proposed changes. All contributions are welcome, whether they are bug fixes, new features, or improvements to the documentation.

License
This project is licensed under the GNU General Public License v3.0.

Acknowledgments
The original Nachos project was developed at the University of California, Berkeley.
Thanks to all contributors who helped improve and expand this project.



