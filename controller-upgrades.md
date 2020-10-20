# Manual controller uprades

If you want to upgrade to a specific controller version outside of the maintenance UI:

1. Find the preferred Cloud Key Gen 2 Plus controller package [here](https://www.ui.com/download/unifi/unifi-cloud-key-gen2/default/unifi-network-controller-51423-debianubuntu-linux-and-unifi-cloud-key)
1. `ssh ubnt@<CLOUD-KEY-IP-ADDRESS>`
1. `cd /tmp && wget <PACKAGE-URL>`
1. `sudo dpkg -i unifi_sysvinit_all.deb `
1. `rm sudo dpkg -i unifi_sysvinit_all.deb`

Reference: https://help.ui.com/hc/en-us/articles/216655518