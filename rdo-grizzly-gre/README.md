Install RDO Grizzly with Quantum networking and layer 2
connectivity provided by GRE tunnels.

- Install the Cirros image
- Creates a `m1.nano` flavor that uses 256MB of RAM
- Sets up a public network (`public`) and a private network (`net0`)
- Configures NAT rules on the network host to provide outbound
  connectivity to `br-ex`

