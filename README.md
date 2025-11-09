Universal Multi-Language Compiler (UMLC)
A cross-platform desktop compiler that supports multiple programming languages in a unified CustomTkinter interface.

🌟 Features
Multi-Language Support: Python, C, C++, Java, JavaScript
Modern GUI: Built with CustomTkinter for beautiful cross-platform interface
Syntax Highlighting: Real-time syntax highlighting for all supported languages
Code Execution: Run code directly from the GUI with real-time output
File Management: Open, save, and manage code files
Error Handling: Comprehensive error reporting and output display
Cross-Platform: Works on Windows, macOS, and Linux
🚀 Supported Languages
Language	Compilation	Execution	File Extensions
Python	Interpreted	Native	.py
C	GCC	Native executable	.c, .h
C++	G++	Native executable	.cpp, .cxx, .cc
Java	javac	Java Runtime	.java
JavaScript	Interpreted	Node.js	.js
📋 Prerequisites
Before running UMLC, ensure you have the following installed:

Python 3.7+
GCC (for C/C++ compilation)
G++ (for C++ compilation)
Java Development Kit (JDK) (for Java compilation and execution)
Node.js (for JavaScript execution)
Installing Dependencies
pip install -r requirements.txt
🛠 Installation
Clone or download the project:
git clone <repository-url>
cd UMLC
Install Python dependencies:
pip install -r requirements.txt
Run the application:
python src/main.py
🎯 Usage
Running the Application
python src/main.py
Basic Workflow
Select Language: Choose your programming language from the toolbar dropdown
Write Code: Type your code in the editor with syntax highlighting
Run Code: Click "Run (F5)" or press F5 to execute your code
View Output: See results in the output panel below the editor
Save/Load: Use File menu to save and open code files
Keyboard Shortcuts
Ctrl+N - New file
Ctrl+O - Open file
Ctrl+S - Save file
Ctrl+Shift+S - Save as
F5 - Run code
F6 - Compile only (for compiled languages)
📁 Project Structure
UMLC/
├── src/                    # Source code
│   ├── main.py            # Main application entry point
│   ├── __init__.py        # Package initialization
│   ├── backend/           # Backend logic
│   │   ├── __init__.py
│   │   └── compiler_manager.py  # Compilation and execution logic
│   └── gui/               # GUI components
│       ├── __init__.py
│       ├── code_editor.py     # Code editor with syntax highlighting
│       ├── output_display.py  # Output display widget
│       └── toolbar.py         # Toolbar component
├── examples/              # Example code files
│   ├── hello_python.py
│   ├── hello_c.c
│   ├── hello_cpp.cpp
│   ├── hello_java.java
│   └── hello_javascript.js
├── tests/                 # Test files (if any)
├── requirements.txt       # Python dependencies
└── README.md             # This file
🔧 Configuration
The application automatically detects available compilers and interpreters. If any are missing, warnings will be displayed, but the application will still function for available languages.

Custom Compiler Paths
To use custom compiler paths, modify the CompilerManager class in src/backend/compiler_manager.py.

🐛 Troubleshooting
Common Issues
"Command not found" errors: Ensure all required compilers/interpreters are installed and in your PATH
Permission denied: Make sure you have execution permissions for compiled programs
Import errors: Ensure all Python dependencies are installed correctly
Dependency Check
The application includes a dependency checker that runs on startup. Check the console output for any missing dependencies.

🤝 Contributing
Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

Development Setup
Fork the repository
Create a feature branch: git checkout -b feature/amazing-feature
Commit your changes: git commit -m 'Add some amazing feature'
Push to the branch: git push origin feature/amazing-feature
Open a Pull Request
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Built with CustomTkinter
Syntax highlighting powered by Pygments
Icons and UI inspiration from various open-source projects
📞 Support
If you encounter any issues or have questions:

Check the troubleshooting section above
Search existing issues on GitHub
Create a new issue with detailed information
🗺 Roadmap
 Add more programming languages (Go, Rust, etc.)
 Implement debugging features
 Add project/workspace management
 Integrate with version control systems
 Add code formatting and linting
 Implement plugin system for extensibility
Happy Coding with UMLC! 🚀
