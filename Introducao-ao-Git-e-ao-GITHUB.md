mkdir livro-receitas // criou um repositório chamado livro-receitas
dir e ls // lista os arquivos dentro do repositório
ls -a // lista os arquivos ocultos dentro do repositório
cd / // caminha dentro do diretorio  "Cd / vai para o repositório c"
cd .. // volta um nivel no repositório
Ctrl l // limpa a tela
git init // cria um novo repositório .git
echo strogonoff>strogonoff.txt // criou um arquivo chamado strogonoff.txt
git status //  exibe o estado do diretório de trabalho e da área de teste
mv strogonoff.md  ./receitas // moveu o arquivo strogonoff.md para o repositório receitas
git remote -v // lista os repositórios remotos cadastrados

Como subir repositório para o github:

*Create a new repository no github
*git remote add origin https://github.com/andrenccosta/livro-receitas.git //no git ... subi um repositório chamado livro-receitas.git
*git push origin master 

