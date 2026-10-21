Step-by-Step Guide & Instructions
1. Install Visual Studio Code
What to do: Download and install VS Code, which will be your primary code editor.

How to do it:

Go to the official website: code.visualstudio.com

Download the installer for your operating system (Windows, macOS, or Linux).

Run the installer and follow the on-screen setup prompts.

2. Install the LTS version of Node.js
What to do: Install Node.js (Long Term Support version), which includes npm (Node Package Manager).

How to do it:

Go to the official website: nodejs.org

Download the LTS (Long Term Support) version.

Run the installer and complete the setup. Make sure to check the option to add Node.js to your PATH if prompted.

3. Install Live Server and Prettier Extensions in VS Code
What to do: Add extensions to make web development easier (Live Server auto-refreshes your browser, and Prettier formats your code).

How to do it:

Open VS Code.

Click on the Extensions icon on the left sidebar (or press Ctrl+Shift+X on Windows/Linux or Cmd+Shift+X on macOS).

Search for Live Server (by Ritwick Dey) and click Install.

Search for Prettier - Code formatter and click Install.

4. Create the web-development-practice Folder
What to do: Create a dedicated workspace folder for your practice files.

How to do it:

Create a new folder anywhere on your computer (for example, on your Desktop or in a Documents folder) and name it exactly: web-development-practice.

Open VS Code, go to File > Open Folder..., and select the web-development-practice folder you just created.

5. Create index.html, style.css, and script.js Files
What to do: Set up the basic files for a web project.

How to do it:

Inside VS Code, use the New File icon in the Explorer panel to create three files:

index.html

style.css

script.js

Optional quick start: Open index.html, type ! (exclamation mark), and press Enter to generate a basic HTML template. Link your CSS and JS if desired.

6. Run the HTML file in the browser using Live Server
What to do: Test your setup by viewing your HTML page live.

How to do it:

Open index.html in VS Code.

Right-click anywhere inside the index.html editor window and select Open with Live Server (or click the Go Live button at the bottom-right corner of the VS Code status bar).

Your default web browser will open automatically, displaying your webpage.

7. Verify the installation via Terminal
What to do: Check that Node and npm are correctly installed and accessible.

How to do it:

In VS Code, open the integrated terminal by going to Terminal > New Terminal (or pressing Ctrl + ~ / Cmd + ~).

Type the following command and press Enter:

Bash
node -v
Type the following command and press Enter:

Bash
npm -v
Note down or keep the version numbers visible in your terminal.

📸 What to Submit
Based on your assignment instructions, you need to capture screenshots of the following items:

VS Code: Showing your open web-development-practice folder with index.html, style.css, and script.js files, along with the installed extensions.

Node.js Version: Your terminal window displaying the output of node -v and npm -v.

Browser: Your web page running in the browser via Live Server.