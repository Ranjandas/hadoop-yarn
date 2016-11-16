# hadoop-yarn

Install ansible > 2.2.0

```
curl -LO http://releases.ansible.com/ansible/ansible-2.2.0.0-0.2.rc2.tar.gz
pip install ./ansible-2.2.0.0-0.2.rc2.tar.gz
```

## Start the containers and network

```
ansible-playbook container.yml -c local
```
[![asciicast](https://asciinema.org/a/98uh7n5b4fqu1wqhlmztp5jkw.png)](https://asciinema.org/a/98uh7n5b4fqu1wqhlmztp5jkw)
