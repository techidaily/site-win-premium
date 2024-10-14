---
title: Access Open Source Files with Ease Using the EmEditor Text Editor in C++
date: 2024-10-10T11:54:15.750Z
updated: 2024-10-14T07:07:02.972Z
tags:
  - product
categories:
  - emeditor
thumbnail: https://thmb.techidaily.com/b7baa33d4b10fe886a40e23c90cd05fef9558b48e747814e8f0bb0ff84874df4.jpg
---

## Access Open Source Files with Ease Using the EmEditor Text Editor in C++

Viewing 1 post (of 1 total)

* Author  
Posts
* March 21, 2008 at 6:02 pm [#5598](https://tools.techidaily.com/emeditor/products/)  
[![](https://secure.gravatar.com/avatar/acd7b53acdac566781d920744da2bbaa?s=80&d=identicon&r=g)shaohao](https://www.emeditor.com/forums/users/shaohao/ "View shaohao's profile")  
Member  
This Macro is useful when you are writing C/C++ code with EmEditor. It will switch between .h and .c/.cpp files.  
    
	#title = ""  
	#tooltip = "C/C++<->H"  
	    
	fso = new ActiveXObject("Scripting.FileSystemObject");  
	    
	// get file full name  
	fn = document.FullName;  
	    
	// get base name and extension  
	base = fso.GetParentFolderName(fn) + "" + fso.GetBaseName(fn);  
	ext = fso.GetExtensionName(fn);  
	if (ext == "") Quit();  
	    
	// get file name to be opened  
	if (ext.toLowerCase() == "h") {  
		fn = base + ".cpp";  
		if (! fso.FileExists(fn)) fn = base + "c";  
	} else if (ext.toLowerCase() == "c" || ext.toLowerCase() == "cpp") {  
		fn = base + ".h";  
	} else {  
		Quit(); // unsupported  

	    
	// open the file  
	if (fso.FileExists(fn)) editor.OpenFile(fn, 0, eeOpenAllowNewWindow);
* Author  
Posts

Viewing 1 post (of 1 total)

* You must be logged in to reply to this topic.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-explore-10-premier-yoga-streams-for-wellness-boost/"><u>[Updated] 2024 Approved Explore 10 Premier Yoga Streams for Wellness Boost</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-rapid-film-techniques-make-your-own-studio-at-home/"><u>[Updated] Rapid Film Techniques Make Your Own Studio At Home</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-from-basics-to-brilliance-fullscreen-proficiency-in-premiere/"><u>2024 Approved From Basics to Brilliance Fullscreen Proficiency in Premiere</u></a></li>
<li><a href="https://win-premium.techidaily.com/adjusting-text-alignment-in-emeditor-a-comprehensive-guide/"><u>Adjusting Text Alignment in emEditor: A Comprehensive Guide</u></a></li>
<li><a href="https://win-premium.techidaily.com/advanced-file-handling-with-emeditor-a-comprehensive-guide/"><u>Advanced File Handling with EmEditor - A Comprehensive Guide</u></a></li>
<li><a href="https://win-premium.techidaily.com/effortless-csv-management-in-emeditor-the-ultimate-text-editor-experience/"><u>Effortless CSV Management in EmEditor, the Ultimate Text Editor Experience</u></a></li>
<li><a href="https://win-premium.techidaily.com/emeditor-text-editor-with-syntax-highlighting-support-for-various-file-extensions/"><u>EmEditor Text Editor with Syntax Highlighting Support for Various File Extensions</u></a></li>
<li><a href="https://win-premium.techidaily.com/emeditor-configure-store-options-via-inixml-files-rather-than-using-the-registry/"><u>EmEditor: Configure Store Options via .ini/XML Files Rather Than Using the Registry</u></a></li>
<li><a href="https://extra-tips.techidaily.com/iconic-top-tier-virtual-reality-films/"><u>Iconic Top-Tier Virtual Reality Films</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-xiaomi-13t-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Xiaomi 13T? | Dr.fone</u></a></li>
<li><a href="https://win-premium.techidaily.com/master-your-documents-advanced-smarttabs-and-customizable-spaces-in-emeditors-text-editor/"><u>Master Your Documents: Advanced SmartTabs and Customizable Spaces in EmEditor's Text Editor</u></a></li>
<li><a href="https://windows11.techidaily.com/pro-tip-unearthing-windows-apps-installed-locations-quickly/"><u>Pro Tip: Unearthing Windows Apps' Installed Locations Quickly</u></a></li>
<li><a href="https://fox-access.techidaily.com/secrets-to-mastering-chromebook-zoom-features/"><u>Secrets to Mastering Chromebook Zoom Features</u></a></li>
<li><a href="https://win-premium.techidaily.com/simplify-writing-with-emeditor-the-premier-text-editor-software/"><u>Simplify Writing with EmEditor: The Premier Text Editor Software!</u></a></li>
<li><a href="https://win-premium.techidaily.com/slowing-down-your-typing-how-wordcomplete-addon-impacts-emeditors-response-time/"><u>Slowing Down Your Typing: How WordComplete Addon Impacts EmEditor's Response Time</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/the-genuine-value-of-truthgpt-coins/"><u>The Genuine Value of TruthGPT Coins</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-ultimate-guide-to-ipad-add-ons-for-a-superior-experience-expert-reviews/"><u>The Ultimate Guide to iPad Add-Ons for a Superior Experience - Expert Reviews</u></a></li>
<li><a href="https://win-able.techidaily.com/troubleshoot-and-stop-zoom-disruptions-on-pcs-latest-solutions/"><u>Troubleshoot and Stop Zoom Disruptions on PCs - Latest Solutions</u></a></li>
<li><a href="https://win-premium.techidaily.com/ultimate-guide-to-emeditor-your-ideal-text-editing-solution/"><u>Ultimate Guide to EmEditor: Your Ideal Text Editing Solution</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141683/17092" target="_top" id="2141683">
  <img src="//a.impactradius-go.com/display-ad/17092-2141683" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141683/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

