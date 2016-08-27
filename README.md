Run Mesos Master Command for docker:
```
 mesos-master --ip=172.17.0.2 --work_dir=/var/lib/mesos
```

Run Mesos Slave command for docker:
```
mesos-slave --master=172.17.0.2:5050 --work_dir=/var/lib/mesos --launcher=posix --no-systemd_enable_suppor
```
