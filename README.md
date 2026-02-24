ProChess Manager v4.5 - Professional Edition
ProChess Manager is a comprehensive, standalone web application designed for chess tournament organizers, club managers, and trainers. It streamlines the management of players, tournaments, matches, and financial records within a single, intuitive interface.

🚀 Key Features
Player Database: Track names, levels (Grandmaster to Beginner), and performance.

Tournament Scheduling: Organize multiple tournaments with status tracking (Planned, Ongoing, Completed).

Match Management: Log individual matches, results, and duration.

Financial Tracking: Monitor income and expenses with an automated balance summary.

Data Persistence: Integrated with Browser Local Storage—your data stays on your device even after a refresh.

Import/Export: Export your entire database to a JSON file for backups or moving to another device.

Responsive UI: A clean, RTL-supported (Right-to-Left) design optimized for professional use.

📋 Prerequisites
As a Single File Application (SFA), the requirements are minimal:

Any modern web browser (Google Chrome, Firefox, Microsoft Edge, Safari).

No installation, no database servers, and no internet connection required to run.

💻 How to Use (Detailed Guide)
1. Getting Started
Simply open the Chess manager.html file in your browser. You will see a clean dashboard divided into functional sections.

2. Managing Players
Scroll to the "إدارة اللاعبين" (Player Management) section.

Enter the player's name and select their skill level.

Click "إضافة لاعب" (Add Player).

The list below will update instantly, allowing you to delete players if needed.

3. Organizing Tournaments
In the "إدارة البطولات" (Tournament Management) section, enter the tournament name, date, and current status.

Click "إضافة بطولة" (Add Tournament).

Use this to keep a history of upcoming and past events.

4. Logging Matches
Select a tournament from the dropdown.

Pick Player 1 and Player 2 from your registered player list.

Set the result (e.g., White Win, Black Win, or Draw).

Click "تسجيل المباراة" (Register Match). Matches are listed at the bottom for review.

5. Financial Management
Use the "السجل المالي" (Financial Ledger) to track club finances.

Choose "Income" (إيراد) for entry fees or "Expense" (مصروف) for prizes/rent.

Enter the amount and a description.

The "ملخص الرصيد" (Balance Summary) at the top of the section updates automatically to show your net profit/loss.

6. Data Safety (Export & Import)
To Backup: Click "تصدير البيانات (JSON)" to download a file containing all your club data.

To Restore: Click "اختيار ملف" under the Import section, select your previously saved JSON file, and confirm.

Warning: Importing will overwrite the current data in your browser.

📂 Project Structure
Plaintext
├── Chess manager.html   # The entire application (HTML, CSS, Logic)
└── README.md            # Documentation
💾 Technical Details (Data Storage)
Mechanism: This app utilizes the localStorage API.

Storage Key: Data is stored under the key chess_v45_final.

Note: If you clear your browser's "Site Data" or "Cache," the stored data will be deleted. Always keep a JSON Export as a backup.

🤝 Contributing
Fork the project.

Create your Feature Branch (git checkout -b feature/AmazingFeature).

Commit your changes.

Push to the branch.

Open a Pull Request.
