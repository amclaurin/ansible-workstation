# ansible-workstation
Ansible files for building a Linux Developer Workstation with Cloud Tools

This is an Ansible build script to run on Fedora, Ubuntu / KUbuntu or Open SuSE to upgrade the KDE Desktop to a useful developer workstation with a good set of base Linux tools, Cloud Management Tools for the 3 major clouds, a clean apprearance for the KDE desktop and a selection of Browsers and Editors

Each of the following options is customisable

Install a standard set of Linux utils to ensure each distribution has the usual baseline for development, such as Curl and Htop

Install Browsers from a choice of Firefox / Falkon, Opera, Chromium, Vivaldi and Brave. The script configures the repos for each of these.

Install editors from Kate / VS Code and Aton, again installing the repos needed.

Installs the AWS, Azure or GCP commad line tools as needed.

Installs the 12.x release of Terraform

Installs sshuttle which is a handy little tunnelling app for cloud testing, but also is useful for VPN like endpoints (it's super easy to set up)

Optionally adds some additional wallpapers

Ensures the noto-sans and ubuntu font families are installed, I find these good defaults for distributions which don't ship with them

Installs some KDE Icons and themes and a customised blue colour scheme. These are optional but I find them useful as some default distribution settings are just ugly

Experimentally adds some Firefox extensions, broken at present.

Optionally adds all the tools required for Linux from Scratch, useful tools if you want to do any low level Linux work.

TBD - Adds a simple text file to the desktop with hints as to quick configuration of the KDE settings, as I haven't wored out how to modify all the KDE conf files and it's 2 minutes work.

Once you have downloaded these scripts, all you have to do is install ansible, run the setup-workstation scripts, make some quick config changes and you will have a professional Linux desktop very suited for Cloud development

This is really a hobby project for me, in part to learn ansible, so please feel free to branch, modify or send comments


