# Morse Code Converter

A simple Java-based application that converts text into Morse code and plays the corresponding beeps. Built using JavaFX, this tool provides both a visual and audio representation of Morse code.

## 🚀 Features
- Convert any text into Morse code.
- Display the Morse code instantly.
- Play Morse code as beeps.
- User-friendly GUI with JavaFX.

## 🛠️ Installation & Setup
### Prerequisites
- Java (JDK 11 or later)
- JavaFX installed (or use OpenJFX if on Linux)
- IntelliJ IDEA (or any Java-compatible IDE)

### Steps to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/morse-code-converter.git
   cd morse-code-converter
   ```
2. Open the project in IntelliJ IDEA.
3. Add JavaFX libraries:
   - Go to **File** → **Project Structure** → **Libraries**.
   - Click **+ (Add)** → **Java**.
   - Navigate to your JavaFX installation folder and add all `.jar` files inside `lib/`.
4. Configure Run Options:
   - Open **Run** → **Edit Configurations**.
   - Add the following **VM Options**:
     ```
     --module-path /path/to/javafx/lib --add-modules javafx.controls,javafx.fxml
     ```
   - Replace `/path/to/javafx/lib` with your actual JavaFX installation path.
5. Click **Run** and enjoy! 🚀

## 📷 Screenshot
![Morse Code Converter GUI](screenshot.png)

## 📝 Usage
1. Enter text in the input field.
2. Click **Convert** to see the Morse code.
3. The Morse code will be displayed immediately.
4. The corresponding beep sound will play automatically.

## 🤝 Contributing
Contributions are welcome! If you find bugs or have suggestions, feel free to open an issue or submit a pull request.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📬 Contact
- **Author:** Kunal Sharma  
- **GitHub:** [your-username](https://github.com/your-username)  
- **Email:** kunalsharma.dev01@gmail.com
