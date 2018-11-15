This playbook will execute the following tasks:

1. Install RPM-GPG-KEY-EPEL-7 gpg key
2. Add EPEL 7 Repo file
3. Install some base packages. Found in roles/common/vars/main.yml
4. Disable SELinux
5. Configure LDAP
	a. Copy over ldap.conf
	b. Create /etc/openldap/cacerts directory
	c. Copy over ca-bundle
	d. Copy over ldap server crt
6. Configure SSSD
7. Configure nsswitch file
8. Configure system-auth PAM
9. Configure password-auth PAM
10. Make sure 'network' service is enabled and running
11. Stop and disable firewalld
12. Stop and diable NetworkManager
13. Start and enable SSSD service
14. Add CRC/CSSD admins to sudoers
15. Configure chronyd
16. Mount ihome
17. Mount zfs1
