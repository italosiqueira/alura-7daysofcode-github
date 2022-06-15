# alura-7daysofcode-github
Repositório da iniciativa #7DaysOfCode da Alura, tema GitHub.

Elaborado por Fabrício Carraro, Product Owner e Instrutor na Alura.

# Roteiro

## Dia 01

Criar um repositório do zero a partir da própria página do GitHub.

### Exercício Opcional

Como um desafio opcional, pesquise como alterar a descrição do seu perfil para adicionar as suas habilidades e deixá-lo estilizado. Solte a sua criatividade e deixe essa página a mais legal possível!

### Dica

Escolha um nome bem autoexplicativo para os seus repositórios, assim, eles serão encontrados mais facilmente por você e, quem sabe, outras pessoas desenvolvedoras no futuro.

Ao criar o repositório, é interessante adicionar uma boa descrição e deixar a visibilidade como "Pública", para que outras pessoas possam contribuir com o seu projeto.

Para o exercício opcional, você terá que alterar o arquivo "Readme" do seu repositório pessoal. Caso não queira pesquisar, você terá mais informações sobre isso na seção "Extra".

### Extra

A Alura tem um [artigo excelente](https://www.alura.com.br/artigos/o-que-e-git-github) criado pelo Paulo Silveira ([@paulo_caelum](https://twitter.com/paulo_caelum)) que você pode ler para ter uma ideia melhor inicial sobre GitHub.

[Neste vídeo](https://www.youtube.com/watch?v=TsaLQAetPLU), a Rafaella Ballerini mostra como personalizar o seu arquivo "_**Readme**_" pessoal para deixar o seu perfil lindo!

E tem também [este ótimo artigo](https://www.alura.com.br/artigos/escrever-bom-readme) com várias dicas mais avançadas de como você pode estilizar o seu arquivo "_**Readme**_".

## Dia 02

A primeira parte do seu desafio hoje será **criar no seu repositório os arquivos HTML e CSS que eu compartilhei [neste template](https://github.com/fabriciocarraro/7DaysOfCode-GitHub), mas isso será feito diretamente a partir da própria página do seu repositório no GitHub, copiando e colando o código manualmente**. Assim que cada arquivo for criado, você deverá realizar o *commit* do mesmo, ao final da página.

A segunda parte do desafio será **fazer o upload de uma pasta "*images*" para o repositório**, contendo as 4 imagens compartilhadas no template acima.

### Dica

Ao realizar um *commit*, sempre escolha uma mensagem muito clara e, de preferência, iniciada com verbos no presente ou no gerúndio.

Para fazer o upload de uma pasta, você pode criá-la localmente na sua área de trabalho com as imagens ou arquivos desejados e selecionar a opção "**Upload Files**".

### Extra

Se você nunca utilizou o Github, calma! Eu tenho o vídeo perfeito para te ajudar nessas primeiras atividades de criação de repositório e adição de arquivos: [GitHub sem linhas de comando](https://www.youtube.com/watch?v=vhqTiQdUHfY).

Você também pode assistir [essa live](https://www.youtube.com/watch?v=nec3n02idMw) que debulha tudo sobre GitHub para iniciantes.

## Dia 03

Hoje, você vai começar a usar uma IDE para continuar brincando com o seu repositório. Recomendo o uso do [Visual Studio Code](https://code.visualstudio.com/download).

Para poder conectar a sua conta GitHub ao Visual Studio Code, você terá que [fazer o download e instalação do Git](https://git-scm.com/downloads) também.

Tendo tudo isso instalado, o seu desafio de hoje será **clonar o seu repositório criado no GitHub para editá-lo localmente, pela sua IDE**.

### Dica

A IDE do Visual Studio Code te dá a opção de clonar um repositório qualquer a partir de uma URL ou a partir de sua conta no GitHub. Você pode associar a sua conta e fazer isso diretamente, ou então ir na página do seu repositório, na aba "**Code**", e copiar a URL disponibilizada lá (escolha a da aba HTTPS).

### Extra

Esse [artigo](https://www.alura.com.br/artigos/visualstudio-code-instalacao-teclas-de-atalho-plugins-e-integracoes) explica como instalar, usar atalhos e dá outras dicas sobre o Visual Studio Code.

## Dia 04

Hoje, você vai continuar a fazer coisas a partir da IDE. Uma grande vantagem de usar uma IDE como o Visual Studio Code é que fazer alterações no código torna-se uma tarefa muito fácil.

O template que você está utilizando, do jeito que está agora, está muito básico e genérico. O mesmo filme está sendo repetido três vezes, o texto de descrição não tem nada relevante e a imagem também está igual para todos.

A primeira parte do seu desafio de hoje será **alterar o arquivo "_index.html_" a partir do Visual Studio Code para que você tenha três filmes diferentes, cada um com a sua descrição, imagem e nota correspondente**.

Quando essas alterações estiverem prontas, você irá salvar o arquivo e, ao fazer isso, notará que, do lado esquerdo da tela, aparecerá um número "1" ao lado da aba "**Source Control**". Isso quer dizer que há uma alteração no seu código em relação ao código que foi baixado do repositório.

Se você clicar duas vezes no nome do arquivo "_index.html_" visto acima, o Visual Studio Code abrirá uma nova janela e você poderá ver claramente onde foram feitas todas as alterações no código.

A segunda e mais importante parte do desafio de hoje será **realizar o commit dessas alterações que você fez no código**. Você fará o commit diretamente a partir da aba "**Source Control**" do Visual Studio Code e passando uma mensagem explicando sobre o que se tratam as alterações.

### Exercício Opcional

Outra coisa que você pode fazer para praticar os seus conhecimentos é usar os comandos do Git diretamente no Terminal do Visual Studio Code.

Para abrir o Terminal, basta ir na aba superior "_Terminal_" e selecionar "_New Terminal_".

### Dica

Para alterar as imagens, basta trocar a URL encontrada em:

`<img src="URL_DA_IMAGEM" alt="DESCRIÇÃO_DA_IMAGEM"/>`

Já o texto de descrição pode ser encontrado dentro da tag `<span></span>`.

Escolha uma mensagem relevante e clara ao realizar o _commit_, para que você mesmo (e outros) no futuro saibam exatamente de que se trata.

### Extra

Esse [vídeo](https://www.youtube.com/watch?v=BAmvmaKQklQ&list=PLh2Y_pKOa4Uf-cUQOVNGlz_GVHx8QYoE6&index=2) dá uma boa explicação sobre a base do Git e como funcionam os commits.

A Alura [tem um artigo excelente para você aprender melhor os comandos do Git que são usados no Terminal](https://www.alura.com.br/artigos/comecando-com-git-aprendendo-versionar).

## Dia 05

Primeiramente, você irá abrir o seu arquivo "index.html" no Visual Studio Code. Altere algo que vá quebrar o seu código (como o fechamento de uma ‘div’ ou de um ‘h2’) e faça o commit e o Push dessas alterações para a sua master. Pode tentar abrir o "index.html" para ver o erro.

O seu desafio de hoje será **reverter esse commit para remover o erro do seu código**.

### Dica

Para o desafio de hoje, é preferível você usar os comandos diretamente no Terminal do Visual Studio Code, assim como no Exercício Opcional de ontem.

### Extra

[Neste vídeo](https://www.youtube.com/watch?v=hISBlHMb-0Y&list=PLh2Y_pKOa4Uf-cUQOVNGlz_GVHx8QYoE6&index=7), o Mário Souto (Dev Soutinho) explica como reverter um commit mal feito.

## Dia 06

Em breve.