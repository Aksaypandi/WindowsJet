---
ID: 2953
post_title: 'Fix Windows Update Error 0x80070543!! [5 Ways]'
author: Preethi Agarwal
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/fix-windows-update-error-0x80070543-5-ways-2953/
published: true
post_date: 2020-06-25 17:18:08
---
<strong><span class="dropcap">F</span>ix Windows Update Error 0x80070543:</strong> It’s one of the <strong>Windows Update errors,</strong> meaning that it does not allow running any Windows updates until its causes will not be removed. In this article, we illustrate an outline of <strong>How to Fix Windows Update Error 0x80070543</strong> in some different ways.
<h2>Table of Contents:</h2>
<ul>
 	<li><a href="#1"><strong>What causes 0x80070543 error?</strong></a></li>
 	<li><a href="#2"><strong>Windows Update Troubleshooter - Run</strong></a></li>
 	<li><a href="#3"><strong>By using Component Services</strong></a></li>
 	<li><a href="#4"><strong>Use Deployment Image Servicing and Management</strong></a></li>
 	<li><a href="#5"><strong>Run System File Checker</strong></a></li>
 	<li><a href="#6"><strong>Windows Update Components - Reset</strong></a></li>
 	<li><a href="#7"><strong>Closure</strong></a></li>
</ul>
<h2 id="1">What causes 0x80070543 error?</h2>
<ul>
 	<li>This error may be caused by Windows system<strong> file damage.</strong></li>
 	<li>The <strong>corrupted</strong> system files entries can be a real threat to your computer.</li>
 	<li>An <strong>incomplete</strong> installation, an <strong>incomplete</strong> uninstall, <strong>improper</strong> deletion of applications or hardware.</li>
 	<li>It can also be caused if your computer is recovered from a <strong>virus or adware/spyware</strong> attack or by an <strong>improper</strong> <strong>shutdown</strong> of the computer.</li>
</ul>
<h2 id="2">Windows Update Troubleshooter - Run:</h2>
<ol>
 	<li>Go to the<strong> start menu.</strong></li>
 	<li>In the search column, type as <strong>Troubleshooting</strong>.</li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_2956" align="aligncenter" width="476"]<img class="size-full wp-image-2956" src="https://windowsjet.com/wp-content/uploads/2020/06/DfCe99UMt5.png" alt="Troubleshooting" width="476" height="761" /> Troubleshooting[/caption]</li>
 	<li>In the left pane of the window, click the <strong><strong>View all option.</strong></strong>

[caption id="attachment_2957" align="aligncenter" width="1027"]<img class="size-full wp-image-2957" src="https://windowsjet.com/wp-content/uploads/2020/06/explorer_Ps9KIgYZB2.png" alt="View all" width="1027" height="607" /> View all[/caption]</li>
 	<li>Find <strong>Windows Update</strong> and click on it.

[caption id="attachment_2959" align="aligncenter" width="1027"]<img class="size-full wp-image-2959" src="https://windowsjet.com/wp-content/uploads/2020/06/explorer_TJxawqdR0P.png" alt="Windows Update" width="1027" height="605" /> Windows Update[/caption]</li>
 	<li>Then, follow the <strong>setup</strong> to run the troubleshooter.

[caption id="attachment_2962" align="aligncenter" width="683"]<img class="size-full wp-image-2962" src="https://windowsjet.com/wp-content/uploads/2020/06/msdt_p0xCpfMRc0.png" alt="Troubleshoot" width="683" height="520" /> Troubleshoot[/caption]</li>
</ol>
<h2 id="3">By using Component Services:</h2>
<ol>
 	<li>Go to the <strong>start menu.</strong></li>
 	<li>In the search column, type as <strong>Component Services.</strong></li>
 	<li><strong>Tap</strong> it which appears at the top of the start menu.

[caption id="attachment_2958" align="aligncenter" width="490"]<img class="size-full wp-image-2958" src="https://windowsjet.com/wp-content/uploads/2020/06/explorer_slJ2oVWMpx.png" alt="Component Services" width="490" height="766" /> Component Services[/caption]</li>
 	<li>Locate <strong>Components</strong> <strong>Services</strong> and <strong>expand</strong> it in the <strong>console</strong> tree.</li>
 	<li>Now, find <strong>Computer</strong> and <strong>expand</strong> it.</li>
 	<li>Then, right-click on <strong>My Computer </strong>and select <strong>Properties</strong>.

[caption id="attachment_2961" align="aligncenter" width="1052"]<img class="size-full wp-image-2961" src="https://windowsjet.com/wp-content/uploads/2020/06/mmc_HFF7gUC3Ju.png" alt="Properties" width="1052" height="735" /> Properties[/caption]</li>
 	<li>Click on the <strong>Default Properties</strong> tab and Select <strong>Connect</strong> on the <strong>Default Authentication Level.</strong></li>
 	<li>In the list of <strong>Default Impersonation Level,</strong> select <strong>Identity </strong>and click <strong>OK</strong>.

[caption id="attachment_2960" align="aligncenter" width="490"]<img class="size-full wp-image-2960" src="https://windowsjet.com/wp-content/uploads/2020/06/mmc_1UBkfZtt13.png" alt="Default" width="490" height="684" /> Default[/caption]</li>
 	<li>Finally, click <strong>Yes </strong>and close <strong>Component Services console.</strong></li>
</ol>
<h2 id="4">Use Deployment Image Servicing and Management:</h2>
<ol>
 	<li>Make use of the shortcut <strong>Windows + X</strong> and select the <strong>Command Prompt (Admin) </strong>option.

[caption id="attachment_2963" align="aligncenter" width="305"]<img class="size-full wp-image-2963" src="https://windowsjet.com/wp-content/uploads/2020/06/QVFRIhoaaR.png" alt="Command Prompt (Admin)" width="305" height="524" /> Command Prompt (Admin)[/caption]</li>
 	<li>If you receive a UAC prompt, click <strong>Yes</strong> to continue.</li>
 	<li>Now, type the following command and press <strong>Enter</strong>.
<pre><code>DISM.exe /Online /Cleanup-image /Scanhealth</code></pre>
</li>
 	<li>Then, copy and paste the following command and press <strong>Enter</strong>.
<pre><code>DISM.exe /Online /Cleanup-image /Restorehealth </code></pre>
</li>
 	<li>Finally, close the<strong> Command Prompt</strong> window and <strong>reboot your PC.</strong></li>
</ol>
<h2 id="5">Run System File Checker:</h2>
<ol>
 	<li>If the previous ways did not help to fix the Windows Update error 0x80070543.</li>
 	<li>Then, try to run the <strong>System File Checker.</strong></li>
 	<li>Follow this <a href="http://support.microsoft.com/kb/929833"><strong>link</strong> </a>to download the System File Checker.</li>
</ol>
<h2 id="6">Windows Update Components - Reset:</h2>
<ol>
 	<li>To reset <strong>Windows Update Components</strong> to get rid of this Error.</li>
 	<li>This method should be<strong> performed carefully</strong> because it requires executing many commands on the registries.</li>
 	<li>Refer to this <a href="https://support.microsoft.com/en-us/kb/971058"><strong>link</strong> </a>to know about how to reset <strong>Windows Update Components.</strong></li>
</ol>
<h2 id="7">Closure:</h2>
<div id="download">We hope that this will help you to know <strong>How to Fix Windows Update Error 0x80070543.</strong> Kindly share your valuable comments in the below box.</div>
&nbsp;