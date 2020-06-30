---
ID: 3093
post_title: '{Quick Solutions} Fix Windows Update Error Code 0x80070490!!'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/quick-solutions-fix-windows-update-error-code-0x80070490-3093/
published: true
post_date: 2020-06-30 03:32:51
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Windows Update Error Code 0x80070490: </strong>The error code 0x80070490 indicates a corrupted file in Component-Based Servicing (CBS) or in System Component Store. These two services have the responsibility of running and controlling all Windows related updates actions. When there is any damage or corrupt within their files, then the Windows Update component might be inoperable. In such cases, you will receive this error on your screen. We will share here some easy methods to fix <strong>Windows Update Error Code 0x80070490 </strong>on your own very quickly.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Disable Third-Party Antivirus</a></strong></li>
 	<li><strong><a href="#2">Run the Update Troubleshooter</a></strong></li>
 	<li><strong><a href="#3">Run the SFC Scan</a></strong></li>
 	<li><strong><a href="#4">Using DISM Tool</a></strong></li>
 	<li><strong><a href="#5">Check Specific Services are Enabled</a></strong></li>
 	<li><strong><a href="#6">Delete ID Cache via Registry Editor</a></strong></li>
 	<li><strong><a href="#7">Verdict</a></strong></li>
</ul>
<h2 id="1">1) Disable Third-Party Antivirus:</h2>
Disabling the antivirus and the firewall can help you to fix the error and so you just follow the below steps.
<ul>
 	<li>First, you have to right-click on the antivirus software that is placed on the Taskbar.</li>
 	<li>After that, you need to choose the <strong>Disable</strong> option.</li>
 	<li>In order to make sure that the antivirus is off, you have to use this shortcut <strong>Ctrl + Alt + Delete</strong> to open the <strong>Task Manager</strong> and check whether any antivirus software is running.</li>
</ul>
<h2 id="2">2) Run the Update Troubleshooter:</h2>
<ul>
 	<li>Open the <strong>Settings</strong> by using this shortcut <strong>Windows key + I</strong>.</li>
 	<li>Then, you have to click on the <strong>Update &amp; Security </strong>option.

[caption id="attachment_2863" align="aligncenter" width="1320"]<img class="size-full wp-image-2863" src="https://windowsjet.com/wp-content/uploads/2020/06/au6.png" alt="Update &amp; Security" width="1320" height="818" /> Update &amp; Security[/caption]</li>
 	<li>Now, you have to tap on the <strong>Troubleshoot</strong> option in the left pane.

[caption id="attachment_2864" align="aligncenter" width="1320"]<img class="size-full wp-image-2864" src="https://windowsjet.com/wp-content/uploads/2020/06/au7.png" alt="Troubleshoot" width="1320" height="822" /> Troubleshoot[/caption]</li>
 	<li>Then, you have to select <b>Windows Update </b>under '<strong>Get up and running</strong>'.

[caption id="attachment_2865" align="aligncenter" width="1319"]<img class="size-full wp-image-2865" src="https://windowsjet.com/wp-content/uploads/2020/06/au8.png" alt="Windows Update" width="1319" height="819" /> Windows Update[/caption]</li>
 	<li>Next, you have to click on <strong>Run the troubleshooter</strong> button.

[caption id="attachment_2866" align="aligncenter" width="1322"]<img class="size-full wp-image-2866" src="https://windowsjet.com/wp-content/uploads/2020/06/au9.png" alt="Run the troubleshooter" width="1322" height="821" /> Run the troubleshooter[/caption]</li>
 	<li>Follow the on-screen instructions to finish the troubleshooting process.</li>
 	<li>After that, try to update your PC to check whether the error gets fixed.</li>
</ul>
<h2 id="3">3) Run the SFC Scan:</h2>
<ul>
 	<li>Go to the <strong>Start</strong> menu and type <strong>'cmd' </strong>in the search box. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="alignnone" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>Now, the System File Checker will perform a scan and repair the damaged or corrupted files of your system.</li>
 	<li>Once the scan gets completed, restart your PC.</li>
</ul>
<h2 id="4">4) Using DISM Tool:</h2>
Follow the below steps to fix the error by using the Deployment Image Servicing and Management (DISM) tool.
<ul>
 	<li>Go to the <strong>Start</strong> menu and type <strong>'cmd' </strong>in the search box. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">DISM.exe /Online /Cleanup-image /Restorehealth</code></p>

<ul>
 	<li>Run the below command and hit Enter if your Windows Update client is damaged or corrupted.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">DISM.exe /Online /Cleanup-Image /RestoreHealth /Source:C:\RepairSource\Windows /LimitAccess</code></p>

<h2 id="5">5) Check Specific Services are Enabled:</h2>
<ul>
 	<li>Hit <strong>Windows key + R</strong> keyboard shortcut to open the <strong>Run Command</strong>.</li>
 	<li>Then, you have to type '<strong>services.msc</strong>' and click <strong>OK</strong>.

[caption id="attachment_2858" align="aligncenter" width="604"]<img class="size-full wp-image-2858" src="https://windowsjet.com/wp-content/uploads/2020/06/au1.png" alt="services.msc" width="604" height="372" /> services.msc[/caption]</li>
 	<li>In the <strong>Services</strong> window, you have to scroll down and locate the <strong>Windows Update, MSI Installer, and Cryptographic </strong>services in order to make sure they are running properly.</li>
 	<li>If you notice any service is not running, you have to right-click on it and choose '<strong>Start the service</strong>'.</li>
 	<li>Then, you can try to update your system using Windows Update.</li>
</ul>
<h2 id="6">6) Delete ID Cache via Registry Editor:</h2>
<ul>
 	<li>You have to make use of this keyboard shortcut <strong>Windows key + R </strong>to open the <strong>Run command</strong>.</li>
 	<li>Type '<strong>regedit.exe</strong>' and click<strong> OK</strong>.

[caption id="attachment_2839" align="aligncenter" width="570"]<img class="size-full wp-image-2839" src="https://windowsjet.com/wp-content/uploads/2020/06/dm1.png" alt="regedit" width="570" height="337" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>On the left pane, you have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Appx\AppxAllUserStore</code></p>

<ul>
 	<li>Now, you have to locate the folder with this number sequence '<strong>S-1-5-21-1505978256-3813739684-4272618129-1016</strong>' and then right-click on it and choose the <strong>Delete</strong> option.</li>
 	<li>After that, you have to close all the opened windows and restart your computer.</li>
</ul>
<h2 id="7">Closure:</h2>
Hopefully, this article guided you to fix<strong> Windows Update Error Code 0x80070490</strong> easily. You just follow the steps and get rid of this error on your system. Don't forget to share your <strong>comments/feedback</strong> in the below section. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-10-error-code-0x80070103-2-quick-fixes-2729/" target="_blank" rel="noopener noreferrer">Fix Windows 10 Error Code 0x80070103!! (*2 Quick Fixes*)</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-windows-10-upgrade-error-code-0x80070070-2707/" target="_blank" rel="noopener noreferrer">How to Fix Windows 10 Upgrade Error Code 0x80070070?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-10-update-error-0xc1900209-qucikly-2819/" target="_blank" rel="noopener noreferrer">Fix Windows 10 Update Error 0xc1900209!! [Qucikly]</a></li>
</ul>