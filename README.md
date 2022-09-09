# ansible-PVE_Discord_Dark
Ansible role to apply and update the (PVE Discord Dark Theme)[https://github.com/Weilbyte/PVEDiscordDark].

## Usage
playbook.yaml
```
---
- name: Play Name
  hosts: MyHosts
  
  roles:
    - role: notmycloud.pve_discord_dark
      vars:
        theme_version: 2022.03.20   # (Optional) Specify a specific version to install, defaults to the latest release.
        theme_basedir: /opt/PVEDiscordDark  # (Optional) Specify where to download the theme assets.
```

## Support
For support, please raise an issue and provide the following items
- Sample task/playbook to replicate your issue
- Resultant file that is created.
- If modifying an existing file, please provide the unmodified version as well.
