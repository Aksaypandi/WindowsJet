---
ID: 3106
post_title: 'Fix Windows 10 Update Error 0x8009000F-0x90002!! [Easy Ways]'
author: Preethi Agarwal
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/fix-windows-10-update-error-0x8009000f-0x90002-easy-ways-3106/
published: true
post_date: 2020-06-30 16:10:14
---
<strong><span class="dropcap dropcap1">F</span>ix Windows 10 Update Error 0x8009000F-0x90002: </strong>This error appears when users are trying to run the <strong>Media Creation Tool</strong> in order to<strong> upgrade their PC</strong> from an earlier version of<strong> Windows to Windows 10.</strong> In this article, we silhouette <strong>How to fix Windows 10 Update Error 0x8009000F-0x90002</strong> in some different ways.
<h2>Table of Contents:</h2>
<ul>
 	<li><a href="#1"><strong>Causes</strong></a></li>
 	<li><a href="#2"><strong>Fix Windows 10 Update Error 0x8009000F-0x90002</strong></a></li>
 	<li><a href="#3"><strong>Closure</strong></a></li>
</ul>
<h2 id="1">Causes:</h2>
<ul>
 	<li>This error may<strong> damage update components</strong> and malfunctioning the Windows Update system.</li>
 	<li>It doesn't allow the user to install<strong> new updates or to upgrade</strong> their PC to a new version of Windows.</li>
 	<li>It goes without saying that <strong>system updates</strong> are an obligatory part of a system’s maintenance.</li>
</ul>
<h2 id="2">Fix Windows 10 Update Error 0x8009000F-0x90002:</h2>
<ul>
 	<li><a href="#4"><strong>Restart Your Windows Update Components</strong></a></li>
 	<li><a href="#5"><strong>Upgrade using Windows Update</strong></a></li>
 	<li><a href="#6"><strong>Install the Latest Version of DirectX</strong></a></li>
</ul>
<h2 id="4">Restart Your Windows Update Components:</h2>
<ol>
 	<li>Go to the <strong>start</strong> <strong>menu</strong>.</li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Right-click</strong> on the command prompt and select <strong>Run as Administrator</strong> option.

[caption id="attachment_2803" align="aligncenter" width="476"]<img class="size-full wp-image-2803" src="https://windowsjet.com/wp-content/uploads/2020/06/Screenshot_1-2.png" alt="Start Menu" width="476" height="769" /> Start Menu[/caption]</li>
 	<li>Now, <strong>type</strong> the following commands in your Command Prompt window.</li>
 	<li>Press <strong>Enter</strong> after each of the commands.
<pre><code>net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc</code></pre>
</li>
 	<li>To <strong>rename</strong> the software distribution folders backup copies.</li>
 	<li><strong>Copy and Paste</strong> the following commands.</li>
 	<li>Press <strong>Enter</strong> after each of the commands.
<pre><code>Ren %systemroot%\SoftwareDistribution SoftwareDistribution.bak
Ren %systemroot%\system32\catroot2 catroot2.bak</code></pre>
</li>
 	<li>Now, to <strong>restart</strong> Windows Update components <strong>type</strong> the following commands.</li>
 	<li>Press <strong>Enter</strong> after each of the commands.
<pre><code>net start appidsvc
net start cryptsvc
net start bits
net start wuauserv</code></pre>
</li>
 	<li>Now, <strong>close </strong>the Command Prompt window and <strong>reboot your PC.</strong></li>
</ol>
<h2 id="5">Upgrade using Windows Update:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + R</strong> to open the Run command dialog box.</li>
 	<li>Type <strong>regedit</strong> in the given space box of <strong>Open</strong> and click <strong>OK</strong>.

[caption id="attachment_3126" align="aligncenter" width="443"]<img class="size-full wp-image-3126" src="https://windowsjet.com/wp-content/uploads/2020/06/explorer_rdZOC5HM7m.png" alt="Run command" width="443" height="255" /> Run command[/caption]</li>
 	<li>After this, Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <strong>Command Prompt.</strong></li>
 	<li><strong>Right-click</strong> on the command prompt and select <strong>Run as Administrator</strong> option.

