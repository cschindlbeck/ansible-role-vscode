# Ansible Role: Visual Studio Code

This role installs and configures Visual Studio Code.

## Requirements

This role supports the following operating systems:

- Ubuntu
- Fedora
- Archlinux
- macOS

## Role Variables

- `is_wsl`: A boolean variable that should be set to `true` if the target machine is a Windows Subsystem for Linux (WSL) environment. This is used to determine the correct paths for VS Code configuration files.

## Dependencies

None.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
    - ansible-role-vscode
```

## License

MIT

## Author Information

This role was created in 2025 by [Chris](https://www.chriscol.in).
