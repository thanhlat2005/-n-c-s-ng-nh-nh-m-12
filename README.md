# 🚀 C++ Caro Console Game

<div align="center">

<!-- TODO: Add project logo/screenshot if available -->

[![GitHub stars](https://img.shields.io/github/stars/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12?style=for-the-badge)](https://github.com/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12/stargazers)

[![GitHub forks](https://img.shields.io/github/forks/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12?style=for-the-badge)](https://github.com/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12/network)

[![GitHub issues](https://img.shields.io/github/issues/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12?style=for-the-badge)](https://github.com/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12/issues)

[![GitHub license](https://img.shields.io/github/license/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12?style=for-the-badge)](LICENSE) <!-- TODO: Add LICENSE file -->

**A classic Caro (Gomoku) game implemented as a console application in C++.**

</div>

## 📖 Overview

This repository hosts a console-based Caro game, a variant of Five-in-a-Row (Gomoku). Developed in C++, this project provides a simple yet engaging two-player experience directly within the command line interface. It's an excellent example of fundamental game development principles, console graphics manipulation, and object-oriented programming in C++.

## ✨ Features

-   🎯 **Two-Player Gameplay:** Enjoy head-to-head matches against another player.
-   🎮 **Console-Based Interface:** Fully functional game rendered directly in the console window.
-    tablero **Dynamic Game Board:** A grid-based board where players place their marks ('X' or 'O').
-   ➡️ **Intuitive Navigation:** Use arrow keys to navigate the board and select a position.
-   ✅ **Win Condition Detection:** Automatically detects when a player achieves five consecutive marks horizontally, vertically, or diagonally.
-   🔄 **Game Reset:** Option to restart the game after a win or draw.
-   🚨 **Input Validation:** Ensures players can only make valid moves on empty cells.
-   💾 **Visual Studio Project:** Ready-to-build solution using Visual Studio.

## 🖥️ Screenshots

<!-- TODO: Add actual screenshots of the game running in the console -->

![Gameplay Screenshot](path-to-gameplay-screenshot.png)
_A placeholder for a screenshot of the Caro game in action._

## 🛠️ Tech Stack

**Core Technologies:**
-   ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
-   **Windows API**: Utilized for console manipulation, input handling, and basic "graphics."

**Development Environment:**
-   **Visual Studio**: The primary IDE and build system used for the project.

## 🚀 Quick Start

### Prerequisites
To build and run this project, you will need:
-   **Visual Studio** (2019 or later recommended) with C++ development workload installed.
-   **Windows Operating System** (as the project likely uses Windows-specific console APIs).

### Installation

1.  **Clone the repository**
    ```bash
    git clone https://github.com/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12.git
    cd DoAnCoSoNganhCNTT-Nhom12
    ```

2.  **Open in Visual Studio**
    Open the `NguyenThanhLat_GameCaro.vcxproj` file using Visual Studio.

3.  **Build the Project**
    In Visual Studio, go to `Build` > `Build Solution` (or press `Ctrl+Shift+B`). This will compile the source code and generate an executable.

4.  **Run the Game**
    After a successful build, you can run the game directly from Visual Studio by pressing `F5` (Start Debugging) or `Ctrl+F5` (Start Without Debugging). Alternatively, navigate to the project's `Debug` or `Release` folder (e.g., `x64\Debug\`) and run the `NguyenThanhLat_GameCaro.exe` executable.

## 📖 How to Play

1.  **Start the Game:** Run the executable.
2.  **Navigation:** Use the **Arrow Keys** (Up, Down, Left, Right) to move the cursor on the game board.
3.  **Place a Mark:** Press **Enter** or **Spacebar** to place your 'X' or 'O' mark at the cursor's current position.
4.  **Turns:** Players take turns placing their marks.
5.  **Winning:** The goal is to get five of your marks in a row, either horizontally, vertically, or diagonally.
6.  **Restart:** After a game ends (win or draw), follow the on-screen prompts to start a new game.

## 📁 Project Structure

```
DoAnCoSoNganhCNTT-Nhom12/
├── NguyenThanhLat_GameCaro.vcxproj          # Visual Studio project file
├── NguyenThanhLat_GameCaro.vcxproj.filters  # Visual Studio filter definitions for files
├── NguyenThanhLat_GameCaro.vcxproj.user     # Visual Studio user-specific settings
├── README.md                                # This README file
├── _Board.cpp                               # Implements the game board logic
├── _Board.h                                 # Header for the Board class/functions
├── _Common.cpp                              # Common utility functions (e.g., console I/O, cursor positioning)
├── _Common.h                                # Header for common utilities
├── _Game.cpp                                # Core game logic, state management, main game loop
├── _Game.h                                  # Header for the Game class/functions
├── _Play.cpp                                # Player interaction, move handling, win checking
├── _Play.h                                  # Header for Play-related functions/classes
├── _Point.cpp                               # Implements the Point structure/class (coordinates)
├── _Point.h                                 # Header for the Point structure/class
└── main.cpp                                 # The main entry point of the application
```

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the game, fix bugs, or add new features, please follow these steps:

1.  **Fork** the repository.
2.  **Create a new branch** for your feature or bug fix (`git checkout -b feature/your-feature-name`).
3.  **Make your changes** and commit them with clear messages.
4.  **Push your branch** to your forked repository.
5.  **Open a Pull Request** to the `main` branch of this repository.

### Development Setup for Contributors

Simply follow the "Quick Start" installation steps above to set up your development environment. All C++ source files are located at the root level.

## 📄 License

This project is currently unlicensed. Please refer to the repository owner for licensing information. <!-- TODO: Add an explicit LICENSE file (e.g., MIT, Apache 2.0) -->

## 🙏 Acknowledgments

-   Developed as a fundamental project (Do An Co So Nganh CNTT) by Group 12.

## 📞 Support & Contact

If you have any questions, encounter issues, or want to provide feedback:

-   🐛 **Issues:** Report bugs or suggest features via [GitHub Issues](https://github.com/thanhlat2005/DoAnCoSoNganhCNTT-Nhom12/issues).
-   📧 **Contact:** For direct inquiries, you can reach out to the repository owner, [thanhlat2005](https://github.com/thanhlat2005).

---

<div align="center">

**⭐ Star this repo if you find it helpful or interesting!**

Made with ❤️ by Lat Nguyen

</div>

