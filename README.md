# Capture The Flag – Crack The Code

An interactive puzzle game that makes learning cryptography fun and hands-on through classic ciphers and engaging gameplay.


## About The Project

Crack the Code is a gamified learning tool designed to make cryptography accessible and enjoyable for beginners. Instead of passively reading about encryption techniques, players actively solve puzzles using two classic ciphers Caesar Cipher and Keyword Cipher while managing time pressure and limited lives.

The game transforms abstract cryptographic concepts into tangible challenges, helping players develop pattern recognition, logical thinking, and a deeper appreciation for data security.


## Objectives

- Improve problem-solving skills
- Learn to spot patterns
- Understand why encryption matters
- Make cryptography less intimidating for beginners
- Keep players curious and engaged while learning


## Key Features

- Two Classic Ciphers – Caesar Cipher and Keyword Cipher
- 16 Themed Categories – Animals, Cybersecurity, Space, Medicine, Brands, and more
- Timer System – Two minutes per puzzle; running out of time costs a life
- Lives System – Players start with three hearts, adding pressure and excitement
- Progress Tracking – Visual progress bar to capture the flag
- Instant Feedback – After each correct answer, the game shows the meaning of the word
- Leaderboard – Compare scores with other players
- Secure Authentication – Registration, login, and OTP password reset


## Game Categories

| Caesar Cipher | Keyword Cipher |
|---------------|----------------|
| Animals | Data Privacy |
| Cybersecurity | Famous People |
| Famous Brands | Medicine |
| Body Systems | Continents |
| Mobile Games | Fruits |
| Local Wonders | Vegetables |
| School Subjects | Earth Wonders |
| Travel Ways | Outer Space |


## Built With

- Frontend: HTML, CSS, JavaScript
- Backend: PHP
- Email Verification: PHPMailer (OTP for password reset)
- Design: Figma
- Server: XAMPP / Apache
- Database: MariaDB


## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- XAMPP ([Download here](https://www.apachefriends.org/))
- Visual Studio Code ([Download here](https://code.visualstudio.com/))
- Web browser


## Installation

Step 1: Install and run XAMPP
Start Apache and MySQL in the XAMPP Control Panel.

Step 2: Create the database
Go to localhost/phpmyadmin and create a new database named **crakthecodedb**.

Step 3: Import the SQL file
In phpMyAdmin, select the crakthecodedb database, click the Import tab, choose the SQL file from the database folder, and click Go.

Step 4: Configure email settings
Update the PHPMailer settings in the Mail folder with your email credentials.

Step 5: Move project files
Copy the project folder to C:\xampp\htdocs\

Step 6: Open in VSCode
Open Visual Studio Code, select File > Open Folder, and choose your project folder.


## Usage

### Access the Game

| Page | Local URL |
|------|-----------|
| **Homepage** | `http://localhost/CrackTheCode/Frontend/Homepage.php` |



### How to Play

1. Create an account and log in
2. Choose Caesar or Keyword Cipher
3. Pick a topic that interests you
4. Decrypt the word before the timer runs out
5. Learn the meaning of each correct answer
6. Complete all puzzles to capture the final flag
7. Check the leaderboard to compare scores


## Disclaimer

This project was developed as an academic requirement for Information Assurance and Security II at the College of Computer Studies, Pamantasan ng Lungsod ng Pasig. All content is for educational and demonstration purposes only.


## Acknowledgments

- Faculty of the College of Computer Studies for their guidance
- Pamantasan ng Lungsod ng Pasig for the opportunity


## Prepared By

**Leader:** Bernardo, Kanzaki Ning O.

**Members:**
- Cabaron, Renalyn L.
- Caneda, Elizor Daniel T.
- Capalaran, Zane Allyson V.
- Cerado, Roileen I.
- Chiu, Janica Annya O.

**August 2025**
