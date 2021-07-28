# foo 

```
git clone https://github.com/01-01-1970/foo.git
cd foo
```

as user
```
ansible-playbook -i inventories/ playbooks/we-play-for-life.yml --ask-become-pass
```

as root
```
ansible-playbook -i inventories/ playbooks/we-play-for-life.yml
```
