# ansible-secure-cockroachdb-playbook
Ansible playbook for installing secure cockroach db cluster. 


Run this command to initialize the cluster:
cockroach init --certs-dir=$CERT_DIRECTORY/root --host=[External Node IP]
