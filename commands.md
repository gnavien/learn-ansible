# ansible -i 172.168.0.x, all -m ping -e ansible_user=centos -e ansible_password=DevOps321

The above command will ping the specified machine and return a pong response.

# We can also ping the specified machine and return a pong response by passing the host name 
# in a file.
 
# ansible -i /tmp/inv all -m ping -e ansible_user=centos -e ansible_password=DevOps321