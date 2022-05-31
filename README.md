# toqi-ansible

(⊃＾ω＾)⊃📦

# Deploy with Ansible Playbook

1. edit inventory.yaml
1. execute playbook

```
ansible-playbook -i inventory.ini playbook.yml
```

# Network Settings

## DHCP: static ip address

```
/etc/dhcpcd.conf

interface eth0
static ip_address=192.168.0.xxx/24
static routers=192.168.0.1
static domain_name_servers=8.8.8.8
```

