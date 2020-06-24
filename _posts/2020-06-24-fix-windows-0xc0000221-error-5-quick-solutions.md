---
ID: 2921
post_title: 'Fix Windows 0xC0000221 Error!! (*5 Quick Solutions*)'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/fix-windows-0xc0000221-error-5-quick-solutions-2921/
published: true
post_date: 2020-06-24 07:30:21
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Windows 0xC0000221 Error: </strong>The error code 0xC0000221 has appeared typically after the system fails to boot. Sometimes, you may face this error while booting your PC every time or you may be stuck in an Automatic Repair Loop. The reason behind this error may due to the mismatch of the system file header checksum and so you will encounter BSOD screen error. Luckily, we are here to provide the best methods to <strong>Fix Windows 0xC0000221 E</strong><strong>rror.</strong>
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Booting in Safe Mode</a></strong></li>
 	<li><strong><a href="#2">Perform an SFC Scan</a></strong></li>
 	<li><strong><a href="#3">Verify for Disk Errors</a></strong></li>
 	<li><strong><a href="#4">Check for RAM Issues</a></strong></li>
 	<li><strong><a href="#5">Remove Secondary Devices</a></strong></li>
 	<li><strong><a href="#6">Conclusion</a></strong></li>
</ul>
<h2 id="1">1) Booting in Safe Mode:</h2>
You have to open your PC in safe mode and it is considered to be a vital step before proceeding to troubleshoot steps. If you get the BSOD error, you won't get the login screen. Therefore, it is essential to boot your system in safe mode so only a few applications and drivers will run and it restricts third-party applications.

BSOD are of two types:
<ol>
 	<li><strong>With Login Screen</strong> - If you can see the booting window, you just sign-in to your system and open the <strong>Run command</strong> by using this shortcut <strong>Windows key + R</strong> and then type '<strong>ms-settings:recovery</strong>' and click OK. Now, you have to click the <strong>Restart now</strong> button that is available under the <strong>Advanced startup</strong> section.</li>
 	<li><strong>Without Login Screen</strong> - During the startup process, you have to force the screen that shows <strong>Advanced Startup Options</strong> for two or more consecutive interruptions. You can perform this by restarting your system during the startup so you will get the troubleshooting window.</li>
</ol>
<ul>
 	<li>Once you see the screen that shows the <strong>Troubleshoot</strong> option, you have to click on it.</li>
 	<li>Then, continue to click on <strong>Advanced options -&gt;</strong> <strong>Startup Settings -&gt;</strong> <strong>Restart. </strong></li>
 	<li>You have to press F4, F5, or F6 to boot your PC with one of the three Safe Modes available.</li>
 	<li>Now, if you see the login screen, then it indicates that the recently installed application is the cause for the BSOD bug. So, try to locate the application that is recently installed and remove it from your system.</li>
</ul>
<h2 id="2">2) Perform an SFC Scan:</h2>
<ul>
 	<li>First, you have to click the <b>Windows key.</b></li>
 	<li>Then, type <strong>'cmd' </strong>in the search box. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type the below and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="aligncenter" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>Now, the System File Checker will perform a scan and repair the damaged or corrupted system files.</li>
 	<li>Once the scan gets done, restart your computer.</li>
</ul>
<h2 id="3">3) Verify for Disk Errors:</h2>
<ul>
 	<li>At first, you have to follow the method 1 to boot your computer in safe mode.</li>
 	<li>After that, you have to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to copy and paste the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">chkdsk C: /f /r /x</code></p>

<ul>
 	<li>C - Disk drive where Windows OS is installed</li>
 	<li>f - Identify the faults</li>
 	<li>r - Scanning faults in a given drive</li>
 	<li>x - Partition of the disk drive and starts repairing process</li>
</ul>
<h2 id="4">4) Check for RAM Issues:</h2>
If the above methods did not fix the error 0xc0000221, then it shows that the problem is in RAM. Make use of the Windows Memory Diagnostics built-in tool that checks the RAM and find out bad sectors.
<ul>
 	<li>You have to press the keyboard shortcut <strong>Windows key + R</strong> and then type '<strong>mdsched.exe</strong>' and click <strong>OK</strong>.

[caption id="attachment_2926" align="aligncenter" width="608"]<img class="size-full wp-image-2926" src="https://windowsjet.com/wp-content/uploads/2020/06/wi1-1.png" alt="mdsched.exe" width="608" height="374" /> mdsched.exe[/caption]</li>
 	<li>Follow the on-screen instructions and restart your computer to check whether the error gets fixed.</li>
</ul>
<h2 id="5">5) Remove Secondary Devices:</h2>
<ul>
 	<li>The error code 0xc0000221 can be fixed by removing all unnecessary secondary drives like webcams, flash drives, and other devices.</li>
 	<li>If your system boots up normally without showing BSOD error, after disconnecting all drives, you can try to connect the devices one by one and restart your system. So, in this way, you can identify which drive is the source of this error.</li>
</ul>
<h2 id="6">Conclusion:</h2>
We hope that after following the above two methods, the error 0xC0000221 gets fixed. You don't require any technical skills to <strong>Fix Windows 0xC0000221 Error</strong> as the solutions are given above are simple to execute. Kindly share your <strong>valuable comments</strong> in the below box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-quickly-fix-the-bsod-error-0xc000021a-on-windows-10-2454/" target="_blank" rel="noopener noreferrer"><strong>How to Quickly Fix the BSOD Error 0Xc000021a on Windows 10?</strong></a></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-the-server-stumbled-error-code-0x801901f7-2776/" target="_blank" rel="noopener noreferrer">How to Fix "The Server Stumbled" Error Code 0x801901F7?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-update-error-0x80080008-on-windows-3-quick-fixes-2478/" target="_blank" rel="noopener noreferrer">How to Fix Update Error 0x80080008 on Windows? (*3 Quick Fixes*)</a></strong></li>
</ul>