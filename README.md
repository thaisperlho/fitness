
# Controle de Versão - Projeto Fitness

## Inicialização do Projeto
1. Criamos o repositório localmente com o comando:
    ```bash
    git init
    ```
2. Adicionamos arquivos ao repositório:
    ```bash
    git add .
    git commit -m "Inicialização do projeto"
    ```

## Criação e Uso de Ramificações
Para criar uma ramificação para cada página (branch):

```bash
git branch desenvolvimento/home
git checkout desenvolvimento/home
```
Ou diretamente:
```bash
git checkout -b desenvolvimento/home
```

## Mesclagem das Ramificações
Após finalizar as alterações em uma ramificação, fazemos a mesclagem:
```bash
git checkout main
git merge desenvolvimento/home
```

## Envio para o GitHub
Primeiro, conecte ao repositório remoto:
```bash
git remote add origin git@github.com:thaisperlho/fitness.git
```
Depois envie as mudanças:
```bash
git push -u origin main
```


## Contribuições dos Alunos

### Aluno 1
**Contribuição:** Desenvolvimento da página Home e da página Sobre, além da estilização geral das páginas utilizando CSS.

**Experiência:** Trabalhar com o Git foi uma boa experiência. Inicializei o projeto localmente e configurei o controle de versão, o que me permitiu acompanhar as mudanças realizadas. A criação das ramificações para o desenvolvimento das páginas me ajudou a isolar o código e evitar conflitos. Realizei o merge das minhas alterações com a branch principal e foi interessante observar como o Git facilita a colaboração em equipe, resolvendo conflitos de código e integrando as diferentes partes do projeto.
### Aluno 2
**Contribuição:** Criação da página de Contato e ajustes finais no layout das páginas.

**Experiência:** Minha experiência ao usar o Git foi positiva. Inicializei o projeto em uma ramificação separada e trabalhei na página de Contato. Aprendi a fazer commit de mudanças com mensagens claras e a utilizar o Git para colaborar com meu colega de equipe. Quando fiz o merge da minha branch com a branch principal, consegui resolver os pequenos conflitos que surgiram e publiquei o projeto no GitHub. Essa experiência me ajudou a entender a importância do controle de versão no desenvolvimento colaborativo.









