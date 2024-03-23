# Tamarutaca

<p align="center">
  <img src="https://github.com/gcomartins/tamarutaca/assets/93291851/2e494e6d-ceac-4db3-a180-77b8f8c9d70f" width="300">
</p>

Este repositório tem a finalidade de centralizar estudos de Offensive Cybersecurity.

## Fundamentos

<details>
  <summary>Linux</summary>

  <details style="margin: 20px">
    <summary>Comandos de Navegacao</summary>
    <ul>
      <li>/ : Representa a Raiz do Sistema</li>
      <li>~: É usado para representar a pasta pessoal do usuário.</li>
      <li>$ : Identifica o usuário comum logado no sistema.</li>
      <li># : Identifica o usuário root logado no sistema.</li>
    </ul>

  </details>

  <details style="margin: 20px">
    <summary>Diretorios</summary>
    <ul>
      <li>/ : Raiz do sistema</li>
      <li>/BIN : Comandos e utilitários usados por todos os usuários.</li>
      <li>/SBIN: Comandos e utilitários que só podem ser utilizados pelo root</li>
      <li>/BOOT: Contem os arquivos necessários para a inicialização do sistema.</li>
      <li>/LIB: Contem as bibliotecas essenciais que o sistema necessita.</li>
      <li>/PROC :Contem informações sobre hardware e o S.O da máquina.</li>
      <li>/VAR: Contém arquivos com conteúdo muito variado:</li>
      <li>/ROOT: Arquivos ou diretórios pessoais do usuário root (ou super usuário)</li>
      <li>/HOME: Arquivos e diretórios pessoais dos usuários ( com exceção do root)</li>
      <li>/USR: Contém todas as configurações e programas instalados pelos usuários.</li>
      <li>/ETC: Contém os arquivos de configuração de quase tudo no Linux.</li>
      <li>/DEV: Arquivos de dispositivos de hardware:</li>
    </ul>
  </details>
</details>

<details >
  <summary >Rede</summary>
  <details style="margin: 20px">
  <summary >Portas</summary>
  As portas de um computador vão de 0 a 65.535, onde até 255 são para aplicativos públicos, até 1023 para comerciais e acima disso não são regulamentados.

  | Porta | Protocolo | Serviço               |
  |-------|-----------|-----------------------|
  | 7     | TCP       | Echo                  |
  | 11    | TCP       | Systat                |
  | 13    | TCP       | Daytime               |
  | 19    | TCP       | Chargen               |
  | 20    | TCP       | FTP Data              |
  | 21    | TCP       | FTP                   |
  | 22    | TCP       | SSH                   |
  | 23    | TCP       | Telnet                |
  | 25    | TCP       | SMTP                  |
  | 43    | TCP       | Whois                 |
  | 53    | TCP       | DNS-zone              |
  | 53    | UDP       | DNS-lookup            |
  | 80    | TCP       | HTTP                  |
  | 443   | TCP       | HTTPS                 |
  | 1433  | TCP       | MS_SQL                |
  | 8080  | TCP       | Proxy/Socks           |
  </details>
    <details style="margin: 20px">
  <summary >Mascaras de rede</summary>
    A mascara de uma subrede indica a classe que o host se encontra:
    
| Máscara de Sub-rede | Classe | Notação CIDR |
|---------------------|--------|--------------|
| 255.0.0.0           | Classe A | /8 (8 bits) |
| 255.255.0.0         | Classe B | /16 (16 bits) |
| 255.255.255.0       | Classe C | /24 (24 bits) |

  </details>
</details>



## Ferramentas de Reconhecimento

<ul>
  <li><a href="https://www.shodan.io/">SHODAN.IO</a>: Search Engine for the Internet of Everything</li>
  <li><a href="https://www.shodan.io/">WHO.IS</a>: WHOIS Search, Domain Name, Website, and IP Tools</li>
</ul>
