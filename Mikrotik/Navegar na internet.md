# Computadores
Para fazer com que os computadores conectados no Mikrotik naveguem na internet:
1. Ir em IP > Firewall
2. Clicar em NAT e adicionar novo NAT
3. Em Chain, deixar srcnat
4. Out. Interface recebe a interface de saída ([Nesse caso por IP](obsidian://open?vault=Notas&file=Mikrotik%2FAdicionar%20conex%C3%A3o%20com%20a%20WAN%20por%20DHCP))
5. Em Action, selecionar masquerade (masquerade deve ser usado quando a interface com a rede é feita através de DHCP).