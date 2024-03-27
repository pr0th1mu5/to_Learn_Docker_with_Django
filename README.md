# Tutorial para criação de um Docker em nuvem com Django.
### Repositório descritivo do processo de implantação de uma aplicação Django simples em nuvem AWS.

> Os passos a seguir foram realizados para configurar uma aplicação Django em nuvem utilizando o serviço EC2 da aws.amazon
###### [Clique aqui para ser direcionado ao site e criar sua conta na aws.amazon](http://aws.amazon.com)

1. Após criar sua conta na aws.amazon, crie uma instância EC2. A utilizada para essa configuração segue a configuração abaxi:
2. Sistema Operacional: Ubuntu Server;
3. Tipo da Instância: t3.micro (2 núcleos de processamento e 1gb de ram);
4. Armazenamento: Alterado para 20gb
> [!IMPORTANT]
> Durante a criação da sua instância guarde em local acessível o arquivo de chave de acesso .pem para conseguir se conectar à sua instância.


1. Atualizei os pacotes
2. Atualizei o sistema upgrade
3. Verifiquei a instalação do python3
4. Instalei o docker com snap install
5. Instalei o virtualenv para criar o ambiente virtual isolado
6. Realizei o clone do projeto django do github
7. Utilizei o pip intall -r requirements.txt para instalar o django e todas as dependências do projeto
8. Criei o arquivo Dockfile com as informações do projeto, dependências e do local para carregar os arquivos no servidor
9. Crie a imagem docker com comando docker build -t <nome_do_projeto> . (o ponto referencial a pasta atual no servidor. Esse comando demorou)


    
