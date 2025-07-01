# 🚀 Playbook de Entrega de Tarefas – Turma **DP-DW**

> **Resumo executivo:** Fork ➜ Branch com seu nome ➜ Commit & Push ➜ Pull Request ➜ Envie o link ao professor.  
> Se ficar na dúvida, retorne ao passo 1 e repita a operação.

---

## 1. Acesse o repositório da turma

1. Abra **https://github.com/awescolar/dp-dw-2025** no navegador.
2. Confirme que está logado na **sua** conta GitHub.

---

## 2. Faça um **fork** (cópia pessoal)

1. Clique no botão **Fork** (canto superior-direito).
2. Aguarde alguns segundos; seu fork aparecerá em `github.com/<seu-usuário>/dp-aw`.

---

## 3. Crie uma **branch** com seu nome

> Use sempre o padrão `seu-nome-sobrenome` (ex.: `joao-silva`).

### 3.1 Pelo terminal (com Git instalado)

```bash
git clone https://github.com/<seu-usuário>/dp-dw-2025.git
cd dp-aw
git checkout -b joao-silva
```

---

## 4. OPERACIONALIZANDO

### 4.1 Adicione ou edite os arquivos da tarefa

- Localize a pasta solicitada pelo professor (ex.: 1BIM/ATV1/).
- _cada tarefa haverá uma pasta e um arquivo em branco para você editar (ex.: BIM/ATV1/[index.html | assets/img]_
- Crie/edite os arquivos necessários.

**Com Git local**

```bash
git add .
git commit -m "instrução conforme prevista no Google Sala de Aula"
```

_(Mantenha a mensagem de commit clara e objetiva.)_

### 4.2 **Push** da branch para o seu fork

```bash
git push -u origin joao-silva
```

### 4.3 Abra um **Pull Request** para o repositório-mãe

1. Clique no banner **Compare & pull request** ou vá em Pull requests → New pull request.
2. Verifique os alvos:
   - base repository: awescolar/dp-aw
   - base branch: main
   - compare: joao-silva no seu fork
3. Título do PR: ATV1 – João Silva.
4. Descreva brevemente o que foi feito.
5. Marque “Create pull request”.

### 4.4 Envie o link do commit/PR na tarefa do GSA (Google Sala de Aula)

- Copie a URL do Pull Request recém-criado;
- Cole na tarefa do GSA;
- **PRONTO**. O professor aprova ou solicita ajustes.
