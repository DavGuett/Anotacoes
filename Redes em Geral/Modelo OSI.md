# Nome
Significa "Open Systems Interconnection"

# Camadas
## Camada 7 - Aplicação
É a camada que interage diretamente com o usuário e softwares como navegadores utilizam os protocolos dessa camada para realizar a comunicação com o usuário.
Exemplo de uso: Protocolo HTTP

## Camada 6 - Apresentação
É a camada que realiza a preparação dos dados para que a camada de aplicação possa usar, tornando-os apresentáveis.
Exemplo de uso: HTML

## Camada 5 - Sessão
É a camada responsável por abrir e fechar sessões de comunicação entre os dispositivos, fechando assim que não for mais necessário e sincronizando a transferência de dados.
Exemplo de uso: Comunicação entre o navegador Chrome e algum servidor Apache.

## Camada 4 - Transporte
Responsável pela ocorrência da comunicação de fato entre dispositivos, dividindo os dados da camada de sessão em segmentos e enviando para a camada 3.
Exemplos de uso: TCP na porta 80/443 e UDP

## Camada 3 - Rede
Responsável pela comunicação entre endereços lógicos de rede, dividindo os segmentos da camada de transporte em partes menores chamadas de pacotes no dispositivo que está enviando e remontando os pacotes no dispositivo que está recebendo.
Exemplos de uso: Internet Protocol (IP)

## Camada 2 - Enlace de Dados
Também chamada de link de dados, realiza a comunicação entre os endereços físicos da rede através por exemplo do ARP e do endereço MAC.
Exemplos de uso: ARP, endereço MAC

## Camada 1 - Física
Camada de abstração mais baixa, comunicação é feita através dos bits 0 e 1 e pelo meio de comunicação do componente usado para a rede, como o rádio no caso do wi-fi, elétrico no cabo de par trançado e luz no caso da fibra ótica.
Exemplos de uso: cabo de rede ethernet, sinal wi-fi.
