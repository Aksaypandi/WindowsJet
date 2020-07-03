---
ID: 3261
post_title: '[Latest] How to Fix Access Violation Error 0xC0000005?'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/latest-how-to-fix-access-violation-error-0xc0000005-3261/
published: true
post_date: 2020-07-03 09:25:23
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Access Violation Error 0xC0000005: </strong>The error code 0xc0000005 may occur due to several reasons such as malware infection, corrupt registry files, incorrect hardware configuration, etc. If you get the error, you don't have to be concerned about it as we are here with efficient solutions. Let's see some quick methods to Fix <strong>Access Violation Error 0xC0000005.</strong>
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Scan your PC for Viruses</a></strong></li>
 	<li><strong><a href="#2">Modify Registry Values</a></strong></li>
 	<li><strong><a href="#3">Turn Off DEP</a></strong></li>
 	<li><strong><a href="#4">Update the Hardware Drivers</a></strong></li>
 	<li><strong><a href="#5">Perform an SFC Scan</a></strong></li>
 	<li><strong><a href="#6">Restore your System</a></strong></li>
 	<li><strong><a href="#7">Reset your PC</a></strong></li>
 	<li><strong><a href="#8">A Short Closure</a></strong></li>
</ul>
<h2 id="1">1) Scan your PC for Viruses:</h2>
<ul>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>Next, you have to click on the <strong>Update &amp; Security</strong> option.

[caption id="attachment_2863" align="aligncenter" width="1320"]<img class="size-full wp-image-2863" src="https://windowsjet.com/wp-content/uploads/2020/06/au6.png" alt="Update &amp; Security" width="1320" height="818" /> Update &amp; Security[/caption]</li>
 	<li>In the left pane, you have to choose <strong>Windows Security</strong>.

[caption id="attachment_3275" align="aligncenter" width="1323"]<img class="size-full wp-image-3275" src="https://windowsjet.com/wp-content/uploads/2020/07/Windows-Security.png" alt="Windows Security" width="1323" height="811" /> Windows Security[/caption]</li>
 	<li>On the right side, you have to choose <strong>Virus &amp; threat protection</strong> under <strong>Protection areas</strong>.

[caption id="attachment_3274" align="aligncenter" width="1330"]<img class="size-full wp-image-3274" src="https://windowsjet.com/wp-content/uploads/2020/07/Virus-threat-protection.png" alt="Virus &amp; threat protection" width="1330" height="819" /> Virus &amp; threat protection[/caption]</li>
 	<li>Click on the <strong>Scan options</strong> link.

[caption id="attachment_3271" align="aligncenter" width="1038"]<img class="size-full wp-image-3271" src="https://windowsjet.com/wp-content/uploads/2020/07/Scan-options.png" alt="Scan options" width="1038" height="819" /> Scan options[/caption]</li>
 	<li>After that, you have to choose the <strong>Full scan</strong> option and then click on the <strong>Scan now</strong> button.

[caption id="attachment_3267" align="aligncenter" width="1028"]<img class="size-full wp-image-3267" src="https://windowsjet.com/wp-content/uploads/2020/07/Full-scan.png" alt="Full scan" width="1028" height="821" /> Full scan[/caption]</li>
</ul>
<h2 id="2">2) Modify Registry Values:</h2>
<ul>
 	<li>Using this shortcut <strong>Windows key + R</strong>, you can open the <strong>Run command</strong>.</li>
 	<li>Type '<strong>regedit.exe</strong>' and click<strong> OK</strong>.

[caption id="attachment_2839" align="aligncenter" width="570"]<img class="size-full wp-image-2839" src="https://windowsjet.com/wp-content/uploads/2020/06/dm1.png" alt="regedit" width="570" height="337" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>You have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Windows</code></p>

<ul>
 	<li>Double-click on <strong>AppInit_DLLs</strong> and set its value to <strong>0</strong> and click <strong>OK</strong>.

[caption id="attachment_3265" align="aligncenter" width="1194"]<img class="size-full wp-image-3265" src="https://windowsjet.com/wp-content/uploads/2020/07/AppInit_DLLs.png" alt="AppInit_DLLs" width="1194" height="728" /> AppInit_DLLs[/caption]</li>
 	<li>Then, you have to restart your system and try to open the application which does not open before.</li>
</ul>
<h2 id="3">3) Turn Off DEP:</h2>
<ul>
 	<li>You have to press <strong>Windows key + R</strong> to open the <strong>Run Command</strong>. Then, you have to type '<strong>sysdm.cpl</strong>' and click <strong>OK</strong>.

[caption id="attachment_3273" align="aligncenter" width="609"]<img class="size-full wp-image-3273" src="https://windowsjet.com/wp-content/uploads/2020/07/sysdm.cpl_.png" alt="sysdm.cpl" width="609" height="374" /> sysdm.cpl[/caption]</li>
 	<li>You have to click the <strong>Advanced</strong> tab and click on the <strong>Settings</strong> button under the <strong>Performance</strong> section.

[caption id="attachment_3272" align="aligncenter" width="663"]<img class="size-full wp-image-3272" src="https://windowsjet.com/wp-content/uploads/2020/07/Settings.png" alt="Settings" width="663" height="743" /> Settings[/caption]</li>
 	<li>Now, you have to click on the <strong>Data Execution Prevention</strong> tab and then select '<strong>Turn on DEP for all programs and services except those I select</strong>' option and click <strong>Add</strong>.

