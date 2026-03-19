# Sonic-Mania-Plus-Port-For-NautilusOS
🎮 #Sonic Mania Plus — NautilusOS Port

A high‑quality browser port of Sonic Mania Plus, packaged for NautilusOS.
📌 Overview

This project is a port of Sonic Mania Plus designed to run directly inside NautilusOS through the Community Games system.
It includes a fully playable browser build, proper file structure, and metadata so it integrates seamlessly with the NautilusOS launcher.
📁 Project Structure
Code

games/
 
 └── racine/
 
      └── sonic-mania-plus/
      
           ├── files/
           
           │    └── index.html
           
           └── info.json

    files/ contains the full web build of the game

    info.json provides metadata used by NautilusOS

    The game is registered in the root games.json file

🚀 Features

    Fully playable Sonic Mania Plus in the browser

    Works inside NautilusOS’s game launcher

    Clean folder structure following Community repo standards

    Fast loading and optimized assets

    Controller + keyboard support (depending on your build)

🛠️ Installation (For Developers)

    Clone the NautilusOS Community repo:
    bash

    git clone https://github.com/nautilus-os/community

    Navigate to the games directory:
    bash

    cd community/games/racine/sonic-mania-plus

    Place your build inside the files/ folder

    Ensure info.json is filled out correctly

    Add your entry to games.json

    Commit and push your changes

    Open a Pull Request to the main repo

📄 info.json Example
json

{
  
  
  "name": "Sonic Mania Plus",
  
  
  "desc": "A browser port of Sonic Mania Plus for NautilusOS.",
  
  
  "icon": "fas fa-gamepad",
  
  
  "author": "Racine",
  
  
  "url": "https://your-hosted-build-url"
}

🧩 Compatibility

    Works on all modern browsers

    Optimized for NautilusOS’s embedded browser environment

    Performance may vary depending on device hardware

📬 Contributing

If you want to improve the port, optimize performance, or fix bugs, feel free to open an issue or submit a PR.
📝 License

This port is provided for educational and archival purposes.
All Sonic Mania Plus assets belong to their respective owners.
