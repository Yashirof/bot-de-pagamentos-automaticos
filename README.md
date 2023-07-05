# Bot de Pagamentos Automáticos
Este é um bot de pagamentos automáticos desenvolvido em JavaScript para realizar transações financeiras de forma automatizada. Ele utiliza a biblioteca Discord.js para se integrar ao Discord e processar comandos relacionados a pagamentos.

Instalação
Siga as instruções abaixo para configurar e executar o bot em seu ambiente local:

Certifique-se de ter o Node.js instalado em sua máquina. Você pode baixá-lo em https://nodejs.org.

Clone este repositório para o diretório desejado em sua máquina:

git clone https://github.com/Yashirof/bot-de-pagamentos-automaticos.git

Acesse o diretório do projeto:

cd bot-de-pagamentos-automaticos ou use crtl + L e digite cmd 

Instale as dependências necessárias utilizando o npm (gerenciador de pacotes do Node.js):

npm install

Crie um arquivo de configuração config.json na raiz do projeto e insira as informações necessárias. Você pode utilizar o arquivo config.example.json como referência.

Execute o bot:

node index.js

Agora o bot estará online e pronto para processar comandos de pagamentos no seu servidor do Discord.

# Requisitos
Node.js (versão 14 ou superior)
Discord.js (biblioteca JavaScript para integração com o Discord)

# Configuração
Antes de executar o bot, é necessário configurar algumas informações no arquivo config.json.

token: O token de autenticação do seu bot Discord. Você pode obter esse token ao registrar um bot no Portal de Desenvolvedores do Discord.
prefix: O prefixo que será utilizado para identificar os comandos do bot. Por exemplo, se definido como "!", os comandos serão iniciados com !.
Certifique-se de que as informações de configuração estejam corretas para garantir o funcionamento adequado do bot.



