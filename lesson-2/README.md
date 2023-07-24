Домашнее задание: Работа с mdadm

Цель: Vagrantfile, который сразу собирает систему с подключенным рейдом (10) и смонтированными разделами. После перезагрузки стенда разделы должны автоматически примонтироваться.

`$ sudo mdadm --detail --scan --verbose`
```
ARRAY /dev/md0 level=raid10 num-devices=6 metadata=1.2 name=otuslinux:0 UUID=59f8097b:de88bac2:c2c6dd89:89d821c7
devices=/dev/sdb,/dev/sdc,/dev/sdd,/dev/sde,/dev/sdf,/dev/sdg
```
