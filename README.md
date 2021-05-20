# :wave: Manipulaçao de Arquivos 

## 🤓 Resumo

Objetivo dessa atividade é praticar manipulaçao de arquivos em C++ 🚀

Espera-se que ao final seja capaz de criar, editar, buscar informaçoes e fechar arquivos e compreender os principais conceitos por tras dessas açoes. 

## 💻 Termos para saber

### Arquivo 
é um conjunto de dados, dispostos de forma sequencial

### buffer 
pode ser usado para acelerar a leitura e escrita de arquivos

### Cursor
Um cursor é associado ao arquivo de forma a indicar a próxima posição a ser lida ou gravada.
O cursor é inicializado com 0 na abertura do arquivo.
O cursor é incrementado a cada operação de leitura ou escrita no arquivo.

### Abertura de arquivo
Deve-se associar um stream a um arquivo e realizar uma operação de abertura 
Após a abertura, informações podem ser trocadas entre o arquivo e o seu programa 
A operação de abertura inicializa o cursor

### Fechamento do Arquivo
A operação de fechamento de arquivo desassocia o arquivo do stream 
Libera a memória (equivalente ao free p/ memória alocada dinamicamente) 
Se um arquivo aberto para escrita for fechado, o conteúdo de seu buffer associado é escrito no arquivo para evitar perda de conteúdo

## 🗄: Atividade

Em C, cada stream associado a um arquivo tem uma estrutura de controle de arquivo do tipo FILE 
Essa estrutura é definida no cabeçalho stdio.h, que deve ser incluído em todos os programas que manipulam arquivos

### Execute os arquivos de exemplo para:

- criar arquivo
- escrever e gravar registros no arquivo
- buscar um registro dentro do arquivo
- fechar o arquivo

## 📝 Passos

* Abra uma pull request para que a professora saiba que encerrou a atividade.  
* Crie um outro documento como esse tipo markdown para escrever o que aprendeu ou que ainda tem duvida. * Crie seu README pessoal. Deixe o mundo saber mais sobre voce. O que gostaria de aprender? Qual seu hoby? Aprenda mais sobre criar documento README em: ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).

## 📚  Recursos: 
* [Cplusplus Files](http://www.cplusplus.com/doc/tutorial/files/) 


