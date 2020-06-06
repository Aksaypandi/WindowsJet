---
ID: 2514
post_title: >
  How to Fix Error Code 0xc7700112 on
  Windows PC?
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-fix-error-code-0xc7700112-on-windows-pc-2514/
published: true
post_date: 2020-06-06 05:13:00
---
<strong><span class="dropcap dropcap1">F</span></strong><strong>ix Error Code 0xc7700112: </strong>While upgrading Windows OS versions like 7, 8, 8.1, and 10, users often encounter an error with an error code 0xc7700112. Automatic upgrades by the user or Windows updates or Windows Update Assistant might end up with this error. In most of the cases, a media creation tool is used to upgrade Windows 10. It offers a direct 'Upgrade this PC' option so it often ends up with the error. So, in this tutorial, you will learn how to <strong>Fix Error Code 0xc7700112 </strong>and upgrade Windows 10 through other methods given below.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Update Drivers Manually</a></strong></li>
 	<li><strong><a href="#2">Remove Windows Setup Entries from BCD Store </a></strong></li>
 	<li><strong><a href="#3">Upgrading Methods to Avoid Errors</a></strong></li>
 	<li><strong><a href="#4">Summary</a></strong></li>
</ul>
<h2 id="1">Update Drivers Manually:</h2>
<ul>
 	<li>Users often forget to update their driver software when they upgrade to the latest OS that may lead to driver related issues.</li>
 	<li>If this is your case, you don't have to be concerned about it. This solution is considered to be effective but makes sure you get the right driver for your PC or else it may damage your computer.</li>
</ul>
<h2 id="2">Remove Windows Setup Entries from BCD Store:</h2>
<ul>
 	<li>Go to the <strong>Start</strong> menu. In the search box, you have to type <strong>'command prompt'</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>You just have to copy and paste the below command on the command prompt and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bcdedit /enum all</code></p>


[caption id="attachment_2526" align="alignnone" width="859"]<img class="size-full wp-image-2526" src="https://windowsjet.com/wp-content/uploads/2020/06/err1.png" alt="Command Prompt" width="859" height="491" /> Command Prompt[/caption]
<ul>
 	<li>Under each device option section, there is an identifier. These identifiers are leftovers from your previous installation. These identifiers may be the reason for not upgrading well. <span id="div-gpt-ad-thewindowsclub_com-medrectangle-3-0" class="ezoic-ad ezoic-adl ezfound" data-google-query-id="CIrV2pqt7OkCFUgnjwodC7MFGQ"></span></li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bcdedit /delete {Here key in the name of the first identifier}</code></p>

<ul>
 	<li>You have to repeat the above command for every device option identifier.</li>
 	<li>After that, you have to reboot your computer. Once your Windows is running properly, you have to again open the Command Prompt with admin privileges.</li>
 	<li>Then, again run the below command to check the entries have been removed.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bcdedit /enum all</code></p>

<h2 id="3">Upgrading Methods to Avoid Errors:</h2>
You have to download the Windows Media Creation tool no matter which methods you are following below. Go to Microsoft's official portal and download it.
<h3>Method 1: USB Flash Drive</h3>
<ol>
 	<li>Launch the downloaded <strong>Media Creation Tool</strong>.</li>
 	<li>Follow the on-screen instructions and agree on the terms and conditions.</li>
 	<li>Now, you will see two options that include <strong>Upgrade this PC </strong>and <strong>Create Installation Media for another PC</strong>. In these options, you have to choose the second one.</li>
 	<li>Then, proceed to select the edition, architecture, and language.</li>
 	<li>Now, you will be asked to choose either <strong>USB Flash Drive</strong> or <strong>ISO File</strong>. You have to opt for USB Flash Drive.</li>
 	<li>You have to plug your USB Drive and make sure that it has at least 8 GB of free space.</li>
 	<li>After that, you have to open the USB drive and click <strong>Next</strong>.</li>
 	<li>At last, Media Creation Tool will start to download Windows 10 upgrade on your USB drive so that you can make use of the drive for upgrading your system.</li>
</ol>
<h3>Method 2: ISO File</h3>
<ol>
 	<li>In this method, you have to repeat the above 1 to 4 steps.</li>
 	<li>Then, in step 5, you have to go with the selection of <strong>ISO File</strong>.</li>
 	<li>You have to wait until the download process gets completed.</li>
 	<li>Now, you have to plug your USB Drive and make sure that it has at least 8 GB of free space.</li>
 	<li>You have to right-click on the downloaded ISO file and choose <strong>MOUNT</strong>.</li>
 	<li>After that, click on the File Explorer in the Taskbar and then choose <strong>Open CD Drive</strong>.</li>
 	<li>Double-click on the <strong>Setup</strong> file and wait until the upgrade is done.</li>
</ol>
<h2 id="4">Summary:</h2>
By following the solutions discussed in this article, you can <strong>Fix Windows Error Code 0xc7700112 </strong>easily. We expect that these clear-cut steps let you understand the method succinctly. If you have any queries, kindly share it in the below comment box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/solved-how-to-fix-windows-10-upgrade-error-code-0x80200056-2494/" target="_blank" rel="noopener noreferrer">[Solved] How to Fix Windows 10 Upgrade Error Code 0x80200056?</a></strong></li>
</ul>