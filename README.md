# TeleDownloader

O TeleDownloader é uma ferramenta Python que permite baixar vídeos automaticamente de um canal do Telegram.

## Configuração no Site do Telegram

Antes de usar o TeleDownloader, você precisa configurar um aplicativo no site do Telegram para obter suas credenciais de API. Siga estas etapas:

1. Acesse https://my.telegram.org/auth e faça login em sua conta do Telegram.
2. Clique em "API Development Tools".
3. Preencha o formulário com as informações solicitadas para criar um novo aplicativo.
4. Anote o "API ID" e o "API Hash", pois você precisará deles para configurar o TeleDownloader.

## Configuração do Ambiente

1. Clone este repositório em sua máquina local:

git clone https://github.com/seu_usuario/TeleDownloader.git
cd TeleDownloader

2. Crie um arquivo .env na raiz do projeto e adicione suas credenciais do Telegram:

API_ID=sua_api_id
API_HASH=sua_api_hash
PHONE_NUMBER=seu_numero_de_telefone

## Instalação de Dependências

Certifique-se de ter o Python instalado em sua máquina. Em seguida, instale as dependências usando o pip:

pip install -r requirements.txt

## Execução do TeleDownloader

Para executar o TeleDownloader, siga estas etapas:

1. Execute o seguinte comando para iniciar o programa:

python tele_downloader.py

2. O programa exibirá um menu onde você pode escolher entre baixar vídeos ou contar mensagens.

3. Selecione a opção desejada e siga as instruções fornecidas pelo programa.

## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues para relatar problemas ou sugerir melhorias.

## Licença

Este projeto é licenciado sob a licença MIT.
