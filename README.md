# Caffeine
A bash script to enable caffeine mode.<br>
Use this tool when you don't want to let the device to sleep while you are gone for some time<br>
It works by simulating a left click (using xdotool) after every 10 minutes.<br>
<hr>
Steps to install(temp)
<ol>
<li>Copy the caffeine file to your Desktop(or any other folder)</li>
<li>Go to that folder via terminal.</li>
<li>Type in <pre>chmod +x caffeine</pre></li>
<li>Install xdotool</li>
</ol>
Thats it !!
<hr>
To run it
<ul>
  <li>Go to Desktop via terminal</li>
<li>Enter <pre>./caffeine</pre></li>
  <li>Enter the number of minutes you want the computer to remain awake</li>
<hr>
(Place caffeine in /usr/local/bin instead of placing it in the desktop and following step 3 to be able to launch it from anywhere (that is no going to any specific folder to run it))
