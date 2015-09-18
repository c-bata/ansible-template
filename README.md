# ansible-template

This is my ansible template.

## Usage

1. Add private key to `ssh/` directory.
2. Modify `ssh_config` and `hosts`
3. Add ansible task.
4. Run ansible-playbook.
    `ansible-playbook playbooks/playbook.yml` 

## How to use ansible-galaxy.

1. Search galaxy from https://galaxy.ansible.com/ .
2. Run ansible-galaxy command.
    `ansible-galaxy install user.name`

3. Add roles to playbook.

    `- user.name`

4. Run ansible-playbook.


## ansible-galaxy's bookmark

You should watch https://github.com/geerlingguy?tab=repositories

- https://github.com/geerlingguy/ansible-role-nginx
- https://github.com/geerlingguy/ansible-role-elasticsearch
- https://github.com/geerlingguy/ansible-role-gitlab
- https://github.com/geerlingguy/ansible-role-jenkins
- https://github.com/geerlingguy/ansible-role-selenium
- https://github.com/geerlingguy/ansible-role-dotfiles
- https://github.com/geerlingguy/ansible-role-security
- https://github.com/geerlingguy/ansible-role-firewall
- https://github.com/geerlingguy/ansible-role-repo-remi
- https://github.com/geerlingguy/ansible-role-mysql
- https://github.com/geerlingguy/ansible-role-redis

**Others**

- https://github.com/geerlingguy/ansible-vagrant-examples

## License

This template is licensed under the MIT License.

