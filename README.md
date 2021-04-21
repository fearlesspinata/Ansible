# Ansible
Repository for various Ansible Playbooks/Projects

## Installation
Required packages:
- Ansible
- Python
```bash
sudo apt-get install ansible
```

## Usage
The dev.yml playbook can be run to get your local dev environment setup using powerline fonts, tmux and zsh.
The zshrc file that is included already has default settings in place that I user personally but you're free to
customize it and adjust the themes. I'd recommend just mixing and matching just to see what works for you.

```bash
ansible-playbook -u <username> -K -i inventory/local.ini playbooks/dev.yml
```

## More playbooks to come...
