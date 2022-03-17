# OpenStack Xena



## 1、 chrony
```bash
  dnf install chrony
  systemctl enable chronyd.service
  systemctl start chronyd.service
```


## 2、 openstack packages
```bash
  dnf install centos-release-openstack-xena
  dnf config-manager --set-enabled powertools
  dnf upgrade
  dnf install python3-openstackclient
  dnf install openstack-selinux
```

## 3、 database with mariadb

## 4、 redis

## 5、 network

## 6、 storage

## 7、 
