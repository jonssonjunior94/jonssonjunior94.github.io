
![status](https://nocache.advaith.workers.dev?url=https://img.shields.io/endpoint?url=https://dev.discordprofiles.me/api/badge/status/276544649148235776?simple=true)
![playing](https://nocache.advaith.workers.dev?url=https://img.shields.io/endpoint?url=https://dev.discordprofiles.me/api/badge/playing/276544649148235776)

![firefox_ch3iRScWSX2222](https://github.com/user-attachments/assets/4ccdf5f3-1f4b-47c9-ab67-e5e9345c7cec=250x250)


&nbsp;

&nbsp;

### Portable Applications


- [7-Zip](https://www.7-zip.org/download.html) - File archiver with a high compression ratio and built-in encryption functionality.
- [ShareX](https://github.com/ShareX/ShareX/releases) - Lets you take screenshots of any selected area with a single key.
- [Discord portable](https://github.com/portapps/discord-portable) - Portable instead of the regular auto install.
- [Open Hardware Monitor](https://openhardwaremonitor.org/downloads/) - Free open source software that monitors temperatures, fans, voltages, load and clock.
- [Geek Uninstaller](https://geekuninstaller.com/) - Geek Uninstaller is a perfectly functional uninstaller. Also removes attached registry keys.
- [Notepad++](https://notepad-plus-plus.org/downloads/) - Notepad++ is a great replacement for Windows notepad. It's a good choice for beginners.
- [VLC](https://www.videolan.org/vlc/download-windows.html) - VLC is a free and open source cross-platform multimedia player and framework that plays most multimedia files.


##### Extras
- [qBittorrent](https://github.com/portapps/qbittorrent-portable/releases) - qBittorrent is a open-source BitTorrent client written in native C++. [Search plugin](https://github.com/qbittorrent/search-plugins/wiki/Unofficial-search-plugins)
- [Scrcpy](https://github.com/Genymobile/scrcpy) - This application provides display and control of Android devices connected via USB.
- [yt-dlp](https://github.com/yt-dlp/yt-dlp) - A youtube-dl fork with additional features and fixes. Works great with [yt-dl-gui](https://github.com/oleksis/youtube-dl-gui).
  Also [FFmpeg.](https://github.com/BtbN/FFmpeg-Builds/releases) copy the bin folder content to the folder that yt-dlp.exe is located at `(ffprobe, ffplay and ffmpeg)`. Settings to download with h264 or h265 codec `$ yt-dlp -f "(bv*[vcodec~='^((he|a)vc|h26[45])']+ba) / (bv*+ba/b)"` And Filename Format `%(autonumber)02d. %(title)s`
- [Twitch GUI](https://github.com/streamlink/streamlink-twitch-gui) - A multi platform Twitch.tv browser for [Streamlink](https://github.com/streamlink/windows-builds/releases). Works great with [VLC](https://www.videolan.org/vlc/download-windows.html).
- [Everything](https://www.voidtools.com/) - Locate files and folders by name instantly. Plus [Everything Toolbar](https://github.com/stnkl/EverythingToolbar) for the taskbar.
- [SuperSlicer](https://github.com/supermerill/SuperSlicer) - Developed to provide users more control over their slicer than what was possible with PrusaSlicer.
- [NVIDIA Profile Inspector](https://github.com/Orbmu2k/nvidiaProfileInspector) - Open source third-party tool created for pulling up and editing application profiles within Nvidia display drivers.
- [FreeTube](https://github.com/FreeTubeApp/FreeTube/releases) - FreeTube is a YouTube client with a focus on privacy. [Importing your Subscriptions](https://docs.freetubeapp.io/usage/importing-subscriptions/)

&nbsp;

&nbsp;

##### Emulators and ROMs
- [Yuzu](https://github.com/yuzu-emu/yuzu-mainline) (Switch) To make Yuzu portable create a folder named "user" inside the installation directory.
- [Dolphin](https://dolphin-emu.org/download/) (GameCube/Wii) To make Dolphin emulator portable create a .txt file named "portable" inside the installation directory.
- [Cemu](https://wiki.cemu.info/wiki/Release_1.26.2f) (Wii U) Cemu is already portable.


RIP Yuzu 04-03-2024.
- Yuzu 1734 [Mediafire](https://www.mediafire.com/file/eodvqt2uavymowj/Yuzu_1734.zip/file)

&nbsp;

#### USB Tools & Operating Systems

- [Rufus](https://rufus.ie/downloads/) Rufus is a utility that helps format and create bootable USB flash drives.
- [Ventoy](https://github.com/ventoy/Ventoy/releases) Ventoy is an open source tool to create bootable USB drive for ISO/WIM/IMG/VHD(x)/EFI files.
- [Tails](https://tails.net/install/) Is a portable operating system that protects against surveillance and censorship.

&nbsp;

##### DNS Blocklists
- [Crazy Max's WindowsSpyBlocker - Hosts spy rules](https://raw.githubusercontent.com/crazy-max/WindowsSpyBlocker/master/data/hosts/spy.txt)
- [HaGeZi's Blocklist - Big Broom](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt)
- [HaGeZi's DoH/VPN/TOR/Proxy Bypass - Prevent methods to bypass your DNS](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/doh-vpn-proxy-bypass.txt)
- [HaGeZi's Threat Intelligence Feeds](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt)
- [HaGeZi's Windows/Office Tracker DNS Blocklist](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/domains/native.winoffice.txt)
- [hBlock - Adblock](https://hblock.molinero.dev/hosts_adblock.txt)
- [OISD BIG - Blocklist](https://big.oisd.nl/)
- [Someone Who Cares](https://someonewhocares.org/hosts/zero/hosts)

&nbsp;

&nbsp;

### Browsers


#### Firefox

- [Mozilla FTP](https://ftp.mozilla.org/pub/firefox/releases/) Installer.
- [Mozilla FTP - Nightly](https://ftp.mozilla.org/pub/firefox/nightly/latest-mozilla-central-l10n/) Installer or Portable.
- [Firefox Profilemaker](https://ffprofile.com/) Tool to create a Firefox profile with the defaults you like.
- Extras: [Compact Mode](https://support.mozilla.org/en-US/kb/compact-mode-workaround-firefox)

### about:config settings:

- Remove Fullscreen Transition Animation
-      full-screen-api.transition-duration.enter = 
       full-screen-api.transition-duration.leave =           Change values to "0 0"

- Disable "enable DRM" banner to prompt
-      browser.eme.ui.enabled
                                                             Change value to "false"

- Remove Recommended Extensions from showing up in add-ons manager
-      extensions.htmlaboutaddons.discover.enabled
       extensions.htmlaboutaddons.recommendations.enabled
                                                             Change value to "false"
   
- Addons: [uBlock Origin](https://addons.mozilla.org/de/firefox/addon/ublock-origin/) [Imagus](https://addons.mozilla.org/en-US/firefox/addon/imagus/) [SponsorBlock](https://addons.mozilla.org/en-US/firefox/addon/sponsorblock/) [ClearURLs](https://addons.mozilla.org/en-US/firefox/addon/clearurls/) [TWP](https://addons.mozilla.org/en-US/firefox/addon/traduzir-paginas-web/) [User-Agent Switcher](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/) [Google Mail Checker](https://addons.mozilla.org/en-US/firefox/addon/ff-google-mail-checker/) [Gumbo: Twitch Companion](https://addons.mozilla.org/en-US/firefox/addon/gumbo-twitch-companion/)

&nbsp;

#### Chrome

- [Ungoogled-Chromium](https://github.com/ungoogled-software/ungoogled-chromium-windows/releases)
Disable "Clear Cookies" to save settings and login information at visited sites. `chrome://settings/cookies`
- [Extensions](https://github.com/jonssonjunior94/Windows-10-Settings/releases/tag/Extensions) Personal backup of extensions. 
- [Chrome Bookmarks Recovery Tool](https://rongjiecomputer.github.io/chrome/bookmark-recovery/#windows) Best way i have found to back up bookmarks from Google Chrome as a .html file to easily use with Ungoogled Chromium.

&nbsp;

&nbsp;

### Useful Websites
- [Send](https://github.com/timvisee/send-instances/#instances) - Share encrypted files with ease.
- [Gmailnator](https://www.emailnator.com/) - Temporary Disposable Gmail. (Use Adblock)
- [Redirect Detective](https://redirectdetective.com/) - URL redirection checker, see the complete path a redirected URL goes through.
- [Have i been pwned](https://haveibeenpwned.com/) - Check if your email or phone is in a data breach. Only publicly discovered breaches.
- [IsThereAnyDeal](https://isthereanydeal.com/?currency=USD) - A useful little web tool that tracks PC game prices across a variety of sources, including Steam.
- [VirusTotal](https://www.virustotal.com/gui/home/upload) - Free service that analyzes files and URLs for viruses. It's not advisable to upload sensitive files.
- [NMHDDS](https://doyou.needmorehdd.space/?fileType=&query=chrome#) NMHDDS Google Open Directory Search Tool. Get direct download links to (almost) anything.
  
&nbsp;

- [Test Ad Block](https://d3ward.github.io/toolz/adblock.html) This tool allows you to check if your adblock solution is blocking enough hosts.
- [dnscheck.tools](https://dnscheck.tools/) Identifies your DNS resolvers, checks DNSSEC validation, and more.
- [ipaddr.tools](https://myip.addr.tools/help) get your public IP address.
- [RDAP data](https://info.addr.tools/me) Displays relevant DNS records and RDAP registration data.
- [Port Checker](https://portchecker.co/) Check for open ports and verify port forwarding setup on your router.

&nbsp;

&nbsp;
