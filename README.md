# Ansible Role: SepForLinux

Installs or upgrades Symantec Endpoint Protection for Linux.

## Requirements

Requires a valid license from Symantec, as well as the software to install.

## Role Variables

sep_target: This is the version of SEP you want to install (e.g., 14.2.5323.2000)<br />
sep_src: Location where you can pull installation package (e.g., /opt/software/SymantecEndpointProtection.zip) <br />
sep_dest: Location from where you will run the install script (e.g., /home/user/SymantecEndpointProtection)<br />

## Dependencies

None.

## Example Playbook
```
 - hosts: linux_servers
   roles:
     - "connellyt.SepForLinux"
```
## License

BSD