[caption id="attachment_3264" align="aligncenter" width="596"]<img class="size-full wp-image-3264" src="https://windowsjet.com/wp-content/uploads/2020/07/Add.png" alt="Add" width="596" height="974" /> Add[/caption]</li>
 	<li>Then, you have to browse and add all the executable (.exe) files that are causing the problem.</li>
 	<li>Then, click <strong>OK</strong> and restart your system.</li>
</ul>
<h2 id="4">4) Update the Hardware Drivers:</h2>
<ul>
 	<li>Hit <strong>Windows key + X</strong> to open the Power User menu and then click on the <strong>Device Manager </strong>option.

[caption id="attachment_3026" align="aligncenter" width="1069"]<img class="size-full wp-image-3026" src="https://windowsjet.com/wp-content/uploads/2020/06/de2.png" alt="Device Manager" width="1069" height="918" /> Device Manager[/caption]</li>
 	<li>In the <strong>Device Manager</strong> window, you have to locate the driver that is indicated with a yellow exclamation mark.</li>
 	<li>Right-click on the driver and choose <strong>Update driver</strong> option.</li>
 	<li>Then, you have to choose '<strong>Search automatically for updated driver software</strong>' option.</li>
 	<li>After that, restart your PC to apply the changes.</li>
</ul>
<h2 id="5">5) Perform an SFC Scan:</h2>
<ul>
 	<li>You just go to the search box and type <strong>‘command prompt’</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type <strong>‘sfc /scannow’</strong> and hit <strong>Enter</strong>.

[caption id="attachment_2491" align="aligncenter" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]</li>
 	<li>Now the System File Checker will perform a scan and repair the damaged or corrupted system files.</li>
 	<li>Once the scan gets completed, restart your device.</li>
</ul>
<h2 id="6">6) Restore your System:</h2>
<ul>
 	<li>You have to press <strong>Windows key + R</strong> to open the <strong>Run box</strong>.</li>
 	<li>Type '<strong>rstrui.exe</strong>' and click <strong>OK</strong> button.

[caption id="attachment_3199" align="aligncenter" width="602"]<img class="size-full wp-image-3199" src="https://windowsjet.com/wp-content/uploads/2020/07/rstrui.exe_.png" alt="rstrui.exe" width="602" height="365" /> rstrui.exe[/caption]</li>
 	<li>You can see a window of '<strong>System Restore</strong>'. You have to click the <strong>Next</strong> button.

[caption id="attachment_3270" align="aligncenter" width="894"]<img class="size-full wp-image-3270" src="https://windowsjet.com/wp-content/uploads/2020/07/Next-2.png" alt="Next" width="894" height="709" /> Next[/caption]</li>
 	<li>Select the update that working fine and click the <strong>Next</strong> button.

[caption id="attachment_3266" align="aligncenter" width="897"]<img class="size-full wp-image-3266" src="https://windowsjet.com/wp-content/uploads/2020/07/Choose-update-and-Next.png" alt="Choose update and Next" width="897" height="711" /> Choose update and Next[/caption]</li>
 	<li>At last, tap on the <strong>Finish</strong> button.</li>
</ul>
<h2 id="7">7) Reset your PC:</h2>
<ul>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>Then, you have to click on <strong>Update &amp; Security</strong>.

[caption id="attachment_2863" align="aligncenter" width="1320"]<img class="size-full wp-image-2863" src="https://windowsjet.com/wp-content/uploads/2020/06/au6.png" alt="Update &amp; Security" width="1320" height="818" /> Update &amp; Security[/caption]</li>
 	<li>In the left pane, you have to click on <strong>Recovery</strong>.

[caption id="attachment_3247" align="aligncenter" width="1331"]<img class="size-full wp-image-3247" src="https://windowsjet.com/wp-content/uploads/2020/07/Recovery.png" alt="Recovery" width="1331" height="817" /> Recovery[/caption]</li>
 	<li>Now, you have to click on the <strong>Get started </strong>button under <strong>Reset this PC.</strong></li>
 	<li>After that, you have to select the <strong>Keep my files</strong> in the <strong>Choose an option.</strong></li>
 	<li>Now, your system will reset OS automatically.</li>
 	<li>You will be asked to enter your user name, email, and password once the factory settings get restored.</li>
</ul>
<h2 id="8">A Short Closure:</h2>
We hope that you liked this article on how to fix <strong>Access Violation Error 0xC0000005</strong> by following simple and easy methods. You just follow any one of the above methods and fix the error code 0xC0000005 quickly. Feel free to leave your <strong>valuable comments</strong> about this article. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-windows-error-code-0x80070057-simple-solutions-2396/" target="_blank" rel="noopener noreferrer">How to Fix Windows Error Code 0x80070057? { Simple Solutions}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-update-error-80243004-3-easy-fixes-3118/" target="_blank" rel="noopener noreferrer">Fix Windows Update Error 80243004!! (*3 Easy Fixes*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-device-manager-error-code-41-5-easy-methods-2829/" target="_blank" rel="noopener noreferrer">How to Fix Device Manager Error Code 41? (*5 Easy Methods*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/solved-how-to-fix-error-code-0x80240024-on-windows-10-store-3102/" target="_blank" rel="noopener noreferrer">[Solved] How to Fix Error Code 0x80240024 on Windows 10 Store?</a></strong></li>
</ul>