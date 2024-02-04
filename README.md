## Procedimento Fork + Pull Request

*Mesmo não que eu não tenha permissão de escrita em um repositório no github, posso enviar contribuições para esse repositório.

### Esse procedimento abaixo é a base para colaboração em projetos de código aberto:



FORK: é quando copio o repositório de outra pessoa do github para o meu github. estou continuando um projeto que veio de outro usuário.
obs. vou fazer um fork de um projeto que não é o meu, vou mexer no projeto e vou mandar uma sugestão para o dono do repositório.

Passo a passo: 
1 Faça um fork do repositório que deseja. obs. todo projeto que entrar para olhar no github, tem o botão do 'fork' e mostra quantas pessoas já 'forkaram' esse projeto. 
2 Clonar o seu repositório 'forkado' para o seu computador.
3 Crie um branch e faça as alterações que desejo. 
git checkout -b ft-readme para criar uma branch onde vou trabalhar nela para fazer as alterações que desejo. 
crio no vscode uma pagina de readme e vou para o gitbash fazer git add . e git commit. 
ainda no gitbash mudo para a branch main com o código git checkout branch main, e faço git pull origin main para atualizar algo do github para o local.
por fim troco para a branch ft-readme com git checkout ft-readme, e faço git merge main , e git push -u origin ft-readme e vou enviar para o meu github. 
ir no github e ver que apareceu um pull request, é um push no meu fork. 
**ATENCAO aqui eu estou fazendo um pull request, e repara que to mandando para o main do outro usuario de onde eu copiei o projeto, nesse caso o prof nelio alves. então aparece para todos essa feature que criei, que eu fiz um pull request lá no repositório do dono do projeto que baixei. Qualquer pessoa pode analisar o meu commit, e participar da discussão. obs. o dono do projeto que é o nelio alves, tem um botão onde ele pode autorizar o pull request ou não. obs e tem a opção de 'close pull request' para eu que criei o pull request, que nesse caso eu estaria desistindo do pull request. 
4 Enviar as alterações para o meu repositório forkado (ja fiz isso no exemplo acima).
5 Crie uma pull request para o repositório original.


### Obs. Essa é a forma de fazer um FORK no projeto de outra pessoa, e fazer uma contribuição para o dono do projeto!!!

