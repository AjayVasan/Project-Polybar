# Project-Polybar
🚀 Project Polybar – BSPWM Setup for Arch Linux


A minimal, elegant, and functional Polybar setup designed for BSPWM on Arch Linux. This configuration enhances productivity with dynamic workspace management, system monitoring, and seamless integrations.

🎯 Features
✅ Multi-Monitor Support – Auto-adjusts to multiple displays.
✅ Live System Stats – CPU, RAM, disk, network, and battery indicators.
✅ Workspace Indicators – Visual feedback for active workspaces.
✅ Media & Volume Controls – Play, pause, and adjust volume on the fly.
✅ Date & Time Module – Displays real-time date and time.
✅ App Launcher Integration – Works with Rofi for quick access.
✅ Notification Support – Fully compatible with Dunst.
✅ Theming & Customization – Easily tweak fonts, colors, and modules.

🛠️ Installation
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/AjayVasan/Project-Polybar.git  
cd Project-Polybar  
2️⃣ Install Dependencies
Ensure the following packages are installed:

sh
Copy
Edit
sudo pacman -S polybar bspwm rofi dunst 
3️⃣ Copy Configuration Files
sh
Copy
Edit
mkdir -p ~/.config/polybar  
cp -r config ~/.config/polybar  
4️⃣ Make the Launch Script Executable
sh
Copy
Edit
chmod +x ~/.config/polybar/launch.sh  
5️⃣ Start Polybar
sh
Copy
Edit
~/.config/polybar/launch.sh  
🎨 Customization
Modify ~/.config/polybar/config.ini to tweak the appearance and functionality.

Colors & Fonts – Adjust in config.ini.
Modules – Add or remove features as needed.
Startup Script – Customize launch.sh for personal preferences.
🖼️ Screenshots

🤝 Contributing
Found a bug or have a cool improvement? Feel free to submit an issue or pull request!
