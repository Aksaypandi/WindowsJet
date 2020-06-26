---
ID: 3010
post_title: 'How to Fix Boot Error 0xc000000e? (*4 Quick Solutions*)'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-fix-boot-error-0xc000000e-4-quick-solutions-3010/
published: true
post_date: 2020-06-26 07:01:08
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Boot Error 0xc000000e: </strong>If you are receiving an error 0xc000000e, you must be noticed a black screen window. There are various reasons for this error and there are several solutions. Let's look out the causes of this error and some simple solutions to <strong>Fix Boot Error 0xc000000e </strong>in Windows 10.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Reasons for Boot Error 0xc000000e</a></strong></li>
 	<li><strong><a href="#2">Rebuild Boot Configuration Data</a></strong></li>
 	<li><strong><a href="#3">Check Physical Device Connections</a></strong></li>
 	<li><strong><a href="#4">Run Windows Startup Repair</a></strong></li>
 	<li><strong><a href="#5">Mark Boot Disk as Online</a></strong></li>
 	<li><strong><a href="#6">Closure</a></strong></li>
</ul>
<h2 id="1">Reasons for Boot Error 0xc000000e:</h2>
<ul>
 	<li>Corrupted or damaged BCD.</li>
 	<li>The file winload.exe is not accessible.</li>
 	<li>Incorrect BIOS configuration.</li>
 	<li>The boot disk is marked as offline.</li>
</ul>
<h2 id="2">Fix 1 - Rebuild Boot Configuration Data:</h2>
Boot Configuration Data (BCD) includes the boot configuration parameters regarding how to start Windows OS. Your Windows 10 PC will fail to boot if the configuration file is corrupted and so it will display the error 0xc000000e. In order to fix this error, you need to rebuild BCD on your system.
<ul>
 	<li>First, you have to create a bootable USB drive from ISO for Windows 10. Then, proceed to follow the below steps.</li>
 	<li>Once your boot your PC from the USB medium, you have to click <strong>Next</strong>.</li>
 	<li>On the next screen, you have to click the <strong>Repair your computer</strong>.</li>
 	<li>Next, you have to click on <strong>Troubleshoot -&gt; Advanced options -&gt; Command Prompt.</strong></li>
 	<li>Now, in the Command Prompt window, you have to type the below command and hit <strong>Enter.</strong></li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /rebuildbcd</code></p>

<ul>
 	<li>Next, you have to press '<strong>Y</strong>' to let it boot from the list.</li>
 	<li>After that, you have to run the following commands successively and hit <strong>Enter</strong> after each command.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /fixmbr</code></p>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">bootrec /fixboot</code></p>

<h2 id="3">Fix 2 - Check Physical Device Connections:</h2>
<ul>
 	<li>Once you receive the error code 0xc000000e, you have to make sure if there any external devices connected to your computer.</li>
 	<li>There are times that the connected external device will take higher boot priority that of the hard disk due to the configuration of the UEFI or BIOS.</li>
 	<li>Therefore, you have to check the devices such as external USB storage, CDs, DVDs, pen drives, etc.</li>
</ul>
<h2 id="4">Fix 3 - Run Windows Startup Repair:</h2>
<ul>
 	<li>Boot your system from the USB medium, you have to click <strong>Next</strong>.</li>
 	<li>On the next screen, you have to click the <strong>Repair your computer</strong>.</li>
 	<li>Next, you have to click on <strong>Troubleshoot -&gt; Advanced options -&gt; Startup Repair.</strong></li>
 	<li>Now, your Windows will start to diagnose your PC automatically.</li>
 	<li>Once the process completes, your system will restart automatically and check whether the error gets fixed.</li>
</ul>
<h2 id="5">Fix 4 - Mark Boot Disk as Online:</h2>
<ul>
 	<li>At first, you have to boot your system from the USB medium, you have to click <strong>Next -&gt; Repair your computer. </strong></li>
 	<li>Then, you have to click on <strong>Troubleshoot -&gt; Advanced options -&gt; Command Prompt.</strong></li>
 	<li>Type the below command and hit <strong>Enter.</strong></li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">diskpart</code></p>

<ul>
 	<li>To list all the disks on your computer, you have to run the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">list disk</code></p>

<ul>
 	<li>You can see the list of disks like Disk 0, Disk 1, etc. If the disk that contains OS shows offline means, you have to make that disk as online.</li>
 	<li>Execute the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">select disk 0</code></p>

<ul>
 	<li>Make sure to replace '0' with your required disk.</li>
 	<li>After that, you have to run the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">online disk</code></p>

<ul>
 	<li>To leave diskpart, you have to execute the following command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">exit</code></p>

<ul>
 	<li>Close the Command Prompt window and reboot your system.</li>
</ul>
<h2 id="6">Closure:</h2>
We hope that the above solutions helped you to <strong>Fix Boot Error 0xc000000e</strong> in Windows 10<strong>. </strong>It is not difficult to fix the error as the methods above let you get rid of the error easily. Feel free to leave your <strong>valuable comments</strong> about this article. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/5-ways-fix-error-code-0x80070652-on-windows-10-2929/" target="_blank" rel="noopener noreferrer">{*5 Ways*} Fix Error Code 0x80070652 on Windows 10!!</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/4-quick-methods-to-fix-windows-update-error-code-c1900107-2600/" target="_blank" rel="noopener noreferrer">(*4 Quick Methods*) to Fix Windows Update Error Code C1900107!!</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-update-error-0x80070543-5-ways-2953/" target="_blank" rel="noopener noreferrer">Fix Windows Update Error 0x80070543!! [5 Ways]</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/6-quick-solutions-fix-windows-installer-error-code-2755-2870/" target="_blank" rel="noopener noreferrer">Fix Windows Installer Error Code 2755!! (*6 Quick Solutions*)</a></strong></li>
</ul>