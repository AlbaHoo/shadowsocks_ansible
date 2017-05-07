# About the repo:
a ansible script to setup a shadowsocks in Ubuntu server

## Command line
`ansible-playbook -s install_ss.yml -i ./inventory/hosts`

`ansible-playbook -s insall_ss.yml -i ./inventory/hosts --limit xbox`

---

Configure the ssh to server setting to your own server*`./inventory/hosts`*, in my case I used Linode.
