# 💣 Git War – Projeto Colaborativo

Bem-vindo ao projeto da aula prática de Git e GitHub.

Aqui você vai trabalhar como em um time real: criando sua própria branch, fazendo alterações e propondo mudanças via Pull Request.

---

## 🎯 Objetivo

Você deve:

* Clonar o repositório
* Criar uma branch com seu nome
* Fazer suas alterações
* Subir para o GitHub
* Criar um Pull Request

---

## 📁 Estrutura do projeto

```
alunos/
  └── seu-arquivo.txt

lista.md
```

---

## 🧪 Tarefas

### ✅ Parte 1 – Criar seu arquivo (SEM conflito)

1. Dentro da pasta `alunos/`, crie um arquivo com seu nome:

```
alunos/seu-nome.txt
```

2. Adicione o seguinte conteúdo:

```
Nome: Seu Nome
Frase: Uma frase qualquer sua
```

---

### ⚠️ Parte 2 – Editar lista de chamada (COM conflito)

Abra o arquivo:

```
lista.md
```

Você verá algo assim:

```
# Lista de chamada

Nome:
```

👉 **IMPORTANTE:**

* TODOS devem editar **a mesma linha**
* Substitua por:

```
Nome: Seu Nome
```

⚠️ Não crie uma nova linha.
⚠️ O objetivo é gerar conflito.

---

## 🔧 Fluxo Git esperado

```bash
git clone <repo>
cd git-war

git checkout -b feat/seu-nome

# faça suas alterações

git add .
git commit -m "feat: adiciona contribuição do seu-nome"

git push origin feat/seu-nome
```

---

## 🌐 No GitHub

1. Vá até a aba **Branches**
2. Encontre sua branch
3. Clique em **Compare**
4. Analise as mudanças
5. Crie um **Pull Request**

---

## 💥 Sobre conflitos

Em algum momento, você verá algo assim:

```
<<<<<<< HEAD
Nome: Seu Nome
=======
Nome: Outro Nome
>>>>>>> main
```

Isso significa que duas pessoas alteraram o mesmo lugar.

👉 Você deve resolver manualmente.

---

## 🧠 Regras

* ❌ Não commitar direto na `main`
* ✅ Use mensagens de commit claras
* ⚠️ Conflitos são esperados (e desejados)

---

## 🚀 Dica

Se algo quebrar… perfeito.
É assim que se aprende Git de verdade.

---

Boa sorte 🙂
