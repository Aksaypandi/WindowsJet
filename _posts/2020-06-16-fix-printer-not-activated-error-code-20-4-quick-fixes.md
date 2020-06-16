---
ID: 2653
post_title: 'Fix Printer not activated &#8211; Error Code 20!! (*4 Quick Fixes*)'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/fix-printer-not-activated-error-code-20-4-quick-fixes-2653/
published: true
post_date: 2020-06-16 05:21:23
---
<strong><span class="dropcap dropcap1">F</span></strong><strong>ix Printer not activated - Error Code 20: </strong>If you are getting the error message Printer not activated - Error Code 20, then it indicates that there is an issue while using QuickBooks application or upgrading from the earlier version of Windows. In this tutorial, you will learn how to <strong>Fix Printer not activated - Error Code 20</strong> on Windows OS by using simple and efficient solutions.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Key Points to Remember</a></strong></li>
 	<li><strong><a href="#2">Run Printer Troubleshooter</a></strong></li>
 	<li><strong><a href="#3">Use Registry Editor</a></strong></li>
 	<li><strong><a href="#4">Grant Permission using Powershell</a></strong></li>
 	<li><strong><a href="#5">Reinstall QuickBooks</a></strong></li>
 	<li><strong><a href="#6">Summary</a></strong></li>
</ul>
<h2 id="1">Key Points to Remember:</h2>
<ul>
 	<li>Before following any one of the solutions below, you have to make sure that your computer and printer connectivity is secure.</li>
 	<li>Further, you have to take a look at Drivers, Printers, and Control Panel to assure that the right printer is selected.</li>
 	<li>After that, backup your registry and set a system restore point and then continue to follow the solutions.</li>
</ul>
<strong>To Backup Registry:</strong>
<ul>
 	<li>Use this shortcut <strong>Windows key + R</strong> to open the Run command.</li>
 	<li>After that, you have to type '<strong>regedit.exe</strong>' and click <strong>OK</strong>.</li>
 	<li>In the Registry Editor, you have to click <strong>File</strong> -&gt; <strong>Export</strong> -&gt; Mark <strong>Export range</strong> as <strong>All</strong> -&gt; Give any <strong>File name</strong> -&gt; <strong>Save</strong>.</li>
</ul>
<strong>To Create a System Restore Point:</strong>
<ul>
 	<li>Go to the <strong>Start</strong> menu. In the search box, type '<strong>restore point'</strong> and hit <strong>Enter</strong>.</li>
 	<li>Click the <strong>Configure</strong> button and make sure '<strong>Turn on system protection</strong>' is selected. If not, you have to select the option.</li>
 	<li>In the <strong>System Properties</strong> window, click the <strong>Create</strong> button.</li>
 	<li>You can type any description to identify your restore point and then click the <strong>Create</strong> button.</li>
</ul>
<h2 id="2">1) Run Printer Troubleshooter:</h2>
<ol>
 	<li>Click the <strong>Start</strong> button and type '<strong>troubleshoot</strong>' in the search box and hit <strong>Enter</strong>.

[caption id="attachment_2662" align="aligncenter" width="872"]<img class="size-full wp-image-2662" src="https://windowsjet.com/wp-content/uploads/2020/06/pa1.png" alt="Troubleshoot" width="872" height="668" /> Troubleshoot[/caption]</li>
 	<li>After that, you have to select <strong>Printer</strong> under the '<strong>Get up and running</strong>' section.</li>
 	<li>Then, click the <strong>Run the troubleshooter</strong> button.

[caption id="attachment_2663" align="aligncenter" width="851"]<img class="size-full wp-image-2663" src="https://windowsjet.com/wp-content/uploads/2020/06/pa2.png" alt="Printer - Run the troubleshooter" width="851" height="483" /> Printer - Run the troubleshooter[/caption]</li>
 	<li>You have to follow the on-screen instructions and let the Printer Troubleshooter run.</li>
 	<li>Restart your system and make sure that the error gets fixed.</li>
</ol>
<h2 id="3">2) Use Registry Editor:</h2>
<ul>
 	<li>Using this shortcut <strong>Windows key + R</strong>, you can open the <strong>Run command</strong>.</li>
 	<li>Type <strong>regedit.exe </strong>and click<strong> OK</strong>.

