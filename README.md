# GitMicroblog
:book: GitMIcroblogging do DevComputaria - Transformando commits 

[![Join the chat at https://gitter.im/dotnet/csharplang](https://badges.gitter.im/dotnet/csharplang.svg)](https://gitter.im/DevComputariaCE/community) 
[![Chat on Discord](https://discordapp.com/api/guilds/804917151059935242/widget.png)](https://discord.gg/jxbC46p3mk)
[![Gitmoji](https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg?style=flat-square)](https://gitmoji.dev)


## Inspirado no projeto [Logit](https://github.com/agentofuser/logit) 

### Join the LogitVerse

```
mkdir logit
git init
git commit --allow-empty -m "Hello world"
hub create # if you're using github
git push --set-upstream origin master
# optional: follow me ;)
git remote add marcialwushu https://git.sr.ht/~marcialwushu/DevComputaria
git fetch marcialwushu
git log marcialwushu/marcialwushu
```

### Feed RSS 

Podemos tambem transformmar o nosso historico de commit em um canal RSS entrando na área de commits do repositório e inserir ```.atom``` no final da URI 

- <https://github.com/DevComputaria/grupo-de-estudo/commits/main.atom>

### Passo a Passo 

#### Commits vazios com apenas a DevMessagem

Como não será codificado nada nesse projeto propriamente dito, como efetuar um commit no projeto sem alterações para subir no repositório 

Será usado um commit vazio passando apenas a sua ```DevMessagemComputaria```

```
git commit --allow-empty -m "DevComputaria on the line"
```

#### Cabeçalho e Corpo das mensagens dos commits organizado

**PRIMEIRO METODO**

```
git commit -m "Title" -m "Description ..........";
```

Aonde cada conteudo adicioando com ```-m``` será um paragrafo e efetuará uma quebra de linha no corpo da mensagem do commit 

Ou podemos fazer da seguinte forma para adicionar quebra de linha na mensagem do commit : 

```
git commit -a -m $'Commit title\n\nRest of commit message...
```


**SEGUNDO METODO**

Use o comando git commit sem sinalizadores. O editor configurado será aberto (Vim neste caso):

![](https://camo.githubusercontent.com/7649d864e3ac18d1b6413b085ac9306c0f892a929dd11e090454225ec7865865/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f66383061692e706e67)

Para começar a digitar pressione a tecla INSERT em seu teclado, então no modo de inserção crie um commit melhor com a descrição que você deseja. Por exemplo:

![](https://camo.githubusercontent.com/10323de4f47b410cee4146f35fe7dc75f11e2f07ee22a6e1f7eaf0186273ca9d/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f5051424b332e706e67)

Depois de ter escrito tudo o que você precisa, para retornar ao git, primeiro você deve sair do modo de inserção, para isso pressione ESC. Agora feche o editor do Vim e salve as alterações digitando no teclado: wq (w - escrever, q - sair):

![](https://camo.githubusercontent.com/42852ffaaa2b6a383f71b41086ce9ce7d7c3427d50cd87bbb6d4fbcf6fc616f2/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f43634143592e706e67)

e pressione ENTER.

No GitHub, esse commit será semelhante a este:

![](https://camo.githubusercontent.com/4aea19f27952c2862c9e770448a46accb4e433c0157f3a7f7cc5197d26e41270/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f714b34374b2e706e67)

**TERCEIRO METODO**

Como editor de commit, você pode usar o VS Code:

```
git config --global core.editor "code --wait"
```

Do site de documentos do VS Code: VS Code as Git editor

![](https://camo.githubusercontent.com/bf5f7978d906c64eeb81ddf2cb1d9fb83c7ad125a2fb4c89eecafb8c6aebe917/68747470733a2f2f692e737461636b2e696d6775722e636f6d2f70643465712e676966)


## Usando emojis nas mensagens dos commits

Usar emojis em mensagens de commit fornece uma maneira fácil de identificar o propósito ou intenção de um commit olhando apenas para os emojis usados. Como existem muitos emojis diferentes, podemos usar como referência o projeto [Gitmoji](https://github.com/carloscuesta/gitmoji), mas tambem podemos consultar a documentação no projeto com uma lista de todos os emojis em markdown suportados para utilização na mensagens de commit, exemplo: 

```
:memo: Adicionado documetação ao projeto
```

:memo: Adicionado documentação ao projeto

## Feeds I know

- @DevComputaria: <https://github.com/DevComputaria>


