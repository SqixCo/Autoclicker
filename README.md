## License

This project is licensed under the GNU General Public License v3.0  
© 2025 Sandipan Ghosh – SQIX™  | support@SQIX.com  
See the [LICENSE.txt](https://github.com/SqixCo/Autoclicker/blob/main/LICENSE) file for details.




## SQIX™  Autoclicker
=======

SQIX™  Autoclicker is a lightweight, open-source desktop tool designed to simulate mouse clicks automatically at customizable intervals. Built for productivity, automation, and usability, it helps users keep their desktops active and handle repetitive clicking tasks effortlessly.


## Core Functionality
Automated Mouse Clicking
Simulates left, right, or middle mouse clicks automatically at predefined time intervals.

Click Type Selection
Choose between left-click, right-click, or middle-click functionality depending on your use case.

Click Interval Customization
Set precise delay between clicks (in milliseconds or seconds) for maximum control.


## Control & Flexibility
Start/Stop via Button or Hotkey (optional)
Quickly toggle the autoclicker using a visible button or keyboard shortcut (configurable).

Fixed or Dynamic Cursor Positioning
Automatically click at the current mouse location or a specified screen coordinate.

Click Count Limiting (optional)
Configure the number of total clicks before auto-stopping.


## User Interface & Experience
Minimal, Intuitive UI
Simple layout focused on ease-of-use. No unnecessary clutter or distractions.

Tray Icon Support (if implemented)
Option to minimize the app to the system tray for background operation.

Real-Time Status Indicator
Display current click status, active/inactive mode, and runtime metrics.


## Compatibility & Portability
Windows OS Support
Fully compatible with Windows 10/11 and Windows Server environments.

Portable Build (No Installation Needed)
Single .exe file — run directly without setup or registry modification.

Low Resource Usage
Lightweight and optimized to consume minimal system memory and CPU.


## Open Source Licensing
GPL v3 Licensed
Freely use, modify, and distribute under the GNU General Public License version 3.

Modifiable Codebase
Developers can inspect or extend functionality while maintaining attribution.

Attribution & Non-Monetization Clause
Protects your work from unauthorized resale or uncredited use.



## Ideal Use Cases
Preventing system sleep/idle (for remote sessions or VPNs)

Automating form submissions or UI testing

Gaming (non-monetized, ethical use)

Repetitive clicking in legacy software interfaces

Keeping collaboration tools (Slack, Teams, Zoom) "active"

Kiosk or demo station activity simulators



## Keep your computer active while away for long duration
This is a simple autoclicker that can be used to keep your computer active while away for long duration. This includes your downloads, emails, messengers, remote site access, etc.

### UI Screenshots
1. Open GUI
   

<img width="397" height="323" alt="open_gui" src="https://github.com/user-attachments/assets/ff4fa51e-8675-4e7f-b62c-37084d6eb2d8" />



2. After pressing Start Button


<img width="401" height="324" alt="Start" src="https://github.com/user-attachments/assets/94d8efbf-7964-4249-8e63-56e7ee3b4633" />




3. On prolonged runnig of the app (In this use case, 2 mins almost)


<img width="415" height="332" alt="running" src="https://github.com/user-attachments/assets/e169fa91-a738-4a9f-b64f-cfe7e69edd16" />


4. Once stopped

   
<img width="399" height="321" alt="Stop" src="https://github.com/user-attachments/assets/fc52c901-335c-4af7-9d6f-e52ff4d15246" />




### How to Use
 1. App launches a GUI -  A small window opens with SQIX™  Logo which also has a button to start the autoclicker.
 2. The welcome message shows the status of the autoclicker.
 3. You get two buttons and you can also adjust the interval between which the autoclicker will click. The default is 120 seconds
 4. When you click Start, the app starts a background task called thread that clicks the mouse every 120 seconds by default and clicks again.
 5. When you click Stop, the app stops the background task.
 6. After each click of the Start button it plays a funny message and shows the count. The counter by default increases the count by 1 after every 120 seconds or whenever the mouse clicks the screen.
 7. You may change the interval time in the GUI.
 8. The message also displays tha the autoclicker is stopped whn you hit the stop button and shows a funny message, "SQIX™  is tired"



### Software Installation

1. Portable .exe file — just download and run.
2. Source code available and modifiable under the GNU General Public License.
3. Designed to work on Windows 10/11 systems.

### Operation

1. Set how frequently the tool clicks — from milliseconds to seconds — based on your needs.
2. Option to click wherever the mouse is currently located or at a specific coordinate on screen.
3. Enable or disable clicking instantly with a simple keyboard shortcut.
4. Clean interface with start/stop controls and status indicator. Designed for simplicity.
5. Runs quietly in the background with a tray icon for quick access and minimal distraction.

### Windows build

```python -m PyInstaller --onefile --windowed --icon=images/Sqix-Autoclicker.ico --add-data "images/*;images" SQIX_Autoclicker.py```


#### TODO

 Finalize main functionality (auto click at intervals)

 Add support for click type (left, right, middle)

 Add click interval and duration settings

 Optional: Add hotkey support for Start/Stop

 Optional: Add system tray minimization

 Show status (active/inactive) in UI

 Add click position toggle (cursor vs fixed point)
