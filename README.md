# provision-mac

A set of `ansible` config to quickly setup my new macs.
Shamelessly inspired (and some time copied) from [geerlingguy/mac-dev-playbook], (lwalley/ ansible-role-iterm2), (gantsign/ansible-role-oh-my-zsh), (sicruse/ansible-powerline-fonts).

To use:
```
> sudo pip3 install --upgrade pip
> pip3 install ansible
> git clone https://github.com/sleeper/provision-mac.git
> cd provision-mac
```
Then copy your `config.yml` in `provision-mac` directory, and

```
> ansible-galaxy install -r requirements.yml
> ansible-playbook main.yml --ask-become-pass
> # Enter password when prompted for the 'BECOME' password
```
