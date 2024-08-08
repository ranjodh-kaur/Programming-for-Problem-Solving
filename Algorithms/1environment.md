# Lab 1: Problem solving using computers:
1. Familiarisation with programming environment.

   
Getting familiar with a programming environment for C++ involves setting up your tools and understanding the workflow for writing, compiling, and debugging C++ code. Here's a step-by-step guide:

### 1. **Choose Your Tools**

#### **IDE or Text Editor**

- **IDEs**: Integrated Development Environments provide a comprehensive suite of tools. Popular C++ IDEs include:
  - **Visual Studio** (Windows): Rich features and strong support for C++.
  - **CLion**: Cross-platform and provides advanced C++ support.
  - **Code::Blocks**: Lightweight and customizable.
  - **Eclipse CDT**: Open-source and cross-platform.

- **Text Editors**: Lightweight alternatives include:
  - **Visual Studio Code**: Highly customizable with extensions for C++.
  - **Sublime Text**: Fast and customizable.
  - **Atom**: Flexible and open-source.

#### **Compiler**

- **Windows**: 
  - **MinGW**: A port of GCC for Windows.
  - **Microsoft Visual C++ Compiler**: Comes with Visual Studio.
- **MacOS**: 
  - **Xcode**: Includes the Clang compiler.
- **Linux**: 
  - **GCC**: The GNU Compiler Collection, commonly pre-installed on Linux systems.

### 2. **Install and Set Up**

1. **Install the IDE or Text Editor**:
   - Download and install your chosen IDE or text editor from its official website.

2. **Install a Compiler**:
   - **Visual Studio**: Includes the compiler; just select the C++ workload during installation.
   - **MinGW**: Download from the MinGW website and follow the installation instructions.
   - **GCC/Clang**: Typically available through package managers like `apt` on Ubuntu or `brew` on Mac.

3. **Configure Your Environment**:
   - **IDEs**: Usually handle configuration automatically but may need paths to the compiler or other tools.
   - **Text Editors**: You may need to configure build tasks and debugging settings. For example, in Visual Studio Code, you can create a `tasks.json` file for building and a `launch.json` file for debugging.

### 3. **Understand the Basic Components**

- **Editor Window**: Where you write your C++ code files (e.g., `.cpp`, `.h`).
- **Build System**: Compiles your code into executables. In IDEs, this is often a button or menu item; in text editors, you might use terminal commands.
- **Debugger**: Allows you to set breakpoints, step through code, and inspect variables.
- **File Explorer**: Helps manage project files and directories.

### 4. **Write and Compile Your First Program**

1. **Create a New Project or File**:
   - **IDE**: Use the project wizard to create a new C++ project.
   - **Text Editor**: Create a new file with a `.cpp` extension.

2. **Write a Simple Program**:
   ```cpp
   #include <iostream>

   int main() {
       std::cout << "Hello, world!" << std::endl;
       return 0;
   }
   ```
   or
   ```cpp
   #include <iostream>
   using namespace std;
   int main() {
       cout << "Hello, world!" << endl;
       return 0;
   }
   ```
   
   ```
   Line 1: #include <iostream> is a header file library that lets us work with input and output objects,
           such as cout (used in line 5). Header files add functionality to C++ programs.
   Line 2: using namespace std means that we can use names for objects and variables from the standard library.
           Don't worry if you don't understand how #include <iostream> and using namespace std works.
           Just think of it as something that (almost) always appears in your program.
   Line 3: A blank line. C++ ignores white space. But we use it to make the code more readable.
   Line 4: Another thing that always appear in a C++ program is int main(). This is called a function.
           Any code inside its curly brackets {} will be executed.
   Line 5: cout (pronounced "see-out") is an object used together with the insertion operator (<<) to output/print text. In our example, it will output "Hello World!".
   Note: Every C++ statement ends with a semicolon ;.
   Note: The body of int main() could also been written as:
   int main () { cout << "Hello World! "; return 0; }
           Remember: The compiler ignores white spaces. However, multiple lines makes the code more readable.
   Line 6: return 0; ends the main function.
   Line 7: Do not forget to add the closing curly bracket } to actually end the main function.


4. **Compile the Program**:
   - **IDE**: Look for a "Build" or "Compile" option.
   - **Text Editor with Terminal**:
     - **Windows (MinGW)**:
       ```bash
       g++ hello.cpp
       ```
     - **Mac/Linux (GCC/Clang)**:
       ```bash
       g++ hello.cpp
       ```
     - Run the compiled program:
       ```bash
       ./a.out
       ```
  ### 5. **Learn Basic Commands and Workflow**

- **Compiling Code**:
  ```bash
  g++ sourcefile.cpp
  ```
- **Running Programs**:
  ```bash
  ./outputfile
  ```
- **Debugging**: Set breakpoints and step through code to diagnose issues.
