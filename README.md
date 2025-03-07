TicTac - Tic-Tac-Toe Game

Overview

TicTac is a simple web-based Tic-Tac-Toe game built using ASP.NET Core MVC. The game supports both 3x3 and 6x6 board sizes and includes a PvP (Player vs. Player) mode and an AI opponent.

Features

3x3 and 6x6 Tic-Tac-Toe modes

Player vs. Player (PvP) and AI mode

Scoreboard to track player wins

Winning cells highlight effect

Simple and interactive UI

Installation & Setup

Prerequisites

.NET SDK installed (version 6.0 or later recommended)

Visual Studio Code or Visual Studio 2022

Git (if cloning the repository)

Steps to Run

Clone the Repository (if downloaded from GitHub):

git clone https://github.com/LouieGaborno/TicTac.git
cd TicTac

Open the Project in Visual Studio Code

code .

Or open the .sln file in Visual Studio.

Restore Dependencies

dotnet restore

Run the Project

dotnet run

Open a web browser and go to:

http://localhost:5000

Or, if running with HTTPS:

https://localhost:5001

Project Structure

TicTac/
├── Controllers/
│   ├── HomeController.cs
├── Models/
│   ├── ErrorViewModel.cs
├── Views/
│   ├── Home/
│   │   ├── Index.cshtml (Main Tic-Tac-Toe UI)
│   ├── Shared/
│   │   ├── _Layout.cshtml (Main Layout)
├── wwwroot/
│   ├── css/
│   │   ├── style.css (Game styles)
│   ├── js/
│   │   ├── game.js (Game logic)
├── Program.cs
├── README.md
├── TicTac.csproj
├── appsettings.json

How to Play

Open the game in a web browser.

Choose between 3x3 or 6x6 mode.

Click on a tile to make a move.

You can switch between PvP mode and AI mode.

The game announces the winner and highlights winning cells.

Restart the game anytime using the Restart button.
