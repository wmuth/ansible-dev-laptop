# ansible-dev-laptop

Ansible development laptop config

This is an ansible project which when run on a fedora install sets up
the system to work the way I want my development laptop to work.

This is based on my previous repo, ansible-personal-config which
I have now been broken up into several smaller repos, of course including this one.

## To run

1. Manually install latest fedora workstation
1. Manuallt install latest ansible
1. Clone this repository
1. `ansible-playbook --ask-become-pass run.yml --extra-vars "reboot=true"`

Omit extra vars if you don't want to reboot at the end of the process.
