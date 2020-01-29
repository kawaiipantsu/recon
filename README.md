# ᵔᴥᵔ Recon
[![Twitter Follow](https://img.shields.io/twitter/follow/davidbl.svg?style=social&label=Follow)](https://twitter.com/davidbl) [![GitHub issues](https://img.shields.io/github/issues/kawaiipantsu/recon.svg)](https://github.com/kawaiipantsu/recon/issues) [![GitHub closed issues](https://img.shields.io/github/issues-closed/kawaiipantsu/recon.svg)](https://github.com/kawaiipantsu/recon/issues) [![GitHub license](https://img.shields.io/github/license/kawaiipantsu/recon.svg)](https://github.com/kawaiipantsu/recon/blob/master/LICENSE) [![GitHub forks](https://img.shields.io/github/forks/kawaiipantsu/recon.svg)](https://github.com/kawaiipantsu/recon/network) [![GitHub stars](https://img.shields.io/github/stars/kawaiipantsu/recon.svg)](https://github.com/kawaiipantsu/recon/stargazers)
> A mishmash of scripts for doing recon and investigation via OSINT both passive and active

![Rec0n](docs/images/rec0n-logo.png)

---

> **recon** - */rɪˈkɒn/* (INFORMAL•NORTH AMERICAN)
>
> **noun**
>> *noun: recon; plural noun: recons*
>> 
>> *short for **[reconnaissance](https://dictionary.cambridge.org/dictionary/english/reconnaissance)**.*
>
> .
# Installation

Most of these scripts use *PHP*, *Python* or *Precompiled C*. So here is the quickest way to
install these recon scripts. I will update this section if you need anymore
dependencies...

```
apt-get install php-cli php-curl
apt-get install python
```
Get recon git project & set it up!
```
cd
git clone https://github.com/kawaiipantsu/recon.git
export PATH="$PATH:~/recon/recon-scripts"
```
If you want to always add it to your PATH
```
# LINUX
Add the following.: export PATH="$PATH:~/recon/recon-scripts"
To the bottom of..: ~/.bashrc

# MacOS
Add the following.: export PATH="$PATH:~/recon/recon-scripts"
To the bottom of..: ~/.bash_profile

# Windowns + Gitbash etc
Add the following.: C:\path\to\recon\recon-scripts
Under.............: Advanced system settings->Environment Variables
``` 

# Recon scripts
Just a quick list of the current recon scripts and a direct link to the text file.
- [recon-update](docs/recon-update.txt) - Update the recon scripts from GIT
- [recon-ct](docs/recon-ct.txt) - Do recon on domain names, almost like AXFR
- [recon-ntoo](docs/recon-ntoo.txt) - Lookup danish phone number and find operator






