<img align="right" height="90" width="100" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" />

## Olá!!! Este é meu projeto para estudos e compartilhamento de conhecimentos que tenho sobre Git!

* Repositório em constante mudança e adição de conhecimentos;

  ​


### Alguns termos iniciais:

---------

* Git: sistema de versionamento de código;

 - Master - main: Linha cronológica principal (é criada quando inicia o repositório);

 - Branch: ramificação da linha cronológica principal (pode se criar uma linha cronógica da Branch);

 - Commit: salvar a nova versão do projeto com um comentário que remete as alterações;

 - Merge: junção da(s) Branch(es) com a linha cronólogica principal;

 - Remote: repositório remoto;

 - Push: envia / "empurra" ao repositório remoto;

 - Pull: "puxa" o que está no repositório remoto;

 - arquivo README.md: é o arquivo que aparece quando você entra em um reporitório;

 - Colar no terminal: insert OU Ctrl + Shift + v;

 - Limpar terminal: clear OU Ctrl + l;

   ​


### Comandos principais:

--------

* git init: iniciar / criar um repositório local (na sua máquina) vazio;

 - git add + nome_arquivo: manda o(s) arquivo(s) para a área de stage (esperando commit) - pode ser mais de um arquivo ao mesmo tempo;

 - git add *: manda todos os arquivos disponíveis para a área de stage;

 - git commit -m + "escreva aqui seu commit": para comitar os arquivos que estão na área de stage;

 - git status: mostra o estado dos arquivos do repositório;

 - git branch -M "main: quando você cria um repositório, cria-se junto a linha cronológica principal chamada de Master, mas pode ser usado o nome de Main para se referir a essa linha, então esse comando basicamente renomeia de Master --> Main; 

   ​


### Comando repositório remoto (GitHub):

---------

* git remote add origin(apelido) + (URL do repositório criado no GitHUb): conexão do repositório local com repositório remoto, e para se referir a ele damos um apelido que por padrão é "origin"; 

 - git remote -v: mostra todos os repositórios remotos daquele repositório local;

 - git push -u origin (master OU main): "empurra" a branch principal, se você permaneceu com o nome master no comando você digita "master" e se você renomeou para main no comando você digita "main";

- //quando clicar no commit pelo github vai abrir o arquivos e as linhas vermelhas que aparecem estão sinalizando as mudanças / alterções do commit anterior para esse;

  ​

### Criando uma Branch:

-------

* git checkout -b "nome-da-branch": criar uma nova branch e o comando -checkout- troca da branch atual para a branch que você criou;


* git checkout "nome-da-branch": muda para mandar que você solicitar;
* para subir pro GitHub: git push origin "nome-da-branch";

- **Merge:** para fazer um merge entre a main / master com outra branch que você criou:
  - git checkout main OU master: para mudar para a branch principal;
  - git merge "nome-da-branch": comando para fazer um merge entre a principal e a branch criada;

