# Manual de instalação do Git

Este é um tutorial para integrar o Git/Github com o VScode no linux.

1. sudo apt-get install git
2. configurar: git config --global user.email "seu_email@exemplo.com"
               git config --global user.name "Seu Nome Completo"
3. ssh-keygen -t rsa -b 4096 -C "seu_email@exemplo.com"
4. Crio o repositório no github
5. Colar o projeto no terminal com a chave ssh -> git clone git@github.com:projeto/instalacao.git
6. No VSC - Abra a pasta do projeto
7. Commit as mudanças 
8. Push

---------------------------
Fetch: Verificam se há alterações no repositório, mas não faz o download das mesmas.
Pull: Faz o download das alterações
Commit: Salva as alterações locais que você fez, mas não envia as mesmas para o servidor.
Push: Envia as alterações locais salvas (commits) para o servidor.
