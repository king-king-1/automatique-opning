🚀 Automatic Opening – Windows Startup Manager
Automatic Opening is a lightweight GUI tool built with PyQt5 that lets you easily add or remove programs from Windows startup.
It keeps a local SQLite database of all entries you’ve added and provides a clean, modern interface to manage them.


✨ Features
Add to Startup – Select any executable (.exe) and add it to the Windows registry (HKCU\Software\Microsoft\Windows\CurrentVersion\Run).

Remove from Startup – Select an executable to remove its startup entry.

Registry List – View all programs you’ve added; click any item to delete it.

Expandable Toolbar – Collapse or expand the sidebar with a smooth animation.

Contact & Support – Quick links to Telegram, Instagram, GitHub, and email.

Help & Manual Removal – Built‑in guide for removing entries manually if the app fails.

GPLv3 License – Full license text included in the app.

📦 Requirements
Python 3.6 or higher

PyQt5

Windows operating system (uses winreg)

🛠 Installation & Running
Clone the repository

bash
git clone https://github.com/your-username/automatic-opening.git
cd automatic-opening
Install dependencies

bash
pip install PyQt5
Run the application

bash
python main.py
Note: The app uses images and icons from the images/ and icons/ folders.
Make sure they are in the same directory as main.py.

🖥 How to Use
1. Active (Add to Startup)
Click "slect a file" and choose an executable (.exe).

The file will be added to Windows startup and saved in the database.

2. Desactive (Remove from Startup)
Click "slect a file" and choose the program you want to remove.

The entry will be deleted from the registry and the database.

3. Registry (View / Delete)
Lists all programs you have added.

Click any button to delete that entry from both the registry and the database.

4. Contact us
Opens links to Telegram, Instagram, GitHub, or shows the Gmail address.

The "problem" button displays a step‑by‑step guide for manually removing a startup entry via regedit.

5. License
Displays the full GNU General Public License v3.0 text.

🔧 Building a Standalone .exe
You can package the application into a single executable using PyInstaller:

bash
pip install pyinstaller
pyinstaller --onefile --windowed --add-data "images;images" --add-data "icons;icons" main.py
Note: Adjust the --add-data syntax according to your platform (Windows uses ;).

📂 File Structure
text
automatic-opening/
├── main.py                 # Main application code
├── images/                 # Background images (e.g., contact page)
├── icons/                  # Toolbar icons (SVG/PNG)
├── data.dp                 # SQLite database (created automatically in %APPDATA%)
└── README.md
🤝 Contributing
Contributions are welcome!
Feel free to open an issue or submit a pull request.

📄 License
This project is licensed under the GNU General Public License v3.0.
See the LICENSE file for details.

📬 Contact
Telegram: @lalalleeab

Instagram: co__dili

GitHub: king-king-1

Email: chebarliissam@gmail.com

Enjoy effortless startup management! 🎉