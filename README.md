# ipoque

```
git clone https://github.com/01-01-1970/ipoque.git
cd ipoque
```

as user
```
ansible-playbook -i inventories/ playbooks/we-play-for-life.yml --ask-become-pass
```

as root
```
ansible-playbook -i inventories/ playbooks/we-play-for-life.yml
```