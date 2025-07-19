docker build -t my-etcd:latest .
docker run -d --name etcd-server -p 2379:2379 -p 2380:2380 my-etcd:latest