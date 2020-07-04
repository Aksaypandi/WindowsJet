---
ID: 3294
post_title: '{3 Ways} To Fix Windows Store Error 0x8024600e on Windows!!'
author: Preethi Agarwal
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/3-ways-to-fix-windows-store-error-0x8024600e-on-windows-3294/
published: true
post_date: 2020-07-04 16:58:52
---
<strong><span class="dropcap dropcap1">F</span>ix Windows Store Error 0x8024600e on Windows: </strong>This error occurs when trying to <strong>install or update Microsoft Store</strong> and mainly prevails on <strong>Windows 8 and Windows 10.</strong> Read this tutorial to know some fixes to<strong> Fix Windows Store Error 0x8024600e on Windows.</strong>
<h2>Table of Contents:</h2>
<ul>
 	<li><a href="#1"><strong>Create the missing Temporary Internet Files</strong></a></li>
 	<li><a href="#2"><strong>Rename Software Distribution directory</strong></a></li>
 	<li><a href="#3"><strong>Perform clean boot</strong></a></li>
 	<li><a href="#4"><strong>Closure</strong></a></li>
</ul>
<h2 id="1">Create the missing Temporary Internet Files:</h2>
Follow the below steps to Create the missing Temporary Internet Files in simple steps.
<ol>
 	<li>Make use of the shortcut <strong>Windows</strong> <strong>+ R</strong> to open the <strong>Run</strong> <strong>command</strong> <strong>dialog box.</strong></li>
 	<li>Type <strong>regedit </strong>in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_3296" align="aligncenter" width="446"]<img class="size-full wp-image-3296" src="https://windowsjet.com/wp-content/uploads/2020/07/explorer_PqoKeohtge.png" alt="Run command" width="446" height="257" /> Run command[/caption]</li>
 	<li>In the <strong>Registry</strong> <strong>Editor</strong> window, Go to the <strong>following</strong> path on the left pane.
<pre><code>HKEY_CURRENT_USER\Software\Microsoft\
Windows\CurrentVersion\Explorer\User Shell Folders</code></pre>
</li>
 	<li>Then in the right pane, locate <strong>Cache</strong>.</li>
 	<li><strong>Double-click</strong> on the <strong>cache</strong> and the <strong>Edit</strong> <strong>string</strong> dialog box gets <strong>open</strong>.</li>
 	<li>In the Value data box type the <strong>following</strong> path.
<pre><code>%USERPROFILE%\AppData\Local\Microsoft\Windows\Temporary Internet Files Value</code></pre>
</li>
 	<li>Click <strong>OK</strong>.

[caption id="attachment_3295" align="aligncenter" width="968"]<img class="size-full wp-image-3295" src="https://windowsjet.com/wp-content/uploads/2020/07/regedit_Pmhie5v2UR.png" alt="Registry" width="968" height="728" /> Registry[/caption]</li>
 	<li>Finally, <strong>Reboot</strong> your PC.</li>
</ol>
<h2 id="2">Rename Software Distribution directory:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + X</strong> to open <strong>Power</strong> <strong>Menu</strong>.</li>
 	<li>Then select the<strong><strong> Command Prompt (Admin).</strong></strong>

[caption id="attachment_3297" align="aligncenter" width="290"]<img class="size-full wp-image-3297" src="https://windowsjet.com/wp-content/uploads/2020/07/ZhdcxKN24D.png" alt="Command Prompt" width="290" height="522" /> Command Prompt[/caption]</li>
 	<li>If the User Account Control message occurs, click <strong>Yes</strong> to proceed.</li>
 	<li>In the <strong>Command Prompt</strong> window, <strong>type</strong> the following commands.</li>
 	<li>Press <strong>Enter</strong> after each command.
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">net stop wuauserv</code></p>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">rename c:\windows\SoftwareDistribution softwaredistribution.old</code></p>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">net start wuauserv</code></p>
</li>
 	<li>That's all.</li>
</ol>
<h2 id="3">Perform a clean boot:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows</strong> <strong>+</strong> <strong>R</strong> to open the <strong>Run command dialog box.</strong></li>
 	<li>Type <strong>msconfig</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_3300" align="aligncenter" width="449"]<img class="size-full wp-image-3300" src="https://windowsjet.com/wp-content/uploads/2020/07/explorer_vGt2T45Fi5.png" alt="Run command" width="449" height="264" /> Run command[/caption]</li>
 	<li>In the <strong>System Configuration</strong> window, click the <strong>Services</strong> tab.</li>
 	<li><strong>Check</strong> <strong>in</strong> the Hide all <strong>Microsoft Services</strong> and click <strong>Disable</strong> <strong>all</strong> options.</li>
 	<li>Click <strong>OK</strong>.

[caption id="attachment_3299" align="aligncenter" width="654"]<img class="size-full wp-image-3299" src="https://windowsjet.com/wp-content/uploads/2020/07/msconfig_bgHnqutbQt.png" alt="Services" width="654" height="459" /> Services[/caption]</li>
 	<li>Now, press<strong> Ctrl + Alt + Delete</strong> to open <strong>Task</strong> <strong>Manager</strong>.</li>
 	<li>Click the <strong>Startup</strong> tab and <strong>disable</strong> programs that are set to boot during Windows startup.

[caption id="attachment_3298" align="aligncenter" width="795"]<img class="size-full wp-image-3298" src="https://windowsjet.com/wp-content/uploads/2020/07/Taskmgr_p06tqiB4OD.png" alt="Task Manager" width="795" height="730" /> Task Manager[/caption]</li>
 	<li>After completion of the above steps, <strong>restart</strong> your PC.</li>
</ol>
<h2 id="4">Closure:</h2>
Hoping that the above article helped you a lot to understand <strong>How to Fix Windows Store Error 0x8024600e on Windows</strong> in some different ways. Kindly, share your <strong>comments</strong> in the below comment section and drop your <strong>worthwhile</strong> <strong>feedback</strong>.
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowsjet.com/how-to-fix-windows-backup-and-restore-error-0x800700b7-3191/" rel="nofollow"><strong>How to fix Windows Backup and Restore Error 0x800700b7?</strong></a></li>
 	<li><a href="https://windowsjet.com/fix-windows-update-error-code-80200053-4-quick-fixes-3285/" rel="nofollow"><strong>Fix Windows Update Error Code 80200053</strong></a></li>
 	<li><a href="https://windowsjet.com/latest-how-to-fix-access-violation-error-0xc0000005-3261/" rel="nofollow"><strong>How to fix access violation error 0xc0000005?</strong></a></li>
 	<li><a href="https://windowsjet.com/how-to-use-screenshot-snipping-tool-in-windows-10-2266/" rel="nofollow"><strong>How to use Screenshot Snipping Tool in Windows 10?</strong></a></li>
 	<li><a href="https://windowsjet.com/how-to-open-printer-user-interface-in-windows-10-2012/" rel="nofollow"><strong>How to open Printer User Interface in Windows 10</strong></a></li>
</ul>