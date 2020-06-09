---
ID: 2553
post_title: 'Fix Windows 10 Installation Error Code 80240020 &#8211; 2 Easy Methods!!'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/fix-windows-10-installation-error-code-80240020-2-easy-methods-2553/
published: true
post_date: 2020-06-09 05:11:14
---
<strong><span class="dropcap dropcap1">f</span></strong><strong>ix Windows 10 Installation Error Code 80240020: </strong>If you are getting the error code 80240020 while updating to Windows 10 then it indicates that there is something wrong with your system. This kind of error appears due to overloaded Windows servers. Luckily, we are here to provide the best methods to <strong>Fix Windows 10 Installation Error Code 80240020</strong><strong>.</strong>
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Method 1: Delete All Content in Download Folder</a></strong></li>
 	<li><strong><a href="#2">Method 2: Modify Registry Key</a></strong></li>
 	<li><strong><a href="#3">Conclusion</a></strong></li>
</ul>
<h2 id="1">Method 1: Delete All Content in Download Folder</h2>
<ul>
 	<li>You just navigate to the following path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">C:\Windows\SoftwareDistribution\Download</code></p>

<ul>
 	<li>Then, you have to delete all content in the <strong>Download</strong> folder. Make sure that you don't delete the Download folder.

[caption id="attachment_2561" align="alignnone" width="1007"]<img class="size-full wp-image-2561" src="https://windowsjet.com/wp-content/uploads/2020/06/ie1.png" alt="Download folder" width="1007" height="596" /> Download folder[/caption]</li>
 	<li>Go to the <strong>Start</strong> menu. In the search box, you have to type <strong>'command prompt'</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>You just have to copy and paste the below command on the command prompt and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">wuauclt.exe /updatenow</code></p>


[caption id="attachment_2566" align="alignnone" width="664"]<img class="size-full wp-image-2566" src="https://windowsjet.com/wp-content/uploads/2020/06/ie2.png" alt="Command Prompt" width="664" height="398" /> Command Prompt[/caption]
<ul>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>Then, you have to click on <strong>Update &amp; Security</strong>.<img class="size-full wp-image-2487" src="https://windowsjet.com/wp-content/uploads/2020/06/ue1.png" alt="Update &amp; Security" width="814" height="452" /></li>
 	<li>It will open the <strong>Windows Update</strong> settings page. Now, your Windows 10 should start downloading again.</li>
 	<li>Once the download gets completed, you should restart your system.</li>
 	<li>After that, you will see a window that shows your upgrade is ready to install. Click <strong>Start the upgrade now</strong> button. Follow the on-screen instructions of the installation wizard.</li>
 	<li>You have to wait until the upgrade process gets done.</li>
</ul>
<h2 id="2">Method 2: Modify Registry Key</h2>
If the first method does not fix the error, you have to follow this method.
<ul>
 	<li>Using this shortcut <strong>Windows key + R</strong>, you can open the <strong>Run command</strong>.</li>
 	<li>Type <strong>regedit.exe </strong>and click<strong> OK</strong>.

[caption id="attachment_2413" align="alignnone" width="426"]<img class="size-full wp-image-2413" src="https://windowsjet.com/wp-content/uploads/2020/06/ec1.png" alt="regedit.exe" width="426" height="231" /> regedit.exe[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>You have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\OSUpgrade</code></p>

<ul>
 	<li>If you don't find the <strong>OSUpgrade</strong> folder, right-click on <strong>WindowsUpdate</strong> and choose <strong>New</strong> and then click on <strong>Key</strong>. After that, you have to name the key as OSUpgrade.</li>
 	<li>Right-click inside OSUpgrade and choose <strong>New</strong> and then choose <strong>DWORD (32-bit) Value</strong>.</li>
 	<li>Next, you have to name the key as <strong>AllowOSUpgrade</strong> and double-click on it and set its value to <strong>0x00000001. </strong></li>
 	<li>Then, close the Registry Editor and reboot your system.</li>
 	<li>After that, try to upgrade your PC.</li>
</ul>
<h2 id="3">Conclusion:</h2>
We hope that after following the above two methods installation error 80240020 gets fixed. You don't require any technical skills to <strong>Fix Windows 10 Installation Error Code 80240020</strong><strong> </strong>as the solutions given above are simple to execute. Kindly share your <strong>valuable comments</strong> in the below box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.