[caption id="attachment_2413" align="alignnone" width="426"]<img class="size-full wp-image-2413" src="https://windowsjet.com/wp-content/uploads/2020/06/ec1.png" alt="regedit.exe" width="426" height="231" /> regedit.exe[/caption]</li>
 	<li>It will open the <strong>Registry Editor</strong>.</li>
 	<li>You have to navigate to the below path.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">HKEY_CURRENT_CONFIG\Software</code></p>

<ul>
 	<li>Right-click on the <strong>Software </strong>folder and navigate to <b><b>Permissions.</b></b>

[caption id="attachment_2664" align="aligncenter" width="734"]<img class="size-full wp-image-2664" src="https://windowsjet.com/wp-content/uploads/2020/06/pa3.png" alt="Permissions" width="734" height="424" /> Permissions[/caption]</li>
 	<li>Now, make sure that the administrator and users have Full Control checked. If not then you have to select them and click Apply followed by OK.</li>
 	<li>At last, you have to restart your PC to apply the changes and see if it fixes the issue.</li>
</ul>
<h2 id="4">3) Grant Permission using Powershell:</h2>
<ul>
 	<li>Go to the <strong>Start</strong> menu, search for <strong>‘powershell’ </strong>in the search box.</li>
 	<li>Right-click on the top result and choose <strong>Run as administrator</strong>.

[caption id="attachment_2665" align="aligncenter" width="871"]<img class="size-full wp-image-2665" src="https://windowsjet.com/wp-content/uploads/2020/06/pa4.png" alt="Powershell" width="871" height="668" /> Powershell[/caption]</li>
 	<li>Now, copy and paste the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white; font-size: 8px;">PowerShell.exe -NoProfile -NoLogo -NonInteractive -Command “$key = [Microsoft.Win32.Registry]::CurrentConfig.OpenSubKey(‘Software’,[Microsoft.Win32.RegistryKeyPermissionCheck]::ReadWriteSubTree,[System.Security.AccessControl.RegistryRights]::ChangePermissions); $acl =$key.GetAccessControl(); $rule = New-Object System.Security.AccessControl.RegistryAccessRule (‘Users’,’FullControl’,’ObjectInherit,ContainerInherit’,’None’,’Allow’); $acl.SetAccessRule($rule); $key.SetAccessControl($acl);”</code></p>

<ul>
 	<li>Reboot your system to save changes.</li>
</ul>
<h2 id="5">4) Reinstall QuickBooks:</h2>
<ol>
 	<li>You have to press <strong>Windows key + R</strong> and then type '<strong>appwiz.cpl</strong>' and hit <strong>Enter</strong>.

[caption id="attachment_2666" align="aligncenter" width="425"]<img class="size-full wp-image-2666" src="https://windowsjet.com/wp-content/uploads/2020/06/pa5.png" alt="appwiz.cpl" width="425" height="205" /> appwiz.cpl[/caption]</li>
 	<li>Now, you can see the list of programs installed in your system. In that list, you have to locate the <strong>QuickBooks</strong> and uninstall it.</li>
 	<li>After that, you have to download the QuickBooks from the official or reliable site.</li>
 	<li>Run the installer and follow the on-screen instructions to install the application.</li>
 	<li>Finally, restart your system.</li>
</ol>
<h2 id="6">Summary:</h2>
By following the solutions discussed in this article, you can <strong>Fix Printer not activated - Error Code 20 </strong>on Windows OS easily. We expect that these steps with clear-cut screenshots let you understand succinctly. If you have any queries, kindly share it in the below comment box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/fix-error-code-0x000314ce-pop-ups-simple-guide-2528/" target="_blank" rel="noopener noreferrer"><strong>Fix 'Error Code 0x000314CE' Pop-ups!! (*Simple Guide*)</strong></a></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-update-error-0x80080008-on-windows-3-quick-fixes-2478/" target="_blank" rel="noopener noreferrer">How to Fix Update Error 0x80080008 on Windows? (*3 Quick Fixes*)</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/solved-how-to-fix-windows-10-upgrade-error-code-0x80200056-2494/" target="_blank" rel="noopener noreferrer">[Solved] How to Fix Windows 10 Upgrade Error Code 0x80200056?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-alres409-dll-error-on-windows-5-simple-solutions-2613/" target="_blank" rel="noopener noreferrer">How to Fix ALRES409.dll Error on Windows? {5 Simple Solutions}</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/2-easy-methods-to-fix-call-of-duty-error-code-16384-2440/" target="_blank" rel="noopener noreferrer">FIX: Call of Duty Error Code 16384!! {2 Easy Methods}</a></strong></li>
</ul>