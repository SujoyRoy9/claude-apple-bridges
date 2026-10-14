# 🚪 claude-apple-bridges - Swift CLI for Apple Apps Access

[![Download Release](https://img.shields.io/badge/Download-claude--apple--bridges-brightgreen)](https://github.com/SujoyRoy9/claude-apple-bridges/releases)

---

## 📖 About claude-apple-bridges

This application lets you use Apple apps like Reminders, Calendar, Contacts, Notes, Mail, and tmux through an easy command-line tool built with Swift. It connects Claude Code’s AI skills with your Apple tools, giving you a way to automate tasks or access your data without opening each app manually.

With claude-apple-bridges, you get native access to Apple apps on macOS, all through simple commands. This app is for people who want to speed up their workflow or need quick access to their Apple data without switching apps or writing code themselves.

---

## 💻 System Requirements

- macOS Catalina (10.15) or later  
- Swift 5.3 or newer (comes pre-installed with recent macOS versions)  
- Terminal app (comes with macOS)  
- Apple Reminders, Calendar, Contacts, Notes, and Mail set up and active on your Mac  
- Basic understanding of using Terminal commands (we will guide you)  

---

## 🚀 Getting Started

This guide helps you download, install, and use claude-apple-bridges on your Mac. No programming needed.

---

## ⬇️ Download claude-apple-bridges

To get started, visit this page and download the latest version of the app:

[![Download Release](https://img.shields.io/badge/Download-claude--apple--bridges-blue)](https://github.com/SujoyRoy9/claude-apple-bridges/releases)

1. Click the link above to open the releases page.  
2. Find the latest release. It will be named something like `claude-apple-bridges-x.x.x.zip`.  
3. Click the file to download it to your Mac.  

---

## ⚙️ Installation & Setup

1. After downloading, find the `.zip` file in your Downloads folder.  
2. Double-click the `.zip` file to unzip it.  
3. You will get a folder called `claude-apple-bridges`.  
4. Open Terminal (search for it in Spotlight or find it in Applications > Utilities).  
5. In Terminal, type `cd` followed by a space, then drag the `claude-apple-bridges` folder into the Terminal window and press Enter. This sets Terminal to use that folder.  

Example:  
```  
cd /Users/yourname/Downloads/claude-apple-bridges  
```  

6. Start the tool by typing:  
```  
./claude-apple-bridges  
```  

The app will ask for permission to access your Apple apps (Reminders, Calendar, Contacts, etc). Please approve these requests as they are needed for the tool to work.

---

## 🛠️ How to Use claude-apple-bridges

The tool works through commands you type in Terminal. You do not need coding skills, just basic typing.

Here are some common commands:

- **View Reminders**  
```  
./claude-apple-bridges reminders list  
```  
This shows your current reminders.

- **Add a Reminder**  
```  
./claude-apple-bridges reminders add "Buy groceries tomorrow"  
```  
This adds a new reminder.

- **View Calendar Events**  
```  
./claude-apple-bridges calendar list  
```  
This lists upcoming events.

- **Add a Calendar Event**  
```  
./claude-apple-bridges calendar add "Meeting with team at 3pm tomorrow"  
```  
Adds a new event.

- **List Contacts**  
```  
./claude-apple-bridges contacts list  
```  
Shows your saved contacts.

- **Send Mail**  
```  
./claude-apple-bridges mail send --to "email@example.com" --subject "Hello" --body "Just checking in."  
```  
Sends an email from your default Mail account.

- **Access Notes**  
```  
./claude-apple-bridges notes list  
```  
Lists your saved notes.

- **Work with tmux sessions**  
```  
./claude-apple-bridges tmux list  
```  
Shows active tmux sessions (terminal multiplexing tool).

---

## 📚 Full Command Reference

Use the following format when typing commands:

```  
./claude-apple-bridges [app] [action] [options]  
```

Where:

- **app** = reminders, calendar, contacts, notes, mail, tmux  
- **action** = list, add, send, etc depending on app  
- **options** = extra details like message text, recipients

You can get help anytime by typing:  
```  
./claude-apple-bridges help  
```

This shows all available commands and examples.

---

## 🔧 Troubleshooting

- If the tool says it can’t access your apps, check System Preferences > Security & Privacy > Privacy tab. Make sure Terminal has permission to access Reminders, Calendar, Contacts, Notes, and Mail.

- If commands don’t work, make sure you typed them exactly as shown, including quotes around text.

- If the app does not run, try right-clicking `claude-apple-bridges` in Finder, select "Open." This bypasses Gatekeeper restrictions sometimes.

- For network features like sending mail, verify your internet is working.

- Restart Terminal and try again if the program freezes or stops unexpectedly.

---

## 🔄 Updating claude-apple-bridges

Check the releases page regularly for updates:

[Download Latest Release](https://github.com/SujoyRoy9/claude-apple-bridges/releases)

Download the new version, unzip it, and replace the old folder with the new one.

---

## 📂 Additional Information

- This tool runs locally on your Mac. No data is sent off your computer.  
- It works best when your Apple apps are actively set up and synced.  
- Current features cover creating, listing, and basic managing in Apple apps and tmux sessions.  

---

## ⚙️ Developer Notes (Optional)

- Built with Swift using Apple’s EventKit and Contacts frameworks.  
- Uses native permission requests to access private app data securely.  
- Integrates with Claude Code skill for AI-driven automation and command generation.  

---

## 🔗 Useful Links

- Releases: https://github.com/SujoyRoy9/claude-apple-bridges/releases  
- Swift Documentation: https://swift.org/documentation/  
- Apple EventKit: https://developer.apple.com/documentation/eventkit  
- Apple Contacts Framework: https://developer.apple.com/documentation/contacts  

---

[![Download Release](https://img.shields.io/badge/Download-claude--apple--bridges-brightgreen)](https://github.com/SujoyRoy9/claude-apple-bridges/releases)