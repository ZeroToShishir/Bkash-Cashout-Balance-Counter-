💸 Cashout Counter
A modern, app-like Progressive Web App (PWA) designed to calculate the maximum bKash cashout amount after deducting service charges.
Built with a clean UI, smooth UX, and real-world usability in mind.

🚀 What Problem It Solves
When trying to cash out your full bKash balance, you don’t know:
“How much can I actually withdraw after charges?”
This app calculates that instantly and accurately.

✨ Key Features
💰 Core Functionality
Calculate maximum withdrawable amount
Supports:
14.90 Tk / 1000 (Priyo)
18.50 Tk / 1000 (Regular)
Custom/manual rate input
Accurate proportional charge calculation

🎨 UI / UX
Modern bKash-inspired design
Large, touch-friendly interface
Selected rate highlight system
Smooth animations & transitions
Result breakdown (cashout + charge)

🌙 Smart Experience
Dark / Light mode toggle
Auto theme switching UI feedback
Clean typography and spacing

📱 App-like Features (PWA)
Installable on mobile (Add to Home Screen)
Full-screen app experience
Offline support (via Service Worker)
Fast loading & lightweight

🧠 Calculation Logic
The app uses a mathematically correct formula:
cashout = balance / (1 + rate / 1000)

This ensures:
Accurate deduction of proportional charges
No guesswork or manual calculation
📊 Example
Balance
Rate
Cashout
Charge
1000
14.90
985.33
14.67
5250
14.90
5172.77
77.23

📁 Project Structure
Since this is a single-file architecture, everything is embedded:
Copy code

index.html
├── HTML (Structure)
├── CSS (Full UI System + Themes)
├── JavaScript (Logic + Interactions)
└── Embedded PWA Manifest

⚙️ How to Use
Enter your balance
Select a charge rate OR enter custom rate
Tap Calculate
View:
Max cashout amount
Total charge
Breakdown

🚀 Deployment
🔹 Vercel (Recommended)
Upload index.html
Deploy instantly
🔹 GitHub Pages
Push file to repo
Enable Pages
🔹 Local
Just open index.html in browser

👨‍💻 Developer
Shishir
🔗 Facebook: https://www.facebook.com/imshishr⁠�
