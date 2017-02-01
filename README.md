This ansible playbook will install Docker Engine 1.12.5 on CentOS 7
and configure it appropriately to join a swarm.

Starting with Docker Engine 1.12, the live restore setting is available.
This setting will keep containers alive when the docker daemon
becomes unavailable, but it is incompatible with swarm mode. This playbook
disables live restore so your node can join a swarm. 




