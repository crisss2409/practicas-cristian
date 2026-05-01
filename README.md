# Pseudocode Translator

## Overview
The Pseudocode Translator is a tool that converts pseudocode into executable code in various programming languages. It is designed for students, educators, and professionals who need to translate pseudocode into practical code for better understanding and implementation.

## Features
- **Multi-language Support**: Converts pseudocode into languages such as Python, Java, C++, and more.
- **User-Friendly Interface**: Simple and intuitive UI that guides users through the translation process.
- **Syntax Highlighting**: Displays pseudocode with syntax highlighting for better readability.
- **Error Handling**: Provides feedback on incorrect or inconsistent pseudocode.

## Installation Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/crisss2409/practicas-cristian.git
   ```
2. **Navigate to the Directory**:
   ```bash
   cd practicas-cristian
   ```
3. **Install Dependencies**:
   Make sure you have Python installed, then run:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Application**:
   ```bash
   python main.py
   ```

## Examples
### Example 1: Simple If Statement
**Pseudocode**:
```
IF a > b THEN
    PRINT "a is greater than b"
ENDIF
```
**Translated Code (Python)**:
```python
if a > b:
    print("a is greater than b")
```

### Example 2: Looping
**Pseudocode**:
```
FOR i FROM 1 TO 5 DO
    PRINT i
ENDFOR
```
**Translated Code (Python)**:
```python
for i in range(1, 6):
    print(i)
```

## Usage
1. Input your pseudocode in the text area.
2. Select the desired output programming language.
3. Click the "Translate" button to generate the corresponding code.
4. Review the translated code in the output area.

## Contributions
Contributions are welcome! Please fork the repository and submit a pull request for any improvements, bug fixes, or features.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For support or inquiries, please reach out to [your-email@example.com].
