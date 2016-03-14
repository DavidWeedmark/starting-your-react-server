# starting-your-react-server
<p>How to install the server used in Facebook's Github React Tutorial</p>
<p>If you're just getting started with React.js, or any server-side web programming, there's a good chance you have never installed a web server on your PC before. This should explain those four little words in the tutorial enclosed in parenthesis, almost as an afterthought, in the tutorial: "Follow your progress by opening http://localhost:3000 in your browser (after starting the server)" in the <a href="https://facebook.github.io/react/docs/tutorial.html">Facebook's React Tutorial</a>.</p>
<h2>1. Download the Zip File</h2>
This is the <a href="https://github.com/reactjs/react-tutorial/archive/master.zip">react-tutorial-master</a> zip folder linked in the tutorial. Place it in your test folder on your PC and extract it. 
<h2>Open the ReadMe.md file</h2>
If your computer can't open this file, you can download and install </a href="https://notepad-plus-plus.org/">NotePad++</a>, a free text editor ideal for working on things like Javascript. 
This file contains the commands you need to start your server. In this tutorial we'll be starting node server.js
<h2>2.Open PowerShell</h2>
After logging into your PC with an admin user account (any account with admin privileges), type "powershell" in the Windows search field and press Enter. This should already be on your Windows computer. If for some reason you don't have PowerShell, you can use Command Prompt (type "cmd" in Windows Search). Mac users can use Terminal.
<h2>3. Go to Your Test Folder</h2>
In PowerShell, navigate to the test directory.
Type "dir" and press Enter to see the contents of your current directory or folder. 
Type "cd .." to go up one level in your directory.
Type "cd folder-name" to open a sub folder. 
Once you get to your test folder type "cd react-tutorial-master" and press Enter.
Open the readme file and type the code you see there: 
"npm install" and press Enter. Wait a few seconds for it to install.
When the command prompt returns, type: 
"node server.js" and press Enter.
After several seconds, you'll see: 
"Server started: http://localhost:3000/" indicating that the server successfully started.
<h2>4. Open a Web Browser</h2>
Type "http://localhost:3000" in the address bar and you should see the web page you need to begin working through the tutorial.
<h2>5. Have fun with the tutorial</h2>


