---
ID: 3004
post_title: 'Easily Fix Your PC needs to be repaired. Error code: 0xc000014c!!'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/easily-fix-your-pc-needs-to-be-repaired-error-code-0xc000014c-3004/
published: true
post_date: 2020-06-26 02:59:55
---
<strong><span class="dropcap dropcap1">F</span></strong><strong>ix Your PC needs to be repaired. Error code: 0xc000014c: </strong>The error code 0xc000014c is a common issue and can occur in Windows 10, 8, 8.1, and 7. This BSOD error locks your computer completely and until the error gets fixed, your PC will not boot. Further, all unsaved will be deleted. So, in this tutorial, we will look over the methods on how to fix <strong>Your PC needs to be repaired. Error code: 0xc000014c.</strong>
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Reasons behind this error</a></strong></li>
 	<li><strong><a href="#2">Remove the Newly Installed Hardware</a></strong></li>
 	<li><strong><a href="#3">Repairing Damaged BCD</a></strong></li>
 	<li><strong><a href="#4">Run SFC Tool to Fix Corrupted System Files</a></strong></li>
 	<li><strong><a href="#5">Check for Bad Sectors using 'chkdsk' command</a></strong></li>
 	<li><strong><a href="#6">Summary</a></strong></li>
</ul>
<h2 id="1">Reasons behind this error:</h2>
<ul>
 	<li>Recently installed hardware</li>
 	<li>Bad sectors on the hard drive</li>
 	<li>Missing or corrupted BCD</li>
 	<li>Corrupted or inconsistency of the system files</li>
</ul>
<h2 id="2">1) Remove the Newly Installed Hardware:</h2>
The error may be occurred due to recently installed hardware in your system. If the hardware is not compatible with your computer, then there is a possibility of getting this error. In such cases, you just remove the hardware and restart your PC to check whether the error gets fixed.
<h2 id="3">2) Repairing Damaged BCD:</h2>
<ul>
 	<li>Insert your Windows 10 Installation Media drive and boot the PC. (If you don't have the DVD drive for Win10, you can download the ISO file from Microsoft.com and make a bootable USB flash drive.)</li>
 	<li>Click on <strong>Repair your computer</strong>.</li>
 	<li>Next, you have to click on <strong>Troubleshoot</strong>.</li>
 	<li>Then, continue to tap on<strong> Advanced options</strong>.</li>
 	<li>After that, select the <strong>Command Prompt</strong>.</li>
 	<li>In the Command Prompt window, you have to type the below commands one by one and hit <strong>Enter </strong>for every command.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /fixmbr</code></p>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /fixboot</code></p>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /scanos</code></p>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /rebuildbcd </code></p>

<h2 id="4">3) Run SFC Tool to Fix Corrupted System Files:</h2>
<ul>
 	<li>Insert your Windows 10 Installation Media drive and boot the PC. (If you don't have the DVD drive for Win10, you can download the ISO file from Microsoft.com and make a bootable USB flash drive.)</li>
 	<li>Click on <strong>Repair your computer</strong>.</li>
 	<li>Next, you have to click on <strong>Troubleshoot -&gt; Advanced Options -&gt; Command Prompt.</strong></li>
 	<li>In the Command Prompt window, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="aligncenter" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>You have to wait until the process gets completed and then restart your PC.</li>
</ul>
<h2 id="5">4) Check for Bad Sectors using 'chkdsk' command:</h2>
<ul>
 	<li>You have to insert your Windows 10 Installation Media drive and boot the PC(If you don't have the DVD drive for Win10, you can download the ISO file from Microsoft.com and make a bootable USB flash drive.)</li>
 	<li>Now, you have to click on <strong>Repair your computer</strong>.</li>
 	<li>Next, you have to click on <strong>Troubleshoot</strong>.</li>
 	<li>Then, continue to tap on<strong> Advanced options</strong>.</li>
 	<li>After that, select the <strong>Command Prompt</strong>.</li>
 	<li>In the Command Prompt window, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">chkdsk C: /f /x /r</code></p>

<ul>
 	<li>The command chkdsk (Check Desk) will perform a check on your system. It will fix errors (/f), checks and repairs disk drive partition (x), and locates &amp; recovers (/r) bad sectors.</li>
 	<li>If you get a prompt to press y/n, you have to press 'y' and hit <strong>Enter</strong>.</li>
 	<li>Restart your computer and it will boot correctly now.</li>
</ul>
<h2 id="6">Summary:</h2>
By following the solutions discussed in this article, you can fix <strong>Your PC needs to be repaired. Error code: 0xc000014c</strong> easily. We expect that these clear-cut steps let you understand the method succinctly. If you have any queries, kindly share it in the below <strong>comment</strong> box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-update-error-0x80080008-on-windows-3-quick-fixes-2478/" target="_blank" rel="noopener noreferrer">How to Fix Update Error 0x80080008 on Windows? (*3 Quick Fixes*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-0xc0000221-error-5-quick-solutions-2921/" target="_blank" rel="noopener noreferrer">Fix Windows 0xC0000221 Error!! (*5 Quick Solutions*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-windows-10-upgrade-error-code-0x80070070-2707/" target="_blank" rel="noopener noreferrer">How to Fix Windows 10 Upgrade Error Code 0x80070070?</a></strong></li>
</ul>