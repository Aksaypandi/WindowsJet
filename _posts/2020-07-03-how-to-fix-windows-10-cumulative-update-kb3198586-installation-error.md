---
ID: 3289
post_title: >
  How to Fix Windows 10 Cumulative Update
  KB3198586 Installation Error?
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-fix-windows-10-cumulative-update-kb3198586-installation-error-3289/
published: true
post_date: 2020-07-03 15:07:55
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Windows 10 Cumulative Update KB3198586 Installation Error: </strong>When you try to install Cumulative Update KB3198586 in Windows 10, it may fail or bring some issues that include corrupted or missing files, BSOD errors, etc. You may face this sort of error for <strong>KB3200970</strong> and <strong>KB3198585</strong> updates. We will share here some easy methods to fix <strong>Windows 10 Cumulative Update KB3198586 Installation Error</strong><strong> </strong>on your own very quickly.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Run the Update Troubleshooter</a></strong></li>
 	<li><strong><a href="#2">Delete Cumulative Update Files</a></strong></li>
 	<li><strong><a href="#3">Run the SFC Scan</a></strong></li>
 	<li><strong><a href="#4">Using DISM Tool</a></strong></li>
 	<li><strong><a href="#5">Use System Restore in Safe Mode</a></strong></li>
 	<li><strong><a href="#6">Verdict</a></strong></li>
</ul>
<h2 id="1">1) Run the Update Troubleshooter:</h2>
<ul>
 	<li>First and foremost, you have to open the <strong>Settings</strong> through a keyboard shortcut <strong>Windows key + I</strong>.</li>
 	<li>In the Windows Settings, you have to click on the <strong>Update &amp; Security </strong>option.

[caption id="attachment_2863" align="aligncenter" width="1320"]<img class="size-full wp-image-2863" src="https://windowsjet.com/wp-content/uploads/2020/06/au6.png" alt="Update &amp; Security" width="1320" height="818" /> Update &amp; Security[/caption]</li>
 	<li>On the left side, you have to tap on the <strong>Troubleshoot</strong> option.

[caption id="attachment_2864" align="aligncenter" width="1320"]<img class="size-full wp-image-2864" src="https://windowsjet.com/wp-content/uploads/2020/06/au7.png" alt="Troubleshoot" width="1320" height="822" /> Troubleshoot[/caption]</li>
 	<li>Proceed to select <b>Windows Update </b>under '<strong>Get up and running</strong>' on the right side.

[caption id="attachment_2865" align="aligncenter" width="1319"]<img class="size-full wp-image-2865" src="https://windowsjet.com/wp-content/uploads/2020/06/au8.png" alt="Windows Update" width="1319" height="819" /> Windows Update[/caption]</li>
 	<li>Just click on <strong>Run the troubleshooter</strong> button.

[caption id="attachment_2866" align="aligncenter" width="1322"]<img class="size-full wp-image-2866" src="https://windowsjet.com/wp-content/uploads/2020/06/au9.png" alt="Run the troubleshooter" width="1322" height="821" /> Run the troubleshooter[/caption]</li>
 	<li>You have to follow the on-screen instructions to complete the troubleshooting process.</li>
 	<li>At last, try to update your PC to check whether the error gets fixed.</li>
</ul>
<h2 id="2">2) Delete Cumulative Update Files:</h2>
<ul>
 	<li>You just navigate to the following path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">C:\Windows\SoftwareDistribution\Download</code></p>

<ul>
 	<li>Then, you have to delete all content in the <strong>Download</strong> folder. It is important that you should not delete the <strong>Download</strong> folder itself.</li>
 	<li>You have to click '<strong>Yes</strong>' if prompted for administrator permission.</li>
 	<li>After that, try to reboot your system.</li>
 	<li>Go to <strong>Settings -&gt; Update &amp; Security -&gt;</strong> <strong>Windows Update</strong> <strong>-&gt;</strong> <strong>Check for Updates</strong>.</li>
 	<li>If you find the KB3198586 update on the list, then install it.</li>
