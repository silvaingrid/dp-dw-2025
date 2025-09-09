#TAREFAS

---

## 1º BIMESTRE

### Atividade 2 - Simples
> Entrega para: 15/09

**Título:** Minha Primeira Página Estruturada  
**Objetivo:** Praticar o uso de títulos, parágrafos, listas e links em uma única página. 
**Descrição:**  
- Crie um arquivo chamado `primeira-estrutura.html`.  
- Estruture o documento corretamente com `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`.  
- No corpo da página insira:  
  - Um título `<h1>` com o nome de um hobby que você gosta.  
  - Um parágrafo `<p>` explicando por que você gosta desse hobby.  
  - Uma lista não ordenada `<ul>` com **3 itens** relacionados ao hobby.  
  - Um link `<a>` que leve para um site relacionado ao tema.  

---

### Atividade 3 - Media
> Entrega para: 19/09

**Título:** Lista de Compras  
**Objetivo:** Trabalhar listas ordenadas e não ordenadas.  
**Descrição:**  
- Crie um arquivo chamado `lista-compras.html`.  
- Estruture o documento corretamente.  
- No corpo da página insira:  
  - Um título `<h2>` chamado “Lista de Compras”.  
  - Uma lista **não ordenada** (`<ul>`) com pelo menos 8 itens de supermercado.  
  - Uma lista **ordenada** (`<ol>`) mostrando os 5 primeiros passos para preparar uma refeição simples.  

---

### Atividade 4 - Média (montagem de estrutura HTML)
> Entrega para: 23/09

**Título:** Página de Links Favoritos  
**Objetivo:** Trabalhar com links e imagens.  
**Descrição:**  
- Crie um arquivo chamado `meus-links.html`.  
- Estruture o documento corretamente.  
- No corpo da página insira:  
  - Um título `<h2>` “Meus Links Favoritos”.  
  - Uma lista de 5 links (`<a>`) para sites que você costuma acessar.  
  - Insira uma imagem (`<img>`) representando um desses sites, com `alt` preenchido corretamente.  

---

### Atividade 5 - Complexa (montagem de estrutura HTML)
> Entrega para: 30/09

**Título:** Mini Currículo Online  
**Objetivo:** Criar uma página completa usando diversos elementos básicos.  
**Descrição:**  
- Crie um arquivo chamado `mini-curriculo.html`.  
- Estruture o documento corretamente.  
- O corpo da página deve conter:  
  - Um título principal `<h1>` com seu nome.  
  - Uma imagem (`<img>`) sua ou de um avatar.  
  - Uma seção `<div>` chamada “Sobre mim” com um parágrafo descrevendo você.  
  - Uma seção “Formação” usando uma **lista ordenada** para mostrar seu histórico escolar.  
  - Uma seção “Habilidades” usando uma **lista não ordenada** com ao menos 5 habilidades.  
  - Uma lista de **links externos** para redes sociais ou sites relacionados.  


# 🚀 Playbook de Entrega de Tarefas – Turma **DP-DW**

> **Resumo executivo:** Fork ➜ Branch com seu nome ➜ Commit & Push ➜ Pull Request ➜ Envie o link ao professor.  
> Se ficar na dúvida, retorne ao passo 1 e repita a operação.





## 1. Acesse o repositório da turma

1. Abra **https://github.com/awescolar/dp-dw-2025** no navegador.
2. Confirme que está logado na **sua** conta GitHub.






## 2. Faça um **fork** (cópia pessoal)

1. Clique no botão **Fork** (canto superior-direito).
2. Aguarde alguns segundos; seu fork aparecerá em `github.com/<seu-usuário>/dp-aw`.





## 3. Crie uma **branch** com seu nome

> Use sempre o padrão `seu-nome-sobrenome` (ex.: `joao-silva`).

### 3.1 Pelo terminal (com Git instalado)

```bash
git clone https://github.com/<seu-usuário>/dp-dw-2025.git
cd dp-aw
git checkout -b joao-silva
```






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
