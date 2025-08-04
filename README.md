# 🍽️ Desafio Git: Cardápio do RU

Bem-vindo(a) ao desafio do nosso minicurso de Git!

Neste exercício, **todos os participantes vão colaborar em um único repositório público**, simulando o dia a dia de um time real de desenvolvimento.

---

## 🎯 Objetivo

Você vai:

- Clonar o repositório
- Criar uma branch com seu nome
- Fazer commit e push direto para o repositório remoto
- Resolver possíveis conflitos
- Contribuir para um projeto compartilhado

---

## 🧪 O que você precisa fazer

### Clone o repositório

```bash
git clone https://github.com/InfoCorpUFMT/cardapio-do-ru.git
cd cardapio-do-ru
```

### Crie uma branch com seu nome

```bash
git checkout -b seu-nome
```

### Edite o arquivo cardapio.md
Adicione um item ao cardápio em qualquer dia da semana no arquivo. Sem apagar nada dos colegas.
#### Exemplo
```
## Sexta-feira
- Baião de dois
```

### Commit e Push
```bash
git add cardapio.md
git commit -m "Adiciona item de sexta-feira - seu-nome"
git push origin seu-nome
```

### Envie sua contribuição

```
git checkout main
git pull origin main
git merge seu-nome
git push origin main

```

### Deu conflito?
Resolva manualmente, edite o arquivo deixando as duas linhas, salve e continue:
```
git add cardapio.md
git commit -m "Resolve conflito - Ana Souza"
git push origin main
```




