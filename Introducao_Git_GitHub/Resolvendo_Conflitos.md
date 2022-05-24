# Resolvendo Conflitos

- Quando existirem alterações no GitHub e o Git está desatualizado
  
  git pull origin master
  
  - Verificar qual alteração será mantida
  
  - salvar arquivo
  
  - agora só seguir o procedimento padrão
    
    git add *
    
    git commit -m "**Mensagem**"
    
    git push origin master

- Erro na mensagem co commit
  
  git commit --amend -m "**Mensagem corrigida**"
  
  git push --force-with-lease origin --> nunca fazer isto quando se está trabalhando com colaboradores
