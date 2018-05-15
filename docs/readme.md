# Documentation

## Setup

Checklists for setting up the Windows desktop computer. We record all the juicy
details in our private SOP document. 

* Uptime
    * [x] BIOS power recovery options: set to on
    * [x] BIOS automatic power on: set to daily
    * [x] Add UPS and power management software
    * [x] Adjust power plan to never sleep or hibernate
    * Automate the reboot cycle
        * [x] Do have Windows Update automatically install & reboot
        * [x] Setup automatic user login
        * [x] Automate locking desktop at user login
        * [x] Launch Nginx (or setup Nginx as a Windows service somehow?)
        * [x] Launch NTP Server Monitor
        * [x] Launch LoggerNet
* Remote management
    * [x] Disable Remote Assistance invitations
    * [x] Enable Remote Desktop with NLA
    * [ ] Implement firewall rules
* WSU ITS
    * [x] Request static IP address & DNS alias
    * [ ] Request firewall rules
* Utilities to install
    * [x] [7-Zip](https://www.7-zip.org/)
    * [x] [Notepad++](https://notepad-plus-plus.org/download/v7.5.6.html)
    * [x] [Cmder Full](http://cmder.net/)
    * [x] [Process Hacker](https://processhacker.sourceforge.io/downloads.php)
    * [x] [GitExtensions](https://github.com/gitextensions/gitextensions)
    * [x] [Greenshot](http://getgreenshot.org/downloads/)
    * [x] [Sysinternals Suite](https://docs.microsoft.com/en-us/sysinternals/downloads/)
* Software to install
    * [x] ~~[Python 3.6](https://www.python.org/downloads/release/python-365/)~~
    * [x] [Crypt-LE](https://github.com/do-know/Crypt-LE)
    * [x] [FileZilla Server](https://filezilla-project.org/download.php?type=server)
    * [x] [Nginx](https://nginx.org/en/download.html)
    * [x] [Nework time protocol](https://www.meinbergglobal.com/english/sw/ntp.htm#ntp_stable)
    * [x] [NTP server monitor](https://www.meinbergglobal.com/english/sw/ntp-server-monitor.htm)
    * [x] LoggerNet
    * [ ] cygwin (for SFTP) or freeSSHd?
    * [ ] hMailAdmin? or maybe just use Google App Passwords?
    * [ ] Areca Backup? or something else?
    * [ ] TightVNC or RealVNC servers?
    * [ ] ~~certbot ([ref](https://community.letsencrypt.org/t/running-certbot-on-windows-phase-1/28348/3))~~
* Server configuration
    * [x] generate SSL certificate
    * [x] get FTP running
        * [x] revise Windows firewall
        * [x] enable SFTP using air.paccar.wsu.edu SSL cert
        * [x] tie in shares directory
    * [ ] get SFTP running
    * [x] get HTTP/browse running
        * [x] fix webroot
        * [x] integrate SSL cert
    * [x] create file share directory structure
* My personal prejudices
    * [x] Fixup browser settings
        * Search engine: DuckDuckGo
        * Tabs: continue where left off
    * [x] Turn Windows features ~~on or~~ off:
        * Internet Explorer 11
        * Media features (DVD maker, Media center/player)
        * Windows Gadget Platform
        
