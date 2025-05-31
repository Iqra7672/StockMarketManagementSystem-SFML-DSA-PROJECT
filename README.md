# StockMarketManagementSystem-SFML-DSA-PROJECT
Stock Market Management System using C++, SFML for GUI, and Data Structures &amp; Algorithms for core logic.

## 🧭 Features:

- User registration and login system  
- Case-insensitive stock name search  
- Binary Search Tree (BST) for efficient stock storage and lookup  
- View list of available stocks with prices  
- Buy stocks and add them to user’s portfolio  
- SFML-based GUI with input handling and feedback  
- Simple and intuitive interface

---

## ⚙️ SFML Setup (Windows & Visual Studio)

1. Download SFML 2.5.1 from [https://www.sfml-dev.org/download/sfml/2.5.1/](https://www.sfml-dev.org/download/sfml/2.5.1/)  
2. Extract SFML to a folder, e.g. `C:\SFML`  
3. Configure Visual Studio project:  
   - Right-click your project → Properties  
   - Under **C/C++ → General → Additional Include Directories**, add:  
     `C:\SFML\include`  
   - Under **Linker → General → Additional Library Directories**, add:  
     `C:\SFML\lib`  
   - Under **Linker → Input → Additional Dependencies**, add:  
     ```
     sfml-graphics-d.lib  
     sfml-window-d.lib  
     sfml-system-d.lib
     ```  
     *(Use the non `-d` versions for Release mode)*  
4. Copy the DLL files:  
   - Copy `sfml-graphics-2.dll`, `sfml-window-2.dll`, `sfml-system-2.dll` from `C:\SFML\bin`  
   - Paste them into your project's Debug or Release folder  

---

## ▶️ How to Run

- Build and run the project in Visual Studio  
- Use the GUI window to interact:  
  - Register or log in  
  - View available stocks and their prices  
  - Buy stocks by entering the stock name (case-insensitive)  
  - Exit or switch between menu options  
- Stocks bought are added to the user’s portfolio (stored in memory during runtime)

---

##  📂 Project Structure

- **main.cpp** – Main application file containing the SFML GUI and user interaction logic.
- **README.md** – Project description, setup instructions, and usage guide.
- **Roboto.ttf** – Roboto font file used for rendering text in the application.
