---
ID: 2911
post_title: >
  How to Fix Windows Defender Update
  Failure Error 0x80070643?
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-fix-windows-defender-update-failure-error-0x80070643-2911/
published: true
post_date: 2020-06-24 04:02:29
---
<strong><span class="dropcap dropcap1">F</span></strong><strong>ix Windows Defender Update Failure with an Error Code 0x80070643: </strong>When you try to update Windows Defender via Windows Update, you may get an error 0x80070643. This sort of error occurs due to some issues while installing Definition Update for Windows Defender. It means that there was a fatal error occurred during installation. The good news is that you can fix it. In this tutorial, we will help you to fix the <strong>Windows Defender Update Failure with an Error Code 0x80070643</strong><strong> </strong>by providing some simple solutions.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Use Antivirus Removal Tool</a></strong></li>
 	<li><strong><a href="#2">Run SFC Scan</a></strong></li>
 	<li><strong><a href="#3">Perform a Clean Boot</a></strong></li>
 	<li><strong><a href="#4">Update Windows Defender Manually</a></strong></li>
 	<li><strong><a href="#5">Wrap-up</a></strong></li>
</ul>
<h2 id="1">Solution 1 - Use Antivirus Removal Tool:</h2>
<ul>
 	<li>When you uninstall third-party antivirus software via Control Panel -&gt; Uninstall a Program, there may be a chance of some files remain uninstalled. This may be a cause for getting this error.</li>
 	<li>You can remove your antivirus software or any leftover files with the use of a particular antivirus removal tool that should be available on the official site of that tool. These kinds of tools are designed to remove the selected application along with all files and registry entries.</li>
</ul>
<h2 id="2">Solution 2 - Run SFC Scan:</h2>
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
<h2 id="3">Solution 3 - Perform a Clean Boot:</h2>
<ul>
 	<li>You have to press <strong>Windows key + R</strong> and type '<strong>msconfig</strong>' and click the <strong>OK</strong> button or hit <strong>Enter</strong>.

[caption id="attachment_2913" align="aligncenter" width="609"]<img class="size-full wp-image-2913" src="https://windowsjet.com/wp-content/uploads/2020/06/wd1.png" alt="msconfig" width="609" height="377" /> msconfig[/caption]</li>
 	<li>Now, you can see the <strong>System Configuration</strong> window.</li>
 	<li>Go to Services tab and select the check-box of '<strong>Hide all Microsoft services</strong>'. Then, you have to click the <strong>Disable all</strong> button.

[caption id="attachment_2914" align="aligncenter" width="913"]<img class="size-full wp-image-2914" src="https://windowsjet.com/wp-content/uploads/2020/06/wd2.png" alt="Hide all Microsoft services" width="913" height="601" /> Hide all Microsoft services[/caption]</li>
 	<li>After that, you have to click the <strong>Startup</strong> tab and click the link <strong>Open Task Manager</strong>.

[caption id="attachment_2915" align="aligncenter" width="901"]<img class="size-full wp-image-2915" src="https://windowsjet.com/wp-content/uploads/2020/06/wd3.png" alt="Open Task Manager" width="901" height="601" /> Open Task Manager[/caption]</li>
 	<li>You can see a list of startup applications. You have to right-click on each item and choose <strong>Disable</strong> option.

[caption id="attachment_2917" align="aligncenter" width="1000"]<img class="size-full wp-image-2917" src="https://windowsjet.com/wp-content/uploads/2020/06/wd4.png" alt="Disable" width="1000" height="890" /> Disable[/caption]</li>
 	<li>Once you disable all applications, you have to close the Task Manager.</li>
 	<li>Then, you have to click <strong>Apply</strong> and <strong>OK</strong> in the System Configuration window.

[caption id="attachment_2918" align="aligncenter" width="911"]<img class="size-full wp-image-2918" src="https://windowsjet.com/wp-content/uploads/2020/06/wd5.png" alt="Apply and OK" width="911" height="608" /> Apply and OK[/caption]</li>
 	<li>Finally, you have to restart your system to apply the changes.</li>
</ul>
<h2 id="4">Solution 4 - Update Windows Defender Manually:</h2>
<ul>
 	<li>You just visit Microsoft's official site to <a href="https://www.microsoft.com/en-us/wdsi/defenderupdates"><strong>download Windows Defender Updates</strong></a>.</li>
 	<li>Check the update file for Windows Defender that matches your OS and then download it.</li>
 	<li>Once the file gets downloaded, you have to open and install it in your system.</li>
 	<li>After that, you have to restart your PC and then run Windows Update to check if the error gets fixed.</li>
</ul>
<h2 id="5">Wrap-up:</h2>
We hope that the above solutions guided you to fix the <strong>Windows Defender Update Failure with an Error Code 0x80070643 </strong>easily. Follow any one of the solutions to fix the error and then run the update of Windows Defender. If you found this article helpful, share your comments in the below section. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/solved-how-to-fix-windows-10-upgrade-error-code-0x80200056-2494/" target="_blank" rel="noopener noreferrer">[Solved] How to Fix Windows 10 Upgrade Error Code 0x80200056?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-windows-error-code-0x80070057-simple-solutions-2396/" target="_blank" rel="noopener noreferrer">How to Fix Windows Error Code 0x80070057? { Simple Solutions}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-error-code-0x000314ce-pop-ups-simple-guide-2528/" target="_blank" rel="noopener noreferrer">Fix 'Error Code 0x000314CE' Pop-ups!! (*Simple Guide*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-onenote-error-code-0xe00015e0-on-windows-10-easy-fixes-2622/" target="_blank" rel="noopener noreferrer">Fix OneNote Error Code 0xE00015E0 on Windows 10!! (Easy Fixes)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-device-manager-error-code-41-5-easy-methods-2829/" target="_blank" rel="noopener noreferrer">How to Fix Device Manager Error Code 41? (*5 Easy Methods*)</a></strong></li>
</ul>