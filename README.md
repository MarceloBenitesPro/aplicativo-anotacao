


<img align="center" height="200em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/2a25a41ccbb59380ac357bf39d266d64/raw/20098ea90c6cda8fde50022f01c6a72355377694/githubicone.svg" />

# 🖊 Aplicativo Anotação 

## Informações Sobre o Aplicativo
* [Sobre](#Sobre)
* [Configurando ambiente de trabalho](#Configurando-ambiente-de-trabalho)
* * [Instalando o Visual Studio Code](#Instalando-o-Visual-Studio-Code)
* * [Instalando o NodeJs](#Instalando-o-NodeJs)
* * [ReactJs](#ReactJs)
* * * [Instalação-Expo](#Instalação-Expo)
* [Iniciando o Aplicativo](#Iniciando-o-Aplicativo)
* [Criando a build do app e instalando](#Criando-a-build-do-app-e-instalando)
* [Requesitos](#Requesitos)
* [Tecnologia](#Tecnologia)

## Sobre

Este é um aplicativo desenvolvido para fazer anotações de maneira simples e que o usuario podera usar no dia a dia.
Ele é feito através da linguagem NodeJS  o ReactJS é feito para a linguagem Mobile para Android e IOS.
Ele possue a dependencia do expo o que deixa a aplicação muita mais leve de ser aplicada.

<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/ad376aabbaecf3a9b1272ef5a8199511/raw/9a1a99e4f02dd02afa14933697cbc8ff226e59a5/githubcard2.svg" />
<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/80eebcb07218fccda4dbab191a342780/raw/854bdc497fb9885593b423e910d5a81ca24e4068/githubcelular2.svg" />
 

<br />
##   🛠 Configurando ambiente de trabalho
<br /><br /><br /><br />
### Instalando o Visual Studio Code
</br>

Antes de começar , você vai precisar fazer o download e instalar o <a href="https://code.visualstudio.com/">VSCODE</a> Versao 2022 a mais conhecida no mercado na area de programação aonde eu instalei as minhas dependencias.
<br /><br />
<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/30549fccc9719e9e718759bfd3022f3e/raw/81cab19a174c9461d3f167cec561d29bf45788e7/githubcodeinfo.svg" />
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
<br /><br /><br /><br /><br /><br /><br /><br />
###  Instalando o NodeJs
</br></br>
Para gerenciar o reactjs você precisa instalar o NodeJs para isso você precisa ir no site do node e fazer o download da ultima versao v16.15.1 LTS após fazer o download é só clicar no botão verde e ele começará imediatamente, faça o download da versão LTS por ele ser estável.
Após isso de next até o final para o nodejs ser instalado.
<br /><br /><br />
<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/fb8be27fb7db2a35888cda34a9a428ec/raw/075fb83545c44fd9f6038cf1dfd4a03b1a193d4e/githubnode.svg" />
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />

Para você testar se o node js foi instalado você precisa acessar o cmd no seu sistema e dar os comandos que estarão aqui abaixo.

```bash
C:\User\user>node -v
<!---Serve-para-ver-a-versão-do-node-->
v16.15.1
C:\User\user>npm -v
6.14.5
C:\User\user>
````
### ReactJS
<br/>
O React Native mudou de documentação e ele recomenda a usar o expo.

### Instalação-Expo
Para instalar o expo na maquina você acessa o cmd do seu computador

```bash
C:\User\user>npm install -g expo-cli
````

E após isso aperte enter para ver se foi instalado basta dar este comando no cmd

```bash
C:\User\user>expo --version
3.21.10
````
Para ver outras documentações do expo acesse o site <a href="https://expo.dev/"></a> e faça o seu cadastro na expo.

<br  />

## Iniciando o Aplicativo

Vamos iniciar o aplicato com o reactjs e com o expo para isso para isso va no desktop 

```bash
C:\User\user>cd desktop
C:\User\user\desktop>
C:\User\user\desktop>expo init "Projeto_01"
````
Isso serve para você criar o seu projeto.
Para ter acesse ao projeto do repositório , bastar fazer o downlond da pasta , como já tenho o expo instalado, você tem que entrar dentro da pasta baixada e dar o seguinto comando no cmd.
```bash
C:\User\user>cd desktop
C:\User\user\desktop>
C:\User\user\desktop>cd "Projeto_App_Agendamento"
C:\User\user\desktop\Projeto_App_Agendamento>expo start
````

Para ter acesso ao projeto recomendo instalar no seu aplicativo do seu celular o expo.
<br /><br /><br /><br />
<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/57ea09a06b35441232f4fcbd1a8a9485/raw/78ec81bd1debd110111ee489418ca20eac1e825b/githubappexpo.svg" />
<br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br /><br />
<br /><br /><br /><br />
<br /><br /><br /><br />
<br /><br /><br /><br />
Após o comando expo start aparecerá o QrCode no aplicativo tem a opção QrCode scaneie o QrCode do seu celular com o QrCode do computador.

<br /><br /><br /><br />
```bash
Microsoft Windows [versão 10.0.19044.1706]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\user>cd desktop

C:\Users\user\Desktop>cd "Projeto_App_Agendamento"

C:\Users\user\Desktop\Projeto_App_Agendamento>expo start
Starting project at C:\Users\user\Desktop\Projeto_App_Agendamento
Developer tools running on http://localhost:19002
Starting Metro Bundler
▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄▄
█ ▄▄▄▄▄ █▀▄█▀     █ ▄▄▄▄▄ █
█ █   █ █▄   ▄██▀ █ █   █ █
█ █▄▄▄█ █ ▀█▀█▄▀ ██ █▄▄▄█ █
█▄▄▄▄▄▄▄█ ▀▄█ █▄▀ █▄▄▄▄▄▄▄█
█  █ ▀█▄ ▀█ ▀▄ ▀██▀  ▄▀▄▄▀█
█  ▀ ▀▀▄▀▀▄▄█▄ ▀▀▄▄▀ ▀▀█▄▄█
█▄█▄▄▀ ▄▄█▀▀██▄ █▀█ ▄█ ██▀█
█▄▀ ███▄▀▄█▄ ▄▀ █ ▄▄ ▀▀██▄█
█▄▄▄▄█▄▄▄▀▄▄▀██▄  ▄▄▄ █ ▄ █
█ ▄▄▄▄▄ █▄ █▀▄▄▄  █▄█  ▀▄ █
█ █   █ █▀█ ▄█ ▀▀▄ ▄▄ █▀▄██
█ █▄▄▄█ █▀▄▀██ ▄█  █▄  ▄█▄█
█▄▄▄▄▄▄▄█▄▄█▄█▄▄█▄███▄▄█▄▄█

› Metro waiting on exp://192.168.100.245:19000
› Scan the QR code above with Expo Go (Android) or the Camera app (iOS)

› Press a │ open Android
`````

<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/a5ff1b78a17edd8fad94b993f6b63622/raw/c21af20bd499d6c0070e6e296fef8c68e0dccae1/githubQrCodeApp.svg" />
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
<br /><br /><br /><br /><br /><br />
Quando você der o expo start aparecera o endereço do localhost:19002 clique nele para ir ao servidor.

```bash
C:\Users\user\Desktop\Projeto_App_Agendamento>expo start
Starting project at C:\Users\user\Desktop\Projeto_App_Agendamento
Developer tools running on http://localhost:19002
````

<img align="left" height="500em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/ab984e5e25882c234a2119bbe0b7e643/raw/e0642a49d8fe434a4d58d1840cc4c4e31d1e18ec/githullocalhostapp.svg" />
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
<br /><br /><br /><br /><br /><br />

Você pode acessar o seu aplicativo com a web apertando a tecla w.

## Criando a build do app e instalando

* 1- Para visualizar a build acesse o site da expo.
* 2- Abra o Projeto "Projeto_App_agendamento" no VSCode
* 3- No arquivo app.json esta configurado para instalar a build com este codico aqui,e obrigatorio ter este codico se não não ira funcionar.
  <br /> <br /> 
<img align="left" height="300em" src="https://raw.githubusercontent.com/gist/MarceloBenitesPro/c969663e29cb679d13a4ece4349687fb/raw/14629e9858fbe87f26e7b47af6725da81a760d03/githubappjsona.svg" />
  <br /> <br /> <br /> <br /> <br /> <br /> 
"android":{
      "package":"com.app.swapp",
      "versionCode":1
    },
    <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> <br /> 
    
* 4- Para Exportar o aplicativo temos que ir no terminal cmd prompt e colocar estes comandos aqui
atenção este comando ios muda para ipk de vez de ser apk.

```bash
C:\Users\user\Desktop\Projeto_App_Agendamento>expo build:android
````

* 5- Após isso aparecerá uma opção em azul clique em apk.
* 6- após isso aparecerá uma conta atenticação clica na segunda opção caso você já tenha uma conta na expo.
* 7- Em sequida perguntara o email da conta cadastrada coloque lá e a senha também.
* 8- Com isso ele será instalado com sucesso!
* 9- Irá aparecer um endereço de url na instalação é só copiar e colar
* 10- Com o cabo USB do seu celular conectado ao computador digite o seguinte comando.

```bash
C:\Users\user\Desktop\Projeto_App_Agendamento>adb install meuapp.apk
C:\Users\user\Desktop\Projeto_App_Agendamento>adb install meuapp.apk
Performing Streamd Install
Success
C:\Users\user\Desktop\Projeto_App_Agendamento>
````
E pronto o seu app foi instalado no seu celular

## Tecnologia
<br /><br /><br /><br /><br /><br />















