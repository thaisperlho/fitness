
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
**Contribuição:** (Descreva aqui o que você fez)

**Experiência:** (Compartilhe sua experiência ao usar o Git)

### Aluno 2
**Contribuição:** (Descreva aqui o que você fez)

**Experiência:** (Compartilhe sua experiência ao usar o Git)


