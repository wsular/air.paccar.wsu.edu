# Documentation

## Setup

Checklists for setting up the Windows desktop computer.

* Uptime
    * [x] BIOS power recovery options: set to on
    * [x] BIOS automatic power on: set to daily
    * [ ] Add UPS and power management software
    * [x] Adjust power plan to never sleep or hibernate
    * Automate the reboot cycle
        * [x] Do have Windows Update automatically install & reboot
        * [ ] Setup automatic user login
* Remote management
    * [x] Disable Remote Assistance invitations
    * [x] Enable Remote Desktop with NLA
* WSU ITS
    * [x] Request static IP address & DNS alias
    * [ ] Request firewall rules
* Software to install
    * [x] [Python 3.6](https://www.python.org/downloads/release/python-365/)
        * Under `C:\server`, for certbot
    * [x] [7-Zip](https://www.7-zip.org/)
    * [x] [Notepad++](https://notepad-plus-plus.org/download/v7.5.6.html)
    * [x] [Cmder Full](http://cmder.net/)
    * [ ] certbot ([ref](https://community.letsencrypt.org/t/running-certbot-on-windows-phase-1/28348/3))
    * [ ] FileZilla
    * [ ] Nginx
    * [ ] cygwin (for SFTP) or freeSSHd?
    * [ ] Nework time protocol & server monitor
    * [ ] LoggerNet
    * [ ] hMailAdmin? or maybe just use Google App Passwords?
    * [ ] Areca Backup? or something else?
    * [ ] TightVNC or RealVNC servers?
* My personal prejudices
    * [x] Fixup browser settings
        * Search engine: DuckDuckGo
        * Tabs: continue where left off
    * [x] Turn Windows features ~~on or~~ off:
        * Internet Explorer 11
        * Media features (DVD maker, Media center/player)
        * Windows Gadget Platform
        
