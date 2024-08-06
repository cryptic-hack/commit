# Inicialize o repositório Git
git init

# Adicione os arquivos ao repositório
git add hello_world.py README.md .gitignore

# Faça o commit inicial
git commit -m "Primeiro commit: adicionar hello_world.py e arquivos de configuração"

# Adicione o repositório remoto (substitua a URL pelo seu repositório)
git remote add origin https://github.com/seu-usuario/seu-repositorio.git

# Envie os arquivos para o repositório remoto
git push -u origin master
