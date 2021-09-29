1) Após criado a sua conta no **GitHub**, crie um repositório remoto 
público chamado "**my\_first\_steps**" e cole o link aqui;

Resposta:

[https://github.com/SaruMan64/my\_first\_steps]((https://github.com/SaruMan64/my_first_steps)

2) Crie um diretório em sua máquina e o vincule ao seu repositório remoto 
"**my\_first\_steps**" utilizando os comandos *git* necessários para a 
realização desta tarefa.

Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

Resposta:

```
$ git clone git@github.com:SaruMan64/my\_first\_steps.git
```

3) Dentro do diretório local, crie um arquivo chamado "**ola\_mundo.txt**", 
adicione algum texto da sua preferência e adicione-o ao seu repositório remoto 
utiliazndo os comandos *git* necessários para a realização desta tarefa.

Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

Resposta:

```
$ cat >> ola_mundo.txt
$ git add.
$ git commit -m "Adicionando oficialmente o arquivo ola_mundo.txt."
$ git push
```

4) Se não existir em seu diretório, adicione ao seu diretório um arquivo com o 
nome de "**.gitignore**". Em seguida, crie um arquivo chamado "**serei\_ignorado.txt**" 
e adicione algum texto dentro dele. Adicione a instrução ao arquivo "**.gitignore**" 
para que as alterações realizadas no arquivo "**serei\_ignorado.txt**" não seja controlado
pelo *git*.

Cole aqui o conteúdo que você utilizou no "**.gitignore**" para realizar esta tarefa.

Resposta:

```
$ touch .gitignore
$ ls -lha
$ git status
$ cat >> serei_ignorado.txt
$ echo serei_ignorado.txt >> .gitignore
$ cat .gitignore
$ git status
$ git add .
$ git commit -m "Criando .gitignore e adicionando arquivo para ser ignorado."
$ git push
```