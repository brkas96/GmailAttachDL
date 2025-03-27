# Auto Attachment Downloader for Gmail


:rocket: **Support this project**: [![Patrocine este projeto](https://img.shields.io/badge/-Sponsor-fafbfc?logo=GitHub%20Sponsors)](https://github.com/sponsors/brkas96)

:rocket: **Contact**: brkas_dev@proton.me

# ABOUT :white_check_mark:

-This project was written in Python and utilizes the Gmail APIs to automate the process of monitoring and 
downloading attachments from Gmail accounts. By integrating with the Gmail API, the program can access and manage 
email data, enabling efficient attachment retrieval based on specific criteria such as unread emails in the inbox.

-This automation was developed and tested on Windows 10.

-This program is an automation tool that monitors and downloads attachments from Gmail accounts. It supports multiple 
accounts, meaning you can monitor and download attachments from several Gmail accounts. However, only one account is 
processed at a time to avoid exceeding the Gmail API usage limit and to comply with Google's usage policies.

-The program will only download emails from the INBOX, which is Gmail’s main inbox. Emails must be marked as unread; 
read emails will be ignored.

This program is under development.
More features will be added over time.

# HOW TO USE :white_check_mark:

This guide assumes that you already know how to create and configure a project using APIs in Google Cloud. If not, 
I recommend reading the official documentation at the link below.

📖 **Gmail API Documentation**: https://developers.google.com/gmail/api/guides?hl=en-us

1. First, log in to: Google Cloud Console
2. Create a new project in Google Cloud.
3. Enable the Gmail API for your project.
4. Generate the API credentials in the Google Cloud dashboard.
5. Download the credentials.json file and place it in the same folder as the program.
6. Rename the credentials file to credentials.json.
7. Start the program and add your first Gmail account by logging in through the browser.


# Compiling the Script :white_check_mark:

-The program's executable is located in the dist folder of the project. 

-But, if you want to compile the script yourself, create a virtual environment and install the required libraries 
listed in the **requirements.txt** file.

-To install the required libraries in the virtual environment via terminal: `pip install -r requirements.txt`

-After installing the libraries, use **PyInstaller** to compile the program using the gmail_api.spec file with the 
following command: `pyinstaller gmail_api.spec`


# Baixar Anexos do Gmail automaticamente (PT-BR)

Apoie este projeto: [![Patrocine este projeto](https://img.shields.io/badge/-Sponsor-fafbfc?logo=GitHub%20Sponsors)](https://github.com/sponsors/brkas96)

Contato: brkas_dev@proton.me

# SOBRE

-Esta automação foi desenvolvida e testada no Windows 10

-Esse programa é uma automação que monitora e baixa anexos de contas do Gmail. Ele suporta multiplas contas, ou
 seja, vc pode deixar baixando e monitorando várias contas Gmail, porém somente uma conta por vez, para não exceder
 o limite de uso da API do Gmail e nem ir contra as diretrizes de uso definidas pela Google.
 O programa baixará somente os emails da INBOX, que é a caixa de entrada principal do Gmail. Os emails devem estar
 marcados como unread(Não lidos). Emails lidos seram ignorados.

 Programa em desenvolvimento.
 Mais funcionalidades seram implementadas ao longo do tempo.

# COMO USAR
-Primeiro você deve fazer login em: https://console.cloud.google.com/apis/library  

-Crie um projeto no Google Cloud

-Ative a API do Gmail para o seu projeto

-Gere as credenciais de API no painel da Google Cloud

-Baixe o credentials.json e coloque na mesma pasta do programa

-Renomeie o arquivo com as credenciais para credentials.json

-Inicie o programa e adicione sua primeira conta Gmail fazendo login pelo navegador

Documentação da API do Gmail: https://developers.google.com/gmail/api/guides?hl=pt-br

# Compilando o script
-Caso você mesmo queira compilar o script, basta criar um ambiente virtual e realizar a instalação das bibliotecas
necessárias que estão no arquivo requirements.txt.

-Comando para instalar as bibliotecas no ambiente virtual via terminal: `pip install -r requirements.txt`

-Após instalar as bibliotecas, use o **Pyinstaller** para compilar o programa através do arquivo gmail_api.spec com o 
seguinte comando: `pyinstaller gmail_api.spec`