[caption id="attachment_2803" align="aligncenter" width="476"]<img class="size-full wp-image-2803" src="https://windowsjet.com/wp-content/uploads/2020/06/Screenshot_1-2.png" alt="Start Menu" width="476" height="769" /> Start Menu[/caption]</li>
 	<li>Now, in the <strong>Windows Registry</strong> window go to the following path.
<pre>Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\OSUpgrade</pre>
</li>
 	<li>Click on <strong>OSUpgrade</strong> and<strong> right-click</strong> on the empty space.</li>
 	<li>Select <strong>New</strong> and<strong><strong> DWORD (32-bit) value.</strong></strong>

[caption id="attachment_3125" align="aligncenter" width="994"]<img class="size-full wp-image-3125" src="https://windowsjet.com/wp-content/uploads/2020/06/regedit_Lgm3PBGjJn.png" alt="New" width="994" height="739" /> New[/caption]</li>
 	<li>Give the <strong>Name</strong> for the new DWORD value AllowOSUpgrade.

[caption id="attachment_3124" align="aligncenter" width="984"]<img class="size-full wp-image-3124" src="https://windowsjet.com/wp-content/uploads/2020/06/regedit_GxoNPvPxvN.png" alt="Give Name" width="984" height="728" /> Give Name[/caption]</li>
 	<li>After that, <strong>double-click</strong> on the AllowOSUpgrade value and change its value to <strong><strong>1.</strong></strong>

[caption id="attachment_3123" align="aligncenter" width="428"]<img class="size-full wp-image-3123" src="https://windowsjet.com/wp-content/uploads/2020/06/regedit_ZTxDsNNVLf.png" alt="Value" width="428" height="228" /> Value[/caption]</li>
 	<li>Click on <strong>OK</strong> and <strong>close</strong> the Command Prompt window.</li>
 	<li>Once you complete the above steps, <strong>restart your PC.</strong></li>
</ol>
<h2 id="6">Install the Latest Version of DirectX:</h2>
<ol>
 	<li>Download the <a href="https://www.microsoft.com/en-us/download/details.aspx?id=35"><strong>DirectX End-User Runtime Web Installer</strong></a> here.</li>
 	<li>Now, <strong>follow</strong> the instructions which appear on screen to download.

[caption id="attachment_3122" align="aligncenter" width="616"]<img class="size-full wp-image-3122" src="https://windowsjet.com/wp-content/uploads/2020/06/chrome_h6QxiYDSDE.png" alt="DirectX End-User Runtime Web Installer" width="616" height="470" /> DirectX End-User Runtime Web Installer[/caption]</li>
 	<li><strong>Restart</strong> your computer and check to see if DirectX was installed successfully on your computer.</li>
 	<li>That' all, now <strong>check</strong> the problem has solved or not.</li>
</ol>
<h2 id="3">Closure:</h2>
Hopefully, the above methods assisted you in<strong> How to fix Windows 10 Update Error 0x8009000F-0x90002.</strong> Try any one of the above fixes to resolve the error. Interested to know your <strong>feedback/comments</strong> in the below section.
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://windowsjet.com/how-to-fix-boot-error-0xc000000e-4-quick-solutions-3010/" rel="nofollow"><strong>Fix Boot Error 0xc000000e</strong></a></li>
 	<li><a href="https://windowsjet.com/how-to-download-offline-maps-in-windows-10-easy-way-1813/" rel="nofollow"><strong>Download Offline Maps in Windows 10</strong></a></li>
 	<li><a href="https://windowsjet.com/how-to-install-xps-viewer-in-windows-10-quick-method-1771/" rel="nofollow"><strong>Install XPS Viewer in Windows 10</strong></a></li>
 	<li><a href="https://windowsjet.com/how-to-fix-windows-10-upgrade-error-code-0x80070070-2707/" rel="nofollow"><strong>Fix Windows 10 Upgrade Error Code 0x80070070</strong></a></li>
 	<li><a href="https://windowsjet.com/quick-solutions-fix-windows-update-error-code-0x80070490-3093/" rel="nofollow"><strong>Fix Windows Update Error code 0x80070490-3093</strong></a></li>
</ul>