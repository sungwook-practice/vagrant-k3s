# 준비
* vagrant
* virtualbox
* Ram 4GB이상

# 실행방법
```shell
vagrant up --provider=virtualbox
```

# 원격접속
```shell
vagrant ssh

$ sudo su
$ kubectl get no
```

# 삭제방법
```shell
vagrant destroy --force
```