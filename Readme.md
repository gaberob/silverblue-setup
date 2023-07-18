
# Instructions
* This is really meant to be used on something like [ublue](https://universal-blue.org/), that already has a lot of QoL improvements built on top of silverblue, so start with a fresh install of one of those images, preferably the main gnome or bluefin one.
* rpm-ostree install ansible
* reboot
* Clone and enter the repo (git clone)
* ansible-galaxy collection install community.general
* Make sure we have a sudo token (sudo whoami)
* ansible-playbook main.yml

# What this script does
* Layers various packages on the host via rpm-ostree
* Installs flatpaks I use
* Imports my dconf keyboard shortcuts


# What this script will do 
* Dotfiles?
* Additional customization?
