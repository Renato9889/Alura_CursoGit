# Alura_CursoGit
Curso de git e github da alura
Crie a pasta;
Na pasta do projeto, execute o comando git init para inicializar um repositório Git;
Execute o comando git status para garantir que você está em um repositório Git;
Execute o comando git add “nome do arquivo” para marcar o arquivo para ser salvo (commitado);
Execute git status e confira que o arquivo agora mudou de estado e está pronto para ser salvo (commitado);
Após adicionar, execute o comando git commit -m "sua mensagem aqui";
Execute o comando git log e analise a sua saída. Execute também git log --oneline, git log -p. 
Crie um arquivo vazio com o nome que quiser, por exemplo, ide-config;
Crie o arquivo .gitignore e adicione uma linha com o nome do arquivo recém-criado (ide-config, no exemplo acima);
Execute git status e verifique que o arquivo ide-config não está na lista para ser adicionado;
Adicione (com git add .gitignore) e realize o commit (com git commit -m "Adicionando .gitignore") o arquivo .gitignore.
 Criar pasta servidor na pasta do projeto, executar git init –bare
Navegue até a pasta onde se encontra o seu projeto;
Execute o comando git remote add local {caminho}. Substitua {caminho} pelo caminho completo da pasta recém criada;
Crie uma nova pasta em seu computador, para representar o trabalho de outra pessoa;
Execute o comando git clone {caminho} projeto. Substitua {caminho} pelo caminho completo da pasta que criamos no primeiro passo;
Acesse a pasta Projeto e execute o comando 'git remote rename origin local' para renomear o repositório local da outra pessoa de "origin" para "local";
Navegue até a pasta onde se encontra o seu projeto original;
Execute o comando git push local main para enviar as suas modificações para o seu servidor;
Navegue até a pasta criada;
Execute o comando git pull local main para baixar as modificações;
Abra o seu navegador e acesse http://github.com/;
Crie um novo repositório, clicando no símbolo de adição no canto superior direito;
No terminal (ou Git Bash, no Windows) adicione, ao seu projeto inicial, o repositório remoto recém criado (os comandos são mostrados pelo próprio GitHub);
Execute git push origin main para enviar as suas alterações para o repositório no GitHub.
