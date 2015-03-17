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

Check out
[this blog post](http://blog.tylerc.me/automation/2015/03/16/ansible-netmiko-stdlib/)
for an example of how it can be used.

## Roadmap

See
[the milestones](https://github.com/supertylerc/ansible-netmiko-stdlib/milestones)
for details on the roadmap.  Issues get assigned to milestones as they are opened
or investigated.  Milestones have target release days (generally every 2 weeks
until v1.0.0).

## Support

Open GitHub issues and pull requests.

Please note:

* Bugs will be backported starting with [v0.1.0](https://github.com/supertylerc/ansible-netmiko-stdlib/milestones/v0.1.0).
* Bug fixes will not be assigned to normal versioned milestones.  Instead, they will be assigned to the [Bug Free](https://github.com/supertylerc/ansible-netmiko-stdlib/issues?q=milestone%3A%22Bug+Free%22+) milestone for ensuring a bug free project.
* All features and design docs will be assigned to a versioned milestone.
* Documentation will not be assigned to a milestone (unless it is also a design doc).

## Author

Tyler Christiansen

## License

MIT.  See [LICENSE](LICENSE).