</ul>
<h2 id="3">3) Run the SFC Scan:</h2>
<ul>
 	<li>Press the <strong>Windows key</strong> and type <strong>'cmd' </strong>in the search box. Then, press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>You have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="alignnone" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>Now, the System File Checker will perform a scan and repair the damaged or corrupted files of your system.</li>
 	<li>Once the scan gets completed, restart your system.</li>
</ul>
<h2 id="4">4) Using DISM Tool:</h2>
Follow the below steps to fix the error by using the Deployment Image Servicing and Management (DISM) tool.
<ul>
 	<li>Click the <strong>Start</strong> menu and type <strong>'cmd' </strong>in the search box. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">DISM.exe /Online /Cleanup-image /Restorehealth</code></p>

<ul>
 	<li>Run the below command and hit <strong>Enter</strong> if your Windows Update client is damaged or corrupted.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">DISM.exe /Online /Cleanup-Image /RestoreHealth /Source:C:\RepairSource\Windows /LimitAccess</code></p>

<h2 id="5">5) Use System Restore in Safe Mode:</h2>
<ul>
 	<li>You have to reboot your system in safe mode.</li>
 	<li>In order to restart your Windows system, you have to hold the <strong>Shift</strong> key and choose the <strong>Restart</strong> option.<strong> </strong></li>
 	<li>You have to press <strong>F8</strong> to boot into Safe Mode before seeing the Windows boot window.</li>
 	<li>After that, you have to press <strong>Windows key + R</strong> to open the <strong>Run box</strong>.</li>
 	<li>Type '<strong>rstrui.exe</strong>' and click <strong>OK</strong> button.</li>
</ul>
[caption id="attachment_3199" align="aligncenter" width="602"]<img class="size-full wp-image-3199" src="https://windowsjet.com/wp-content/uploads/2020/07/rstrui.exe_.png" alt="rstrui.exe" width="602" height="365" /> rstrui.exe[/caption]
<ul>
 	<li>You can see a window of '<strong>System Restore</strong>'. You have to click the <strong>Next</strong> button.

[caption id="attachment_3270" align="aligncenter" width="894"]<img class="size-full wp-image-3270" src="https://windowsjet.com/wp-content/uploads/2020/07/Next-2.png" alt="Next" width="894" height="709" /> Next[/caption]</li>
 	<li>Select the update that working fine and click the <strong>Next</strong> button.

[caption id="attachment_3266" align="aligncenter" width="897"]<img class="size-full wp-image-3266" src="https://windowsjet.com/wp-content/uploads/2020/07/Choose-update-and-Next.png" alt="Choose update and Next" width="897" height="711" /> Choose update and Next[/caption]</li>
 	<li>At last, tap on the <strong>Finish</strong> button.</li>
</ul>
<h2 id="6">Closure:</h2>
Hopefully, this article guided you to fix<strong> Windows 10 Cumulative Update KB3198586 Installation Error </strong>easily. You just follow the steps and get rid of this error on your system. Don't forget to share your <strong>comments/feedback</strong> in the below section. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-windows-update-error-0x80070543-5-ways-2953/" target="_blank" rel="noopener noreferrer"><strong>Fix Windows Update Error 0x80070543!! [5 Ways]</strong></a></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/latest-how-to-fix-access-violation-error-0xc0000005-3261/" target="_blank" rel="noopener noreferrer">[Latest] How to Fix Access Violation Error 0xC0000005?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-boot-error-0xc000000e-4-quick-solutions-3010/" target="_blank" rel="noopener noreferrer">How to Fix Boot Error 0xc000000e? (*4 Quick Solutions*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-the-server-stumbled-error-code-0x801901f7-2776/" target="_blank" rel="noopener noreferrer">How to Fix "The Server Stumbled" Error Code 0x801901F7?</a></strong></li>
</ul>