---
ID: 2454
post_title: >
  How to Quickly Fix the BSOD Error
  0Xc000021a on Windows 10?
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-quickly-fix-the-bsod-error-0xc000021a-on-windows-10-2454/
published: true
post_date: 2020-06-04 10:14:46
---
<strong><span class="dropcap dropcap1">F</span></strong><strong>ix Error 0Xc000021A</strong><strong>: </strong>A common <strong>Blue Screen of Death (BSOD)</strong> will appear with the error code <strong>0Xc000021A. </strong>This system crash can appear randomly and you will lose any unsaved data or work. In this article, you will learn how to <strong>Fix Error 0Xc000021A on Windows 10.</strong>
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Causes of Error 0Xc000021A</a></strong></li>
 	<li><strong><a href="#2">Fix Corrupted Files</a></strong></li>
 	<li><strong><a href="#3">Disable Driver Signature Enforcement</a></strong></li>
 	<li><strong><a href="#4">Run System File Checker Scan</a></strong></li>
 	<li><strong><a href="#5">Verdict</a></strong></li>
</ul>
<h2 id="1">Causes of Error 0Xc000021A:</h2>
<ul>
 	<li><b>csrss.exe - </b>This file manages the graphical instruction of Windows PC and it is the core OS file.</li>
 	<li><b>winlogon.exe</b> – As the name of the file represents, this file handles the login and logout operations inside Windows.</li>
</ul>
If the above two files have been corrupted, damaged, deleted, or replaced by a 3rd party software, you will get this error.
<h2 id="2">Method 1 - Fix Corrupted Files:</h2>
<ol>
 	<li>First, you have to insert your Windows 10 DVD into your device and boot to the DVD. (If you don't have the DVD drive for Win10, you can download the ISO file from Microsoft.com and make a bootable USB flash drive.)</li>
 	<li>Then, you have to click on <strong>Troubleshoot</strong>.</li>
 	<li>After that, click on<strong> Advanced options</strong>.</li>
 	<li>You have to choose <strong>Command Prompt</strong>.</li>
 	<li>In the Command Prompt window, you have to type the below command and hit <strong>Enter</strong>.</li>
 	<li>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">chkdsk C: /f /r</code></p>
</li>
 	<li>The command chkdsk (Check Desk) will perform a check on your system. It will fix errors (/f) and locates &amp; recovers (/r) bad sectors.</li>
 	<li>If you get a prompt to press y/n, you have to press 'y' and hit Enter.</li>
 	<li>Restart your computer and it will boot correctly now.</li>
</ol>
<h2 id="3">Method 2 - Disable Driver Signature Enforcement:</h2>
<ol>
 	<li>You have to restart your Windows system by holding the <strong>Shift</strong> key and select the <strong>Restart</strong> option.</li>
 	<li>Now, you can see the screen that shows <strong>Choose an Option</strong>. Here, you have to select <strong>Troubleshoot</strong>.</li>
 	<li>Then, you have to choose <strong>Advanced options</strong>.</li>
 	<li>In the next window, you have to select <strong>Startup Settings</strong>.</li>
 	<li>You can see the screen of Startup Settings. You have to press <strong>F7</strong> for <strong>Disable driver signature enforcement. </strong></li>
 	<li>After that, your computer will restart. Monitor the situation and check if the BSOD 0Xc000021a is resolved.</li>
</ol>
<h2 id="4">Method 3 - Run System File Checker Scan:</h2>
<ol>
 	<li>You just go to the search box and type <strong>'command prompt'</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type <strong>'sfc /scannow'</strong> and hit <strong>Enter</strong>.</li>
 	<li>Now the System File Checker will perform a scan and repair the damaged or corrupted system files.</li>
 	<li>Once the scan gets completed, restart your device.</li>
</ol>
<h2 id="5">Verdict:</h2>
Hopefully, the above three methods assisted you to <strong>Fix Error 0Xc000021A on Windows 10. </strong>Try any one of the above fixes to resolve the error on your Windows PC. Interested to know your <strong>feedback/comments</strong> in the below section. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.