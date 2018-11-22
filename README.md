# Atikmdag-Patcher-2.2.1
Atikmdag Patcher 2.2.1
Version 2.2.1 is compatible with Catalyst 15.12 to Crimson 18.2.3. It can be used with future versions if it finds the limits you need.
Getting started:
Run atikmdag-patcher.exe.
If all limits are found, click "Yes" to patch and sign. If a limit is not found or if multiple matches are found, the patcher needs to be updated.
Reboot.
To restore the unpatched driver, run the patcher again and click "Yes" to restore from backup.

https://ibb.co/ifstbJ
 
Known issues:
Legacy drivers may have issues with HDCP and video acceleration with the patch.
Workarounds for video playback issues with legacy drivers:
Disable hardware acceleration in the Flash Player settings (right-click on any Flash video and click "Settings...").
Use the Codec Tweak Tool to disable DXVA hardware acceleration under "Various Tweaks" (in the "Miscellaneous" section).
AMD/ATI cards have a design limitation unrelated to the patch that causes video acceleration to scramble the screen if the vertical blanking/total is below standard with the video card's memory overclocked or with multiple monitors connected. Skype is known to trigger this problem. Either don't overclock the video card's memory, or use the "LCD standard" vertical blanking/total in CRU.
AMD/ATI cards require the "LCD standard" vertical blanking/total to reduce the memory clock when idle. Horizontal values can still be reduced if necessary.


Download:
