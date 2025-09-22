# MCP Puppeteer VS Code



Integrating a Puppeteer Model Context Protocol (MCP) server with VS Code enables AI-powered coding tools within VS Code to interact with and automate web browsers. This allows functionalities like web page navigation, element interaction, screenshot capture, and JavaScript execution within a browser context, all controlled through an AI assistant or agent within VS Code.



## Setup in VS Code:



## Install Node.js: Ensure Node.js (version 18 or higher is recommended) is installed on your system.



Node.js is a platform for building fast and scalable server applications using JavaScript. Node.js is the runtime and npm is the Package Manager for Node.js modules.



Visual Studio Code has support for the JavaScript and TypeScript languages out-of-the-box as well as Node.js debugging. However, to run a Node.js application, you will need to install the Node.js runtime on your machine.



https://code.visualstudio.com/docs/nodejs/nodejs-tutorial





## Download and Install Node.js



https://nodejs.org/en/download/





## Add MCP Server Configuration:

Open VS Code and press Ctrl + Shift + P to open the command palette.

Type and select "Preferences: Open User Settings (JSON)".

Add a JSON block to your settings.json file to configure the Puppeteer MCP server. The configuration typically specifies the command to run the server (e.g., using npx to execute a package like puppeteer-mcp-server).

Alternatively, for workspace-specific configuration, create a .vscode/mcp.json file in your workspace root and add the server configuration there (without the top-level mcp key).



## Restart VS Code: Close and reopen VS Code to ensure the new MCP server configuration is loaded.



Utilize with AI Tools: If you are using an AI coding assistant or agent within VS Code that supports MCP (e.g., Claude Code, Cursor), you can then instruct it to use the Puppeteer MCP server to perform browser automation tasks.



## Example Configuration for User Settings (JSON):



{

&nbsp; "mcpServers": {

&nbsp;   "puppeteer": {

&nbsp;     "command": "npx",

&nbsp;     "args": \["-y", "puppeteer-mcp-server"],

&nbsp;     "env": {}

&nbsp;   }

&nbsp; }

}



