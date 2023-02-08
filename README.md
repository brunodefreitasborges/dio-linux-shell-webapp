# Script de Instalação de Aplicação Web

Este script é responsável por atualizar e instalar a dependências necessárias para rodar uma aplicação web em sistemas Unix/Linux. Além disso, o script baixa e copia os arquivos da aplicação para o diretório padrão de sites em execução no servidor.

## Recursos
Atualização do sistema operacional.
Instalação do Apache2, necessário para servir a aplicação web.
Instalação do Unzip, necessário para descompactar o arquivo baixado da aplicação.
Baixa dos arquivos da aplicação.
Copia dos arquivos da aplicação para o diretório padrão de sites em execução no servidor.
## Como usar
Faça o clone do repositório para o seu sistema.
Acesse o diretório do repositório clonado.
Conceda permissão de execução ao script: chmod +x script.sh
Execute o script como usuário administrador: sudo ./script.sh
## Considerações
Este script foi testado em sistemas Unix/Linux com o apt-get como gerenciador de pacotes.
É necessário que o usuário que executa o script tenha permissões administrativas (root).
O endereço de download dos arquivos da aplicação pode mudar, verifique se o endereço está correto antes de executar o script.
