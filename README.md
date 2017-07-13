# ansible_playbooks

This is an Ansible playbook to upgrade all packages on Debian/Ubuntu.

Steps:


Check if there are any packages to be upgraded on the server.

If yes, upgrade all packages that need upgrades.

Check if server requires a restart after the upgrade.

If yes, restart the server. If not, continue to next step.

Exit with code=success.


Requirements:

Debian/ Ubuntu Linux 12.04+

su privilege.
