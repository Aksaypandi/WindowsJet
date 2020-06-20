---
ID: 2776
post_title: 'How to Fix &#8220;The Server Stumbled&#8221; Error Code 0x801901F7?'
author: Ankita Singh
post_excerpt: ""
layout: post
permalink: >
  https://windowsjet.com/how-to-fix-the-server-stumbled-error-code-0x801901f7-2776/
published: true
post_date: 2020-06-20 14:59:25
---
<strong><span class="dropcap dropcap1">F</span></strong><strong>ix "The Server Stumbled" Error Code 0x801901F7: </strong>Those who are using Windows OS will access Microsoft Store to download various applications. Sometimes, you may get "The Server Stumbled" Error Code 0x801901F7 while opening the Microsoft store. So, you cannot able to download any apps from the store. In this tutorial, you will learn how to <strong>Fix "The Server Stumbled" Error Code 0x801901F7 </strong>on Windows by using simple and efficient solutions.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">Reasons for getting Server Stumbled Error</a></strong></li>
 	<li><strong><a href="#2">Turn Off Proxy Server</a></strong></li>
 	<li><strong><a href="#3">Reset Store Cache</a></strong></li>
 	<li><strong><a href="#4">Delete DataStore File</a></strong></li>
 	<li><strong><a href="#5">Modify Windows Update Properties</a></strong></li>
 	<li><strong><a href="#6">Run System File Checker</a></strong></li>
 	<li><strong><a href="#7">Summary</a></strong></li>
</ul>
<h2 id="1">Reasons for getting Server Stumbled Error:</h2>
<ul>
 	<li>Corrupted registry files</li>
 	<li>Outdated driver, missing .DLL files</li>
 	<li>Virus infection</li>
 	<li>Incorrect configuration</li>
 	<li>Microsoft server overload.</li>
</ul>
<h2 id="2">1) Turn Off Proxy Server:</h2>
<ul>
 	<li>Use this shortcut <strong>Windows key + I</strong> to open the <strong>Settings</strong>.</li>
 	<li>After that, you have to click on the <strong>Network &amp; Internet</strong> option.

[caption id="attachment_2794" align="aligncenter" width="1492"]<img class="size-full wp-image-2794" src="https://windowsjet.com/wp-content/uploads/2020/06/ss1.png" alt="Network &amp; Internet" width="1492" height="829" /> Network &amp; Internet[/caption]</li>
 	<li>In the left pane, you have to choose the <strong>Proxy</strong>.

[caption id="attachment_2795" align="aligncenter" width="1485"]<img class="size-full wp-image-2795" src="https://windowsjet.com/wp-content/uploads/2020/06/ss2.png" alt="Proxy" width="1485" height="830" /> Proxy[/caption]</li>
 	<li>Now, you have to scroll down and <strong>turn off the slider</strong> under <strong>Use a proxy server</strong>.

[caption id="attachment_2796" align="aligncenter" width="1494"]<img class="size-full wp-image-2796" src="https://windowsjet.com/wp-content/uploads/2020/06/ss3.png" alt="Turn Off Proxy" width="1494" height="834" /> Turn Off Proxy[/caption]</li>
 	<li>Then, try to reconnect your internet and open the Microsoft Store. If you see the error again, continue with the below steps.</li>
 	<li>Go to the <strong>Start</strong> menu and type '<strong>cmd</strong>' in the search box. You have to right-click on the top result and choose <strong>Run as administrator </strong>so it will open the Command Prompt with admin privileges.</li>
 	<li>You have to copy and paste the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">netsh winhttp reset proxy</code></p>


[caption id="attachment_2797" align="aligncenter" width="1228"]<img class="size-full wp-image-2797" src="https://windowsjet.com/wp-content/uploads/2020/06/ss4.png" alt="Reset proxy command" width="1228" height="709" /> Reset proxy command[/caption]
<ul>
 	<li>Then, you have to close the Command Prompt window and try to open the Store.</li>
</ul>
<h2 id="3">2) Reset Store Cache:</h2>
<ul>
 	<li>To open the <strong>Run box</strong>, you have to press <strong>Windows key + R</strong>.</li>
 	<li>Type the below command and click <strong>OK</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">wsreset.exe</code></p>


