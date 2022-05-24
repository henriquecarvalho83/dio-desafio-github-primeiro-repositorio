# Configurar Github chave SSH

1. Gerar uma chave SSH
   
   No Git bash utilizar o comando:
   
   SSH-keygen -t ed25519 -C **email cadastrado no Github**

2. Entrar na pasta onde estão as chaves local e publica
   
   cd /C/Users/**usuário**/.ssh/
   
   ls para ver os arquivos
   
   cat id_ed25519.pub --> para mostrar a chave pública
   
   copiar a chave

3. Ir até as configurações no Github
   
   imagem do perfil -> Settings -> SSH and GPG keys -> SSH keys -> New SSH key
   
   colar a chave publica e dar um nome a ela.

4. Iniciar o SSH agent
   
   eval $(ssh-agent -s)
   
   ssh-add id_ed25519
   
   


