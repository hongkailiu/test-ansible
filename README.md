# test-ansible

Tested with CentOS minimal installation

```sh
$ cat /etc/*release
CentOS Linux release 7.3.1611 (Core)
```

```sh
$ docker --version
Docker version 17.03.1-ce, build c6d412e
```

```sh
$ cd centos
$ ansible-playbook -i ./hosts site.yml  --ask-become-pass
```
