
🛡️ MazyVazy
A simple, secure, standalone password manager that lives in a single HTML file.

MazyVazy is designed to be the ultimate "offline" vault. It runs entirely in your browser, connects to no servers, and can be carried around on a USB stick. It’s like a digital safe you can keep in your pocket.

🌟 Why use this?

Zero Installation: No apps to install. Just open the file in Chrome, Edge, or Firefox.

100% Offline: Your passwords never leave your device. No cloud hacks, no leaks.

Portable: Put MazyVazy.html on a flash drive and use it on any computer.

Self-Contained: The database is inside the file. The code is the app, and the app is the database.

How to use it
1. Getting Started

Simply download MazyVazy.html and double-click it.

First time? Enter a strong Master Password. This will encrypt the file.

Returning? Enter your password to unlock your vault.

2. Saving Changes (Important!)

Because this is a secure browser file, it cannot "overwrite" itself on your hard drive automatically (browsers don't allow that for safety).

Add your passwords and click 💾 Save Changes.

The app will instantly download a new file (e.g., MazyVazy (1).html).

This new file is your current vault.

Delete the old file and rename the new one back to MazyVazy.html.

3. Backups

Since there is no cloud, you are the cloud.

Email the file to yourself.

Put a copy on a USB stick.

Save it to Google Drive/Dropbox if you want.
(Even if someone steals the file, they cannot open it without your Master Password).

🔒 Security Details

Encryption: Uses AES-256-GCM (Government-grade standard).

Key Derivation: Uses PBKDF2 (100,000 iterations) to stop hackers from guessing your password.

Anti-Forensics: When you close the tab, the data is wiped from the computer's memory. It leaves no trace on the machine.

⚠️ WARNING: There is no "Forgot Password" button. If you lose your Master Password, your data is gone forever. This is mathematically impossible to crack.

🛠️ Technical Info

Built with: HTML, CSS, and Vanilla JavaScript.

Dependencies: None. Zero.

Size: Extremely lightweight (< 10KB).

Credits


Designed and coded by Me?
Free to use, modify, and share.
