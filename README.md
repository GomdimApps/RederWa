
# Documentação de Instalação do RederWA Bot de Automação do WhatsApp

Esta documentação fornece instruções passo a passo sobre como instalar e configurar o RederWA, um bot de automação do WhatsApp, no dispositivo Android.

## Requisitos

Antes de prosseguir com a instalação do RederWA verifique seguintes requisitos:

Para instalar o RederWA no seu celular android, você deve atender aos seguintes requisitos:

- Celular Android 6.0 ou superior.
- Termux instalado no dispositivo. [Baixar Termux](https://github.com/termux/termux-app/releases/download/v0.118.0/termux-app_v0.118.0+github-debug_x86_64.apk).
- Um editor de JSON. [Baixar Editor](https://play.google.com/store/apps/details?id=com.tuyware.jsongenie).

Para instalar o RederWA no seu computador, você deve atender aos seguintes requisitos:

1. Instale o Gitbash. Você pode baixá-lo [aqui](https://git-scm.com/downloads).
2. Instale o Node.js LTS. Você pode baixá-lo [aqui](https://nodejs.org/en/download/).
3. Instale o VSCode [aqui](https://code.visualstudio.com/Download) ou Notepad++ [aqui](https://notepad-plus-plus.org/downloads/v8.5.4/)

Depois de instalar essas ferramentas, você estará pronto para instalar o RederWA no seu PC.


## Instalação pelo celular [ANDROID]

1. Abra o aplicativo Termux no seu dispositivo Android.
2. Execute o seguinte comando para conceder acesso à memória: 
```
termux-setup-storage
```
<br>
<img src="documentação/img/001.png" alt="Instruções de Extração" />
<br>
Clique em "Permitir" quando solicitado para conceder acesso à memória do dispositivo.

<img src="documentação/img/002.png" alt="Instruções de Extração" />
<br>
3. Crie uma pasta chamada "RederWA" no seu gerenciador de arquivos antes de prosseguir.
<br>
<img src="documentação/img/003.png" alt="Instruções de Extração" />
<br>
4. Volte para o aplicativo Termux e execute o seguinte comando: 

```
cd /sdcard/RederWA/
```
 Esse comando irá mudar o diretório atual para a pasta "RederWA" recém-criada no seu armazenamento interno.
<br>
<img src="documentação/img/004.png" alt="Instruções de Extração" />
<br>

## Extrair o Bot

Após ter feito a compra do bot, nossa equipe lhe enviará um arquivo ZIP contendo o bot RederWA. Siga as instruções abaixo para extrair o arquivo dentro da pasta "RederWA":

1. Após receber o arquivo ZIP, localize-o no seu dispositivo Android.
2. Abra o gerenciador de arquivos do seu dispositivo e navegue até a pasta "RederWA".
3. Extraia o conteúdo do arquivo ZIP para dentro da pasta "RederWA".
4. Certifique-se de que todos os arquivos e pastas do bot foram corretamente extraídos e estão dentro da pasta "RederWA".

Agora você concluiu o processo de extrair o bot RederWA dentro da pasta "RederWA". Você está pronto para prosseguir com as etapas de instalação e iniciar o bot conforme descrito anteriormente.

Lembre-se de que o arquivo ZIP fornecido pela equipe do RederWA contém todos os arquivos necessários para o funcionamento adequado do bot. Certifique-se de extrair todo o conteúdo do arquivo para a pasta correta antes de iniciar o bot.

Se você tiver alguma dúvida ou encontrar algum problema durante o processo de extração, não hesite em entrar em contato com nossa equipe de suporte para obter assistência adicional.

Agora você está pronto para instalar as dependências necessárias para o RederWA.

## Instalar Dependências no Termux

1. No Termux, com o diretório apontando para a pasta "RederWA", execute o seguinte comando: 
  ```
  bash install.sh
  ```
 Esse comando iniciará o processo de instalação das dependências necessárias para o funcionamento do bot.
 <br>
 <img src="documentação/img/005.png" alt="Instruções de Extração" />
 <br>

2. Aguarde o procedimento de instalação ser concluído. Isso pode levar alguns minutos, dependendo da velocidade da sua conexão com a internet. Certifique-se de que o dispositivo esteja conectado a uma rede estável durante esse processo.

3. Depois que terminar a instalação o bot vai avisar.

 <img src="documentação/img/006.png" alt="Instruções de Extração" />

## Configurar Informações da Empresa

Após a instalação do bot RederWA, é necessário configurar as informações da empresa dentro do bot. Para fazer isso, vamos usar um editor JSON e modificar o arquivo "usuario.json". Siga as etapas abaixo:

1. Acesse a pasta "RederWA" no seu dispositivo.
2. Procure a pasta "usr" dentro da pasta "RederWA".
3. Dentro da pasta "usr", você encontrará um arquivo JSON chamado "usuario.json".
4. Abra o arquivo "usuario.json" usando um editor JSON de sua escolha.
5. Dentro do arquivo, você poderá configurar as informações do atendimento da empresa, como nome, descrição, horário de funcionamento, entre outros.
6. Salve as alterações feitas no arquivo "usuario.json" após configurar as informações da empresa.

Agora você concluiu a configuração das informações da empresa dentro do bot RederWA. As informações atualizadas serão utilizadas nas interações do bot com os usuários.
Ainda não inicie o bot.

## Instalação pelo Computador [WINDOWS e LINUX]

Configurando o RederWA

1. Baixe o arquivo enviado pela nossa equipe.

    <img src="documentação/img/007.png" alt="Instruções de Extração" />

2. Entre na pasta onde o arquivo foi baixado e extraia os arquivos do bot.
   
    <img src="documentação/img/008.png" alt="Instruções de Extração" />

3. Instale as ferramentas necessárias, como o VSCode e o Gitbash.

    <img src="documentação/img/009.png" alt="Instruções de Extração" />

4. Abra o VSCode e abra a pasta do bot pelo VSCode.

    <img src="documentação/img/010.png" alt="Instruções de Extração" />

    <img src="documentação/img/011.png" alt="Instruções de Extração" />

    <img src="documentação/img/012.png" alt="Instruções de Extração" />
5. Dentro do VSCode, na pasta do bot, procure a pasta "usr".

    <img src="documentação/img/013.png" alt="Instruções de Extração" />

6. Dentro dessa pasta, há um arquivo chamado "usuario.json".
7. Abra esse arquivo e preencha as informações da sua empresa ou negócio:

 ```
{ 
  “NomeDono”: “Carlos”,
  “NomeEmpresa”: “Linxy Corporation”,
  “numeroDono”: “559391057890”, 
  “grupoVendas”: “120363129598125491”, 
  “TextAtendimento”: “Olá” 
}
 ```

   <img src="documentação/img/014.png" alt="Instruções de Extração" />

8. Depois de inserir suas informações no arquivo aberto no Visual Studio Code, você deve pressionar as teclas `Ctrl + S` para salvar as alterações feitas. Em seguida, você pode fechar o Visual Studio Code. Isso garantirá que suas alterações sejam salvas com sucesso.

## Dialogflow

Nesta seção, vamos abordar a integração do bot RederWA com o Dialogflow, uma plataforma de processamento de linguagem natural. Para configurar essa integração, siga as etapas abaixo:

1. Crie uma conta no Dialogflow:
   - Visite o site do Dialogflow (https://dialogflow.cloud.google.com/#/) e crie uma conta.
   - Faça login no Console do Dialogflow usando suas conta google.
2. Obtenha as credenciais de uso (API key) do Dialogflow: veja o video.

 [<img src="https://docs.kony.com/marketplace/ChatbotV3/Content/Resources/Images/Chatbot_DialogflowV2_JSONFile.png" alt="descrição da imagem" width="1280" height="720">](https://www.youtube.com/watch?v=lUVT6r5-NrE)

# Configurando o arquivo de credenciais do Dialogflow e Painel

1. Baixe o arquivo JSON de credenciais do Dialogflow.
2. Coloque o arquivo JSON na pasta `BOTWA > session`.
3. Renomeie o arquivo para `credencial.json` para que o bot possa reconhecê-lo.

    <img src="documentação/img/015.png" alt="Instruções de Extração" />

Com essas etapas, você terá configurado corretamente o arquivo de credenciais do Dialogflow para uso com o bot.


4. Crie um novo agente no Dialogflow para o seu bot RederWA:
   - No Console do Dialogflow, crie um novo agente.
   - Configure as intenções (intents), entidades (entities) e respostas do seu agente de acordo com as interações desejadas. veja nossa playlist de como usar o dialogflow.

 [<img src="https://www.kommunicate.io/blog/wp-content/uploads/2021/10/19-1.png" alt="descrição da imagem" width="1280" height="720">](https://www.youtube.com/playlist?list=PLlqXqdYg2QK-0zy8XLFdqbanEAv-rqKa_)


Agora você possui uma conta no Dialogflow e as credenciais de uso necessárias para a integração com o bot RederWA. Certifique-se de utilizar essas credenciais corretamente durante o processo de configuração do bot.

Caso precise de mais informações ou suporte adicional sobre o uso do Dialogflow, consulte a documentação oficial fornecida pelo Dialogflow ou entre em contato com a equipe de suporte do serviço.



## Iniciar o Bot

Após a conclusão da instalação das dependências, você está pronto para iniciar o bot RederWA. Siga as instruções abaixo:

1. No Termux, certifique-se de que o diretório atual seja a pasta "RederWA".
2. Execute o seguinte comando para iniciar o bot: 
```
npm start
```
3. Aguarde alguns instantes até que o bot seja iniciado com sucesso. Você verá as informações de log e o QR code no terminal.
4. Use o WhatsApp no seu dispositivo para ler o QR code e fazer login no bot.
5. Após o login bem-sucedido, o bot estará pronto para automatizar tarefas no WhatsApp.

Lembre-se de que o comando `npm start` só deve ser executado após a instalação das dependências necessárias. Certifique-se de ter concluído o processo de instalação antes de iniciar o bot.

**Observação:** É importante manter o Termux em execução em segundo plano para que o bot continue funcionando. Se você fechar o aplicativo Termux, o bot também será encerrado.

Agora você concluiu a instalação e configuração do RederWA no seu dispositivo Android. Você pode começar a explorar os recursos e funcionalidades do bot para automatizar suas interações com o WhatsApp.
