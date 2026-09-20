A simple role to install [Commando](https://gitlab.hax0rbana.org/public-repos/meshtastic/commando) as a service.

# Examples
## Playbook
Below is an example of a playbook to set up commando.

```yaml
- hosts: all
  become: true
  roles:
    - role: hax0rbana_adam.commando
```

# Official repo location
All activity takes place on the official GitLab instance:
[https://gitlab.hax0rbana.org/public-repos/ansible/ansible-role-commando](https://gitlab.hax0rbana.org/public-repos/ansible/ansible-role-commando)

Any other hosting providers, such as GitHub.com and GitLab.com, are just mirrors
and we do not monitor the issue trackers over there.

# Support
## Matrix channel
You can also join our Matrix channel: #ansible:hax0rbana.org

This is a good place to ask questions or make requests without having to sign
up for another account.

# Contributing
See [contributor guidelines](CONTRIBUTING.md).

# License
This project is licensed under MIT License. See [LICENSE](LICENSE) for more details.
