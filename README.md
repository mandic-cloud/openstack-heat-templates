# Templates heat #

Varios exemplos de templates do OpenStack Heat

### autoscaling.yaml ###

Exemplo básico de autoscaling
* Sem balanceador de carga

### LB-HAproxy.yaml ###

Exemplo básico de implementação de um balanceador de carga numa VM.
* Sem alta disponiblidade

### LB-HAproxye-VRRP ###

Exemplo básico de implementação de um balanceador de carga numa VM com alta disponibilidade usando VRRP.
* Uso de allowed_pair_adresses
* Uso de antiafinidade de servidores para garantir que as VMs não ficam nos mesmos compute nodes.

### servidor-web ###

Exemplo básico de um servidor web.
* Uso de cloud-init para a configuração inicial do servidor
* Uso de security groups
* Assignação de floating ips

### vpn ###

Criação de um vpn gateway usando ipsec.
