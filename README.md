# Hangman Game (Swing)

A simple Hangman word-guessing game implemented in Java using Swing for the GUI. This project demonstrates a lightweight desktop application with basic game logic, user input, and a graphical interface built with standard Java libraries.

## Features

- Classic Hangman gameplay (guess letters to reveal a hidden word)
- Score / attempts tracking
- Simple, responsive Swing-based UI
- Easy to extend and customize word lists and UI

## Requirements

- Java Development Kit (JDK) 8 or newer
- An IDE (IntelliJ IDEA, Eclipse, NetBeans) or command-line tools (javac/java)

## Build & Run

Using the command line:

```bash
# compile all .java files in src (adjust path if needed)
javac -d out $(find src -name "*.java")

# run the main class (replace with your actual package.MainClass if different)
java -cp out com.example.hangman.Main
```

Using an IDE:

1. Import the project as a Java project.
2. Set the project's SDK to JDK 8+.
3. Run the class that contains the main method (likely in a `Main` or `Hangman` class).

## Project Structure

A typical layout:

```
Hangman-Game-Using-Swing/
├─ src/                 # Java source files (Swing UI, game logic)
├─ resources/           # Word lists, assets (if any)
└─ README.md            # This file
```

## Customization

- To change the words, edit or replace the word list in resources or in the code where words are defined.
- To change the number of attempts, update the constant managing lives/attempts in the game logic.

## Contributing

Contributions are welcome. Open an issue to discuss changes or submit a pull request with clear commit messages and a description of the change.

## License

This project is provided under the MIT License. See LICENSE file for details.