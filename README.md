# Setup Fedora

## Run setup
```sh
sudo dnf install ansible git dnf5 -y
cd /tmp
git clone https://github.com/CamilleKoestli/Setup.git
cd setup
ansible-playbook playbook.yaml -K # or --ask-become-pass, eventually with -v for verbose mode it if fails
```
## Manual steps
- pdf studio
- virtualbox
- antidote
