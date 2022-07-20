# <img src='https://upload.wikimedia.org/wikipedia/commons/thumb/1/15/Logotipo_IFET.svg/573px-Logotipo_IFET.svg.png' height='28'/>  Sistema de gerenciamento da monitoria 
Projeto de TCC cujo objetivo é desenvolver um sistema para gerenciar o processo de seleção e acompanhamento do monitor no IFAL - Campus Palmeira dos Índios. Clique [aqui](https://sistema-de-monitoria-ifal.vercel.app/) pra testar.

## 👩🏽‍💻 Equipe de desenvolvimento

### Alunos

 📸 | Nome | Email
| --- | --- | --- |
 <img src='https://github.com/JaianeOliveira.png' height='30' /> | [Jaiane Oliveira](https://github.com/JaianeOliveira) | <jaianeoliveira.dev@gmail.com>
 <img src='https://github.com/TheusGabriel.png' height='30' /> | [Matheus Gabriel](https://github.com/TheusGabriel) | <matheugmalmeida@gmail.com>
 


### Professor Orientador

- [Ítalo Arruda](mailto:italo.arruda@ifal.edu.br)

## 🚧 Como rodar o projeto na sua máquina
Clone o projeto na sua máquina
```
$ git clone https://github.com/JaianeOliveira/sistema-de-monitoria-ifal
```
em seguida, dentro da pasta do repositório clonado, instale as dependências do projeto com o comando
```
$ yarn
```
agora é só executar com 
```
$ yarn start
```

## ✨ Padrões de projeto

### Sistema de branches
A branch `main` equivale ao *ambiente de produção*, a branch `staging` ao *ambiente de homologação* e a branch `development` ao *ambiente de desenvolvimento*.

**Nunca faça commit direto na main**. Para manter uma arvore de commits organizada, sempre que for implementar uma nova feature navegue até `development` e crie uma nova branch a partir dela com o comando `git checkout -b nome-da-branch`, nomeando-a de acordo com a feature que você vai implementar de preferência em inglês. 

Quando você terminar de implementar a nova feature, faça o `merge` da branch que você estava com `development`.

> #### Boa prática
> Uma boa prática pra evitar que você tenha mais dor de cabeça com os conflitos do merge é fazer primeiro o merge da development na sua branch e resolver os conflitos nela. Depois que estiverem resolvidos você faz o merge da sua branch na development sem mais problemas.
>
> *atenção: não esqueça de dar `git pull` na development antes do merge*

Depois de testar o sistema na development, se estiver tudo certo, você pode mandar as alterações pra `staging`. 

### Padrões de commits
É interessante que a estrutura dos seus commits siga as os padrões de [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).


## 🔗Links

- [Protótipo no Figma](https://www.figma.com/file/5YDaF4Hdhlfvk7TqC0IEDt/Untitled?node-id=0%3A1)
- [Trello](https://trello.com/b/jmmTGkmQ/sistema-de-gerenciamento-de-monitoria)
- [Site em produção](https://sistema-de-monitoria-ifal.vercel.app/)
- [Drive](https://drive.google.com/drive/folders/0AOp5ERKBOyQdUk9PVA)

## 🛠️ Tecnologias

- React JS
- Typescript
