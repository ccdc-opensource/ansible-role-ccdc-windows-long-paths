# Ansible Role: Allow paths longer than 260 characters

This role applies the (registry fix)[https://docs.microsoft.com/en-us/windows/win32/fileio/naming-a-file#enable-long-paths-in-windows-10-version-1607-and-later] that allows removing MAX_PATH limitations from common Win32 file and directory functions starting in Windows 10, version 1607.

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - windows-long-paths

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas