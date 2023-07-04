1. Ir até System > Identity e mudar o nome do roteador.
2. Ir até Interfaces e mudar o nome do interface na qual seu computador está conectado.
3. Ir até IP > Addresses e configurar o endereço de IP tipo C que quiser, indicando a máscara de rede (no caso /24) e a interface renomeada no passo anterior.
4. Para configurar DHCP, ir até IP > DHCP Server e clicar em DHCP Setup, indicar a interface configurada, configurar a lista de IPs caso queira, adicionar o servidor DNS (8.8.8.8 é uma boa) e por fim o lease time do IP.