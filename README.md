# Comandos Iniciais

Criar um repositório 
    
    git init

Criar um repositório Git sem uma cópia dos arquivos 

    git init --bare
    
Analisar o estado do repositório
        
    git status

Adicionar arquivos para serem commitados

    git add <nome_arquivo>

Commitar arquivos

    git commit -m "mensagem de identificacao do commit"

# Histórico de commits

oneline
    
    git log --online

verificar alterações        

    git log -p
    
# Log com parametros de formatação

    git log --pretty="parametros de formatação"
            
Retorna apenas os hash
    
    git log --pretty="format:%H"

Retorna hash resumido seguido pela mensagem do commit

    git log --pretty="format:%h %s"
        
# Repositório remoto
    
lista repositório remoto

    git remote

lista de repositórios + caminhos
        
        git remote -v

adicionar repositório remoto

    git remote add <nome> {caminho}
    
remover um repositorio remoto

    git remote remove <nomeDoRepositório>

clonar um repositório

    git clone {caminho} 
    
