```shell
git@github.com:dtgoitia/arch-gnome-i3.git
cd arch-gnome-i3
vagrant up
```

User: `root`
Pass: `vagrant`


Provision only the Ansible part:

```bash
vagrant provision --provision-with ansible_local
```
