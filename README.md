#ceph rbd 动态pvc
ceph 集群正常，已创建rbd pool
k8s集群正常，添加ceph key到secret，添加storageclass填写对应的ceph信息以及ceph.com/rbd作为provider
