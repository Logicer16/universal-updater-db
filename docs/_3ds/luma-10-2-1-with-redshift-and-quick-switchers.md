---
archive:
  .*\.zip:
  - boot.firm
  - luma/
author: Nutez
avatar: https://gbatemp.net/data/avatars/l/439/439371.jpg?1618764346
categories:
- utility
- firm
- luma3ds
color: '#927c64'
created: '2019-02-24T20:26:00Z'
description: Return of the customisable screen filter & other QoL improvements
download_page: https://gbatemp.net/download/35619/
downloads:
  luma1021_QuickSwitchers - Wifi button toggle.zip:
    url: https://gbatemp.net/download/luma-10-2-1-with-redshift-and-quick-switchers.35619/download?version=38477
gbatemp: '35619'
github: DullPointer/Luma3DS
image: https://gbatemp.net/data/avatars/l/439/439371.jpg?1618764346
layout: app
license: gpl-3.0
license_name: GNU General Public License v3.0
source: https://github.com/DullPointer/Luma3DS
systems:
- 3DS
title: Luma 10.2.1 with Redshift and Quick-Switchers
update_notes: 'New features:<br/>

  <ul>

  <li>Quick toggle Wifi from menus with START button press</li>

  <li>Option to force revert TWiLightMenu widescreen patch from Quick-Switchers submenu
  - useful if game specific aspect ratio patch fails or forced exit from TWiLightMenu</li>

  <li>Option to toggle <a class="externalLink" href="https://github.com/hax0kartik/rehid"
  rel="nofollow" target="_blank">rehid</a> folder from System configuration sub menu
  - useful to temporarily disable rehid patch to allow use of button combos that might
  otherwise be blocked (Rosalina, BootNTR, plugins, <a class="externalLink" href="https://github.com/hax0kartik/wumiibo"
  rel="nofollow" target="_blank">wumiibo</a>). Folder must be disabled before loading
  game to not have rehid apply.</li>

  <li>Merged in <a class="externalLink" href="https://github.com/LumaTeam/Luma3DS/pull/1623"
  rel="nofollow" target="_blank">enhancements</a> to Luma cheats system</li>

  </ul>'
