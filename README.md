# DVM Ansible Role

## Description

Opinionated Ansible role to install the DVM Project binaries on a site.

## Requirements

Debian or Ubuntu based system (including a Raspberry Pi), `apt`, and an AMD64, ARM64 or ARM32 CPU.

## Role Variables

| Variable | Description | Default | Required |
|----------|-------------|---------|----------|
| use_netbird | Set this to true if Netbird is installed on the host | false | No |
| dvm_folder | Set this variable to use a custom folder name throughout the role | dvm | No |

## Limitations

- This role only supports P25.  While DVM supports DMR and NXDN, I did not add support for configuring them as part of this role.
- This role does not *yet* support DVRS mode.  Support for DVRS mode is planned in the future.

PRs are welcomed if you want to help add support for either of those things.

## Example Playbook

Please refer to the CANTACS dvm-deploy repo for a detailed playbook.
