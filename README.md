# BionicAptPackagesRepo
For OTUS-2021 HomeWork and may be something else.


How to use:
===

sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://mar94ok.github.io/BionicAptPackagesRepo/my_list_file.list"

curl -s --compressed "https://mar94ok.github.io/BionicAptPackagesRepo/KEY.gpg" | sudo apt-key add -

sudo apt update


Many Thanks to the origin:
===
https://assafmo.github.io/2019/05/02/ppa-repo-hosted-on-github.html
