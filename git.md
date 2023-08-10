# Somente na primeira configuração do computador
git config --global user.name "Pedro"
git config --global user.email "henriquepedrodutra@gmail.com"

# Somente no inicio do projeto
git init

# Sempre que uma atualização for feita no projeto
git add .
git commit -m "mensagem para o commit"
git push

# Sempre que for baixar o projeto em outro computador
git clone sitedoprojeto.git

# Sempre que for atualizar o projeto na maquina com atualização que foram feitas de outro computador
git pull