updated: '2021-08-06T18:02:00Z'
version: 10.2.1 2021-08-06
version_title: Luma 10.2.1 with Redshift and Quick-Switchers
---
<a class="internalLink" href="https://gbatemp.net/threads/unofficial-luma-build-discussion.573617/">Discussion/question thread</a><br/>
<a class="externalLink" href="https://github.com/DullPointer/Luma3DS" rel="nofollow" target="_blank">Source</a><br/>
<br/>
Features:<br/>
<span style="color: rgb(0, 102, 0)"><b>Luma 10.2.1</b></span><br/>
<ul>
<li>Thank you to the Luma developers <a class="externalLink" href="https://github.com/LumaTeam/Luma3DS/wiki" rel="nofollow" target="_blank">official github</a></li>
</ul><span style="color: rgb(0, 102, 0)"><a class="internalLink" href="https://gbatemp.net/threads/ctr_redshift-hardware-based-blue-light-filter-for-old3ds-and-2ds.493736/page-5">Redshift</a><b> custom screen filter (thanks to Sono):</b></span><br/>
<ul>
<li>Tweak screens individually (not possible for o2DS due to single screen hardware)</li>
<li>Dimming effect for additional brightness reduction<br/>
</li>
<li>Much greater range of filter customisation</li>
<li>Reapplies saved filter on awaken from sleep<br/>
</li>
<li>Automatic LED suppression when filter applied</li>
</ul><span style="color: rgb(0, 102, 0)"><b>Automatic cut to slot power when booted with DS/TWL game cartridge inserted:</b></span><br/>
<ul>
<li>This stops DS flashcarts from <a class="externalLink" href="https://github.com/LumaTeam/Luma3DS/issues/1202#issuecomment-449624237" rel="nofollow" target="_blank">leeching power</a> when not in use<br/>
</li>
<li>You will need to force boot into DS game cartridge by using the CIA from <a class="internalLink" href="https://gbatemp.net/threads/twl-slot-1-launcher-first-custom-dsiware-app.414501/">here</a>, with <a class="externalLink" href="https://github.com/DS-Homebrew/TWiLightMenu/releases" rel="nofollow" target="_blank">TWiLightMenu</a> or reinsert the cartridge</li>
</ul><b><span style="color: rgb(0, 102, 0)">Quick-Switchers sub menu:</span></b><br/>
<ul>
<li>Quick-Switch between your preferred filters/config for DS/i games (<a class="internalLink" href="https://gbatemp.net/threads/twpatcher-ds-i-mode-screen-filters-and-patches.542694/">TwlBg</a>) and GBA games (<a class="internalLink" href="https://gbatemp.net/threads/twpatcher-ds-i-mode-screen-filters-and-patches.542694/page-71#post-9143128">AgbBg</a>, <a class="externalLink" href="https://github.com/profi200/open_agb_firm" rel="nofollow" target="_blank">open_agb_firm</a>, <a class="internalLink" href="https://gbatemp.net/download/open-agb-launcher.36828/">Open AGB Launcher</a>)<br/>
</li>
<li>TwlBg option displays ".cxi" files from "/luma/sysmodules/TwlBg" and persists selected file name to "/luma/sysmodules/twlbgName.txt"<br/>
</li>
<li><a class="externalLink" href="https://wiki.ds-homebrew.com/twilightmenu/playing-in-widescreen.html" rel="nofollow" target="_blank">Widescreen</a> option displays ".cxi" files from "/luma/sysmodules/Widescreen" and persists selected file name to "/luma/sysmodules/widescreenName.txt"</li>
<li>AgbBg option displays ".cxi" files from "/luma/sysmodules/AgbBg" and persists selected file name to "/luma/sysmodules/agbbgName.txt"<br/>
</li>
<li>Open_AGB option displays ".ini" files from "/3ds/open_agb_firm" and persists selected file name to "/3ds/open_agb_firm/configName.txt"<br/>
</li>
<li>Works best with meaningful file names e.g. "redshiftWideMode.cxi", "pixelPerfect.cxi", "lowBrightness.ini"<br/>
</li>
<li>Delete the .txt file when creating new TwlBg/AgbBg patches to avoid the persisted name being incorrect</li>
<li>Option to force revert TWiLightMenu widescreen patch</li>
</ul><b><span style="color: rgb(0, 102, 0)">Plugin loader:</span></b><br/>
<ul>
<li>All credit to Nanquitas and PabloMK7 and anyone else involved in the CTRPF project!</li>
<li>Not backwards compatible with .plg or old .3gx<br/>
</li>
<li>Supports new CTRPF v0.6.0 and v0.7.0 .3GX format (header 3GX$0002) plugin</li>
<li>Default plugin available from <a class="internalLink" href="https://gbatemp.net/threads/ctrpluginframework-blank-plugin-now-with-action-replay.487729/page-68#post-9343144">CTRPF thread</a> or <a class="externalLink" href="https://discord.com/invite/z4ZMh27" rel="nofollow" target="_blank">Nanquitas' Playground</a> announcements channel</li>
<li>"default.3gx" goes in "/luma/plugins" directory</li>
</ul><b><span style="color: rgb(0, 102, 0)">Enhanced brightness adjustment interface:</span></b><br/>
<ul>
<li>Adjust brightness of top and bottom screens independently (not possible for o2DS due to single screen hardware)</li>
<li>Option to use hidden true maximum brightness (at your own risk?)</li>
<li>Option to use hidden true minimum brightness<br/>
</li>
<li>Option to switch off bottom screen backlight entirely</li>
</ul><b><span style="color: rgb(0, 102, 0)">Software volume control interface (thanks again to <a class="internalLink" href="https://gbatemp.net/threads/is-there-an-volume-management-homebrew.474817/#post-8699169">Sono</a>):</span></b><br/>
<ul>
<li>Accessible from System Configuration sub menu</li>
<li>Change volume in 1/64 steps without using physical volume slider</li>
<li>Volume percentage now displayed in sub menus</li>
</ul><b><span style="color: rgb(0, 102, 0)">Permanent brightness recalibration:</span></b><br/>
<ul>
<li>Recalibration is applied for 3DS, DS/i and GBA modes<br/>
</li>
<li>Accessible from System Configuration sub menu</li>
<li>Edit the values behind the 5 selectable brightness levels</li>
<li>Changes are saved to NAND so use sparingly to avoid wearing out the memory</li>
<li>Upper limit of 172 is found in code so it is presumed to be safe but may reduce LCD lifespan</li>
</ul><b><span style="color: rgb(0, 102, 0)">Misc/QoL:</span></b><br/>
<ul>
<li>Quick toggle LEDs from menus by pressing SELECT</li>
<li>Quick toggle WiFi from menus by pressing START<br/>
</li>
<li>New3DS clock/cache status visible on main menu</li>
<li><a class="externalLink" href="https://github.com/LumaTeam/Luma3DS/pull/1634" rel="nofollow" target="_blank">Allow Patches in the Home Menu</a> e.g. place <a class="internalLink" href="https://gbatemp.net/threads/release-betterbatterycolors-for-homemenu.523138/">BetterBatteryColors</a> hud_LZ.bin in /luma/titles/*YourRegionHomeMenuTitleId*/romfs - thank you <a class="externalLink" href="https://github.com/gabe565" rel="nofollow" target="_blank"><span style="font-size: 12px">gabe565</span></a></li>
<li>Merged in <a class="externalLink" href="https://github.com/LumaTeam/Luma3DS/pull/1623" rel="nofollow" target="_blank">enhancements</a> to Luma cheats system - thank you <a class="externalLink" href="https://github.com/s5bug" rel="nofollow" target="_blank"><span style="font-size: 12px">s5bug</span></a></li>
<li>Option to toggle <a class="externalLink" href="https://github.com/hax0kartik/rehid" rel="nofollow" target="_blank">rehid</a> folder System configuration sub menu (folder must be disabled before loading game to not have rehid apply)</li>
</ul>