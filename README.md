# Primeiro-repositorio-github---Dio
Repositorio criado para o desafio de projeto do curso da Dio sobre github

comando do git

#### git init

- inicializa um novo repositório



#### git config --global  user.email "e-mail"

- configuração global configurar e-mail

#### git config --global user.name "nome"

- configurar um autor 

 

#### git status

- status dos arquivos alterado, repositorio ...



#### git add *

-  envia todos os arquivos para controle de  versão local .

#### git commit -m" mensagem "

- preparar o controle de versão local para nuvem 



#### git push origin main 

- envia o commit para nuvem 





# Criação de chave SSD e tokken 



#### ssh-keygen -t ed25519 -C seu e-mail

enter

vai pedir para criar uma senha após isso a chave será criada

## visualizar o conteudo das chaves 

#### cat arquivo com a chave

cat id_ed25519.pub

ele irá mostrar achave publica 

#### Iniciar o conteudo que irá iniciar as chaves

##### eval $(ssh-agent -s)

entregar a chave para o agent 

#### ssh-add id_ed25519

enter + senha da chave

