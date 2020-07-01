---
ID: 3191
post_title: >
  How to Fix Windows Backup and Restore
  Error 0x800700b7?
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-fix-windows-backup-and-restore-error-0x800700b7-3191/
published: true
post_date: 2020-07-01 12:51:35
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Windows Backup and Restore Error 0x800700b7: </strong>The error code 0x800700b7 may appear when you try to perform a system restore or backup process. Windows backup and restore service is considered to be a vital thing as you can backup your data regularly and restore it when needed. Once you received this error, you cannot restore your data. Let's look out the causes of this error and some simple solutions to <strong>Windows Backup and Restore Error 0x800700b7</strong>.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Reasons for Error 0x800700b7</a></strong></li>
 	<li><strong><a href="#2">Run System Restore in Safe Mode</a></strong></li>
 	<li><strong><a href="#3">Disable Third-Party Antivirus</a></strong></li>
 	<li><strong><a href="#4">Perform an SFC Scan</a></strong></li>
 	<li><strong><a href="#5">Restore the Registry</a></strong></li>
 	<li><strong><a href="#6">Closure</a></strong></li>
</ul>
<h2 id="1">Reasons for Error 0x800700b7:</h2>
<ul>
 	<li>Third-party antivirus software conflicts with system restore</li>
 	<li>Corrupted and damaged files or malware</li>
 	<li>Registry failure</li>
 	<li>Failed or pending installation of a program</li>
</ul>
<h2 id="2">Fix 1 - Run System Restore in Safe Mode:</h2>
<ul>
 	<li>You have to reboot your system in safe mode.</li>
 	<li>In order to restart your Windows system, you have to hold the <strong>Shift</strong> key and choose the <strong>Restart</strong> option.</li>
 	<li>Now, you can see the screen that shows <strong>Choose an Option</strong>. Here, you have to select <strong>Troubleshoot</strong>.</li>
 	<li>Then, you have to choose <strong>Advanced options</strong>.</li>
 	<li>In the next window, you have to select <strong>Startup Settings </strong>then click on<strong> Restart. </strong></li>
 	<li>When the computer reboots, you have to press <strong>F4</strong> to boot into Safe Mode.</li>
 	<li>After that, you have to press <strong>Windows key + R</strong> to open the <strong>Run box</strong>.</li>
 	<li>Type '<strong>rstrui.exe</strong>' and click <strong>OK</strong> button.

[caption id="attachment_3199" align="aligncenter" width="602"]<img class="size-full wp-image-3199" src="https://windowsjet.com/wp-content/uploads/2020/07/rstrui.exe_.png" alt="rstrui.exe" width="602" height="365" /> rstrui.exe[/caption]</li>
 	<li>You can see a window of '<strong>Restore system files and settings</strong>'. In that window, you have to select '<strong>Choose a different system restore point</strong>' and click the <strong>Next</strong> button.

[caption id="attachment_3195" align="aligncenter" width="895"]<img class="size-full wp-image-3195" src="https://windowsjet.com/wp-content/uploads/2020/07/Choose-a-different-restore-point.png" alt="Choose a different restore point" width="895" height="711" /> Choose a different restore point[/caption]</li>
 	<li>Then, you have to select the update that working fine and click the <strong>Next</strong> button.

[caption id="attachment_3198" align="aligncenter" width="898"]<img class="size-full wp-image-3198" src="https://windowsjet.com/wp-content/uploads/2020/07/Next.png" alt="Next" width="898" height="715" /> Next[/caption]</li>
 	<li>At last, tap on the <strong>Finish</strong> button.</li>
</ul>
<h2 id="3">Fix 2 - Disable Third-Party Antivirus:</h2>
<ul>
 	<li>You have to right-click on the antivirus software that is located on the <strong>Taskbar</strong>.</li>
 	<li>After that, you need to choose the <strong>Disable</strong> option.</li>
 	<li>In order to make sure that the antivirus is off, you have to use this shortcut <strong>Ctrl + Alt + Delete</strong> to open the <strong>Task Manager</strong> and check whether any antivirus software is running.</li>
</ul>
<h2 id="4">Fix 3 - Perform an SFC Scan:</h2>
<ul>
 	<li>Click on the <strong>Start</strong> button. In the search box, type <strong>'command prompt'</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>Copy and paste the below command in the Command Prompt and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="alignnone" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>Now, the System File Checker will perform a scan and repair the corrupted or damaged system files.</li>
</ul>
<h2 id="5">Fix 4 - Restore the Registry:</h2>
<ul>
 	<li>You have to make use of this keyboard shortcut <strong>Windows key + R </strong>to open the <strong>Run command</strong>.</li>
 	<li>Type '<strong>regedit.exe</strong>' and click<strong> OK</strong>.

[caption id="attachment_2839" align="aligncenter" width="570"]<img class="size-full wp-image-2839" src="https://windowsjet.com/wp-content/uploads/2020/06/dm1.png" alt="regedit" width="570" height="337" /> regedit[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>On the left pane, you have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskCache</code></p>

<ul>
 	<li>Right-click on <strong>TaskCache</strong> and choose the <strong>Export</strong> option.

[caption id="attachment_3197" align="aligncenter" width="1186"]<img class="size-full wp-image-3197" src="https://windowsjet.com/wp-content/uploads/2020/07/Export.png" alt="Export" width="1186" height="728" /> Export[/caption]</li>
 	<li>Enter the file name as 'backup' and save it.</li>
 	<li>After that, you have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Schedule\TaskCache\Tree\Microsoft\Windows</code></p>

<ul>
 	<li>Right-click on the <strong>Windows</strong> folder and choose the <strong>Delete</strong> option.

[caption id="attachment_3196" align="aligncenter" width="1190"]<img class="size-full wp-image-3196" src="https://windowsjet.com/wp-content/uploads/2020/07/Delete.png" alt="Delete" width="1190" height="724" /> Delete[/caption]</li>
 	<li>After that, you have to close all the opened windows and restart your computer.</li>
</ul>
<h2 id="6">Closure:</h2>
We hope that the above solutions helped you to fix <strong>Windows Backup and Restore Error 0x800700b7</strong>. It is not difficult to fix the error as the methods above let you get rid of the error easily. Feel free to leave your <strong>valuable comments</strong> about this article. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-update-error-80243004-3-easy-fixes-3118/" target="_blank" rel="noopener noreferrer"><strong>Fix Windows Update Error 80243004!! (*3 Easy Fixes*)</strong></a></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-boot-error-0xc000000e-4-quick-solutions-3010/" target="_blank" rel="noopener noreferrer">How to Fix Boot Error 0xc000000e? (*4 Quick Solutions*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/quick-solutions-fix-windows-update-error-code-0x80070490-3093/" target="_blank" rel="noopener noreferrer">{Quick Solutions} Fix Windows Update Error Code 0x80070490!!</a></strong></li>
</ul>