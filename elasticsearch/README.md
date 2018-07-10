# ELASTIC SEARCH

**before lunch**:

- *hostname setting*
```
sudo vi /etc/sysconfig/network
HOSTNAME=elastic-1.gsgr
sudo reboot
```

- *max map count setting*
```
sudo sysctl -w vm.max_map_count=262144
```
