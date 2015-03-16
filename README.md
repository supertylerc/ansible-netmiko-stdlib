# ansible-netmiko-stdlib

Ansible modules using Netmiko.

## Prerequisites

* [Ansible](https://github.com/ansible/ansible)
* [Netmiko](https://github.com/ktbyers/netmiko)

## Usage

Clone the repository:

```bash
mkdir ~/git
cd ~/git
git clone https://github.com/supertylerc/ansible-netmiko-stdlib
```

Add the following line to you `${HOME}/.bashrc`, `${HOME}/.zshrc`, or the `rc`
file of whatever shell you're using.

```bash
source "${HOME}/git/ansible-netmiko-stdlib/env-setup"
```

> This assumes you cloned the repository to `${HOME}/git/ansible-netmiko-stdlib`.

In order to use this module, you must set the connection to local.  You can
do this with the `connection: local` setting on plays/playbooks, or you can
set the `ansible_connection=local` connection type in the `hosts` file.

## Support

Open GitHub issues.

## Author

Tyler Christiansen

## License

MIT
