---
title: Access Open Source Files with Ease Using the EmEditor Text Editor in C++
date: 2024-10-07T16:40:11.143Z
updated: 2024-10-08T16:36:48.763Z
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
<li><a href="https://some-knowledge.techidaily.com/new-infusing-homes-with-suns-invisible-light/"><u>[New] Infusing Homes with Sun's Invisible Light</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-laughlens-pictorial-humor-studio/"><u>[New] LaughLens Pictorial Humor Studio</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-inside-look-how-does-vr-headgear-work/"><u>2024 Approved Inside Look How Does VR Headgear Work?</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-tips-on-how-to-edit-youtube-channel-description/"><u>2024 Approved Tips on How to Edit YouTube Channel Description</u></a></li>
<li><a href="https://win-premium.techidaily.com/best-ipad-and-iphone-file-management-apps-for-macos-top-picks/"><u>Best iPad and iPhone File Management Apps for macOS: Top Picks!</u></a></li>
<li><a href="https://win-premium.techidaily.com/comprehensive-guide-on-navigating-through-the-intricacies-of-mp4-video-files/"><u>Comprehensive Guide on Navigating Through the Intricacies of MP4 Video Files</u></a></li>
<li><a href="https://win-premium.techidaily.com/easy-guide-to-syncing-iphone-data-with-your-mac/"><u>Easy Guide to Syncing iPhone Data with Your Mac</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-xr-data-completely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone XR Data Completely | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-realme-c67-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>In 2024, Does Realme C67 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-mastering-lock-screen-settings-how-to-enable-and-disable-on-realme-v30-by-drfone-android/"><u>In 2024, Mastering Lock Screen Settings How to Enable and Disable on Realme V30</u></a></li>
<li><a href="https://win-premium.techidaily.com/introducing-the-new-release-of-apowermirror-v1463-features-youll-love/"><u>Introducing the New Release of ApowerMirror (v1.4.6.3): Features You'll Love</u></a></li>
<li><a href="https://win-premium.techidaily.com/mastering-cross-platform-messaging-a-guide-to-accessing-your-whatsapp-conversations-from-a-computer/"><u>Mastering Cross-Platform Messaging: A Guide to Accessing Your WhatsApp Conversations From a Computer</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-ken-burns-effect-in-final-cut-pro-a-beginners-guide-to-professional-results-for-2024/"><u>New Ken Burns Effect in Final Cut Pro A Beginners Guide to Professional Results for 2024</u></a></li>
<li><a href="https://win-premium.techidaily.com/step-by-step-tutorial-for-shifting-pictures-from-your-samsung-galaxy-note-10-to-pc-efficiently/"><u>Step-by-Step Tutorial for Shifting Pictures From Your Samsung Galaxy Note 10 to PC Efficiently</u></a></li>
<li><a href="https://win-premium.techidaily.com/the-ultimate-list-top-4-screen-reflector-software-options-for-the-huawei-mate-xs/"><u>The Ultimate List: Top 4 Screen Reflector Software Options for the Huawei Mate XS</u></a></li>
<li><a href="https://win-premium.techidaily.com/ultimate-step-by-step-tutorial-capturing-images-with-your-toshiba-device/"><u>Ultimate Step-by-Step Tutorial: Capturing Images with Your Toshiba Device</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/which-pokemon-can-evolve-with-a-moon-stone-for-oneplus-11-5g-drfone-by-drfone-virtual-android/"><u>Which Pokémon can Evolve with a Moon Stone For OnePlus 11 5G? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884017/19272" target="_top" id="1884017">
  <img src="//a.impactradius-go.com/display-ad/19272-1884017" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884017/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

