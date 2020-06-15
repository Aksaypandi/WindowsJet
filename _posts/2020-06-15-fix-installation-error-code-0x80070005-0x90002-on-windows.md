---
ID: 2632
post_title: >
  Fix Installation Error Code
  0x80070005-0x90002 on Windows!!
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/fix-installation-error-code-0x80070005-0x90002-on-windows-2632/
published: true
post_date: 2020-06-15 04:47:55
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Installation Error Code 0x80070005-0x90002: </strong>The error code 0x80070005 – 0x90002 normally shows up when you opt for Windows 10 installer. There are various reasons why this error occurs, but the most common reason is that the installer could not find the required files. It is also considered that the error appears due to damage of .dll files or the error might be caused by third-party antivirus software. In this tutorial, we will look out the methods to <strong>Fix Installation Error Code 0x80070005-0x90002 </strong>on Windows.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Disable Antivirus Software</a></strong></li>
 	<li><strong><a href="#2">Run an SFC Scan</a></strong></li>
 	<li><strong><a href="#3">Use Registry Editor</a></strong></li>
 	<li><strong><a href="#4">Verdict</a></strong></li>
</ul>
<h2 id="1">1) Disable Antivirus Software:</h2>
<ul>
 	<li>To open the <strong>Settings</strong>, you have to use this shortcut <strong>Windows key + I.</strong></li>
 	<li>After that, you have to click on <strong>Apps</strong>.

[caption id="attachment_1819" align="aligncenter" width="878"]<img class="size-full wp-image-1819" src="https://windowsjet.com/wp-content/uploads/2020/05/om1.png" alt="Select Apps" width="878" height="557" /> Select Apps[/caption]</li>
 	<li>Next, you can see the list of applications installed on your device under <strong>Apps &amp; features. </strong></li>
 	<li>Then, you have to look for your antivirus software and select it.</li>
 	<li>You have to click on the <strong>Uninstall</strong> button.</li>
 	<li>At last, you can try to update your Windows system.</li>
 	<li>If the error still occurs, then move on to the next fix.</li>
</ul>
<h2 id="2">2) Perform an SFC Scan:</h2>
<ul>
 	<li>Click on the <strong>Start</strong> menu. In the search box, you have to type <strong>'command prompt'</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="alignnone" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>Now, the System File Checker will perform a scan and repair the corrupted system files.</li>
 	<li>Once the scan gets completed, restart your PC.</li>
</ul>
<h2 id="3">3) Use Registry Editor:</h2>
<ul>
 	<li>Using this shortcut <strong>Windows key + R</strong>, you can open the <strong>Run command</strong>.</li>
 	<li>Type <strong>regedit.exe </strong>and click<strong> OK</strong>.

[caption id="attachment_2413" align="alignnone" width="426"]<img class="size-full wp-image-2413" src="https://windowsjet.com/wp-content/uploads/2020/06/ec1.png" alt="regedit.exe" width="426" height="231" /> regedit.exe[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>You have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\OSUpgrade</code></p>

<ul>
 	<li>If you don't find the <strong>OSUpgrade</strong> folder, right-click on <strong>WindowsUpdate</strong> and choose <strong>New</strong> and then click on <strong>Key</strong>. After that, you have to name the key as OSUpgrade.</li>
 	<li>Right-click inside OSUpgrade and choose <strong>New</strong> and then choose <strong>DWORD (32-bit) Value</strong>.</li>
 	<li>Next, you have to name the key as <strong>AllowOSUpgrade</strong> and double-click on it and set its value to <strong>0x00000001. </strong></li>
 	<li>Then, close the Registry Editor and reboot your system.</li>
 	<li>After that, try to upgrade your PC.</li>
</ul>
<h2 id="4">Conclusion:</h2>
We hope that after following the above three methods installation error 0x80070005-0x90002 gets fixed. You don't require any technical skills to <strong>Fix Installation Error Code 0x80070005-0x90002 on Windows</strong><strong> </strong>as the solutions given above are simple to execute. Kindly share your <strong>valuable comments</strong> in the below box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-windows-error-code-0x80070057-simple-solutions-2396/" target="_blank" rel="noopener noreferrer">How to Fix Windows Error Code 0x80070057? { Simple Solutions}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/4-quick-methods-to-fix-windows-update-error-code-c1900107-2600/" target="_blank" rel="noopener noreferrer">(*4 Quick Methods*) to Fix Windows Update Error Code C1900107!!</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-alres409-dll-error-on-windows-5-simple-solutions-2613/" target="_blank" rel="noopener noreferrer">How to Fix ALRES409.dll Error on Windows? {5 Simple Solutions}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-quickly-fix-the-bsod-error-0xc000021a-on-windows-10-2454/" target="_blank" rel="noopener noreferrer">How to Quickly Fix the BSOD Error 0Xc000021a on Windows 10?</a></strong></li>
</ul>