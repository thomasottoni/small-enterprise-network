# Security Policy

## ACL Rules

- HR VLAN is restricted from accessing the Finance VLAN
- IT VLAN has unrestricted network access
- Inter-VLAN communication is permitted unless explicitly denied by ACL policy

## Hardening

- Unused ports disabled
- Enable secret configured
- Password encryption enabled
- Management VLAN implemented
- SSH remote management configured
- Port-security enabled on access interfaces
- Unused ports assigned to an isolated parking VLAN
