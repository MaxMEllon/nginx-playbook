# nginx-playbook

About
---

This playbook is for setup of nginx to hosts.

Usage
---

* remote

```
$ echo [REMOTE_IP] > hosts
$ ansible-playbook -i hosts playbook.yml
```

* local

```
$ echo 127.0.0.1 > hosts
$ ansible-playbook -i hosts playbook.yml --connection=local
```

Requirements
---
* `ansible` >= 2.1.1.0

Reference
---

* [Ubuntuに最新のnginxをインストールする](http://qiita.com/hiroq/items/420424bc500d89fd1cc8)

Author
---
* MaxMEllon (Kento TSUJI) `<maxmellon1994@gmail.com>`