[caption id="attachment_2798" align="aligncenter" width="602"]<img class="size-full wp-image-2798" src="https://windowsjet.com/wp-content/uploads/2020/06/ss5.png" alt="wsreset.exe" width="602" height="370" /> wsreset.exe[/caption]
<ul>
 	<li>It will open the Microsoft Store along with a Command Prompt.</li>
 	<li>Once the system resets the Windows Store cache, you have to reboot your PC.</li>
</ul>
<h2 id="4">3) Delete DataStore File:</h2>
<ul>
 	<li>You have to go to this location <strong>C:\Windows\SoftwareDistribution\DataStore\DataStore.edb.</strong></li>
 	<li>Right-click on <strong>DataStore.edb</strong> and choose the <strong>Delete</strong> option.

[caption id="attachment_2799" align="aligncenter" width="1394"]<img class="size-full wp-image-2799" src="https://windowsjet.com/wp-content/uploads/2020/06/ss6.png" alt="Delete DataStore File" width="1394" height="660" /> Delete DataStore File[/caption]</li>
 	<li>Now open Microsoft store, and this method may fix error 0x801901F7 in Windows 10.</li>
 	<li>If not, you have to close all programs and restart your system then launch the Store again.</li>
</ul>
<h2 id="5">4) Modify Windows Update Properties:</h2>
<ul>
 	<li>You have to press <strong>Windows key + R</strong> to open the <strong>Run Command</strong>. You have to type '<strong>services.msc</strong>' and hit <strong>Enter</strong>.

[caption id="attachment_2800" align="aligncenter" width="599"]<img class="size-full wp-image-2800" src="https://windowsjet.com/wp-content/uploads/2020/06/ss7.png" alt="services.msc" width="599" height="366" /> services.msc[/caption]</li>
 	<li>In the <strong>Services</strong> window, you have to scroll down and locate the Windows Update service.</li>
 	<li>Right-click on it and choose <strong>Properties</strong>.</li>
 	<li>You have to check the <strong>Service status</strong>. If it is running, you have to stop it.</li>
 	<li>Then, you have to change the option to <strong>Automatic</strong> on <strong>Startup type</strong>.

[caption id="attachment_2801" align="aligncenter" width="650"]<img class="size-full wp-image-2801" src="https://windowsjet.com/wp-content/uploads/2020/06/ss8.png" alt="Startup type" width="650" height="748" /> Startup type[/caption]</li>
 	<li>After that, you have to start the service and then click on the <strong>Apply </strong>button and then <strong>OK</strong>.</li>
 	<li>At last, you have to restart your system and check whether the error gets fixed.</li>
</ul>
<h2 id="6">5) Run System File Checker:</h2>
Run the built-in System File Checker to repair corrupted files caused by your Windows OS. You just follow the below steps.
<ul>
 	<li>You have to click the <strong>Start</strong> button.</li>
 	<li>After that, in the search box and type <strong>'cmd'</strong>. Then press <b>Ctrl + Shift + </b><strong>Enter</strong> to open the Command Prompt with admin privileges.</li>
 	<li>In the Command Prompt, you have to type the below command and hit <strong>Enter</strong>.</li>
</ul>
<p style="background: #4a47ff;"><code style="background: #4a47ff; color: white;">sfc /scannow</code></p>


[caption id="attachment_2491" align="aligncenter" width="748"]<img class="size-full wp-image-2491" src="https://windowsjet.com/wp-content/uploads/2020/06/ue5.png" alt="SFC Scan" width="748" height="440" /> SFC Scan[/caption]
<ul>
 	<li>Now, the System File Checker will perform a scan and repair the corrupted files.</li>
 	<li>Once the scan gets completed, restart your PC.</li>
</ul>
<h2 id="7">Summary:</h2>
By following the solutions discussed in this article, you can <strong>Fix "The Server Stumbled" Error Code 0x801901F7 </strong>on Windows easily. We expect that these steps with clear-cut screenshots let you understand succinctly. If you have any <strong>queries</strong>, kindly share it in the below comment box. Thanks for visiting <a href="https://windowsjet.com/"><strong>Windows Jet</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-quickly-fix-the-bsod-error-0xc000021a-on-windows-10-2454/" target="_blank" rel="noopener noreferrer">How to Quickly Fix the BSOD Error 0Xc000021a on Windows 10?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://windowsjet.com/how-to-fix-error-code-0xc7700112-on-windows-pc-2514/" target="_blank" rel="noopener noreferrer">How to Fix Error Code 0xc7700112 on Windows PC?</a></li>
</ul>