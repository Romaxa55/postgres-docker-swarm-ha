FROM quay.io/coreos/etcd:v3.5.8

# Задаем кастомный CMD
CMD /usr/local/bin/etcd \
    -name=${ETCD_NAME} \
    -advertise-client-urls=${ETCD_ADVERTISE_CLIENT_URLS} \
    -listen-client-urls=http://0.0.0.0:2379 \
    -initial-advertise-peer-urls=${ETCD_INITIAL_ADVERTISE_PEER_URLS} \
    -listen-peer-urls=http://0.0.0.0:2380 \
    -initial-cluster-token=etcd-cluster-1 \
    -initial-cluster=${ETCD_INITIAL_CLUSTER} \
    -initial-cluster-state=new