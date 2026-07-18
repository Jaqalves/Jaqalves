# Como publicar e manter seu perfil, projetos e site — guia sem terminal

Este guia explica, passo a passo e só pelo navegador (sem usar terminal/linha de comando), como manter tudo que já foi criado para você e como preencher o que ainda falta.

Todo texto marcado com **[colchetes]** é um espaço para você preencher com informações reais. Todo texto dentro de `<!-- comentário -->` é uma instrução só para você e não aparece na página nem no README renderizado.

---

## ✅ O que já está pronto

| Item | Repositório | Status |
|---|---|---|
| README do perfil | [Jaqalves/Jaqalves](https://github.com/Jaqalves/Jaqalves) | Criado e publicado |
| README do projeto de Power BI | [Jaqalves/rh-planejamento-powerbi](https://github.com/Jaqalves/rh-planejamento-powerbi) | Criado e publicado |
| README + requirements.txt do projeto de IA | [Jaqalves/ia-aplicada-rh](https://github.com/Jaqalves/ia-aplicada-rh) | Criado e publicado |
| Site pessoal (index.html + style.css) | [Jaqalves/Jaqalves.github.io](https://github.com/Jaqalves/Jaqalves.github.io) | Criado e publicado em https://jaqalves.github.io/ |

Você não precisa recriar nada disso — os passos abaixo servem para quando quiser **editar** ou **entender como foi feito**, caso queira repetir o processo em outro projeto no futuro.

---

## 1. Editando o README do perfil (Jaqalves/Jaqalves)

1. Acesse o repositório [Jaqalves/Jaqalves](https://github.com/Jaqalves/Jaqalves).
2. Clique no ícone de lápis (✏️) no canto superior direito do texto do README.
3. Faça as alterações desejadas no editor.
4. Clique em **Preview** para conferir como vai ficar antes de salvar.
5. Role até o final da página e clique em **Commit changes...**.
6. Confirme clicando em **Commit changes** (mantendo a opção "Commit directly to the main branch").

> 💡 Este arquivo é especial: como o repositório tem o mesmo nome do seu usuário, o README dele aparece automaticamente na página principal do seu perfil no GitHub.

---

## 2. Criando um novo repositório de projeto

Use estes passos sempre que quiser criar um novo projeto (por exemplo, se quiser adicionar um terceiro projeto no futuro):

1. Acesse [github.com/new](https://github.com/new).
2. Em **Repository name**, escolha um nome curto e descritivo (ex.: `nome-do-projeto`).
3. Adicione uma descrição breve.
4. Mantenha a visibilidade como **Public** (para que apareça no seu portfólio).
5. Clique em **Create repository**.
6. Dentro do repositório, clique em **creating a new file** (ou no ícone **+** ao lado do campo "Go to file").
7. Nomeie o arquivo como `README.md`, cole o conteúdo desejado e clique em **Commit changes...** → **Commit changes**.

---

## 3. Publicando o site pessoal (GitHub Pages)

O site já está publicado, mas caso precise recriar o processo:

1. Crie um repositório com o nome **exatamente igual** a `SeuUsuario.github.io` (no seu caso, `Jaqalves.github.io`). Esse nome exato é obrigatório para o site funcionar na raiz do domínio (ex.: `jaqalves.github.io`, sem nenhuma pasta depois).
2. Adicione um arquivo `index.html` (a página principal) e um `style.css` (o visual), do mesmo jeito que no passo 2 acima ("creating a new file").
3. Vá em **Settings → Pages** dentro do repositório.
4. Repositórios com o nome `usuario.github.io` publicam automaticamente a partir da branch `main`, pasta raiz — você verá a mensagem "Your site is live at https://seu-usuario.github.io/".
5. Clique em **Visit site** para conferir o resultado.

> ⚠️ Sempre que você editar `index.html` ou `style.css` e fizer commit, o site é atualizado automaticamente em alguns segundos/minutos — não é preciso fazer nada além do commit.

---

## 4. Preenchendo os placeholders

Em vários arquivos você vai encontrar textos assim:

```
[Descreva aqui o problema de RH que motivou este projeto.]
```

Para preencher:

1. Abra o arquivo no GitHub e clique no ícone de lápis (✏️) para editar.
2. Localize o texto entre colchetes.
3. Apague o texto (incluindo os colchetes `[ ]`) e digite seu conteúdo real.
4. Clique em **Preview** para conferir e depois em **Commit changes...** → **Commit changes**.

Os comentários `<!-- assim -->` podem ser apagados quando você não precisar mais deles — eles nunca aparecem na página publicada, então não há pressa.

---

## ✅ Checklist final

- [ ] Preencher a seção "Sobre mim" do README do perfil com 2-3 frases pessoais
- [ ] Preencher a descrição do projeto rh-planejamento-powerbi (contexto, objetivo, resultados)
- [ ] Adicionar o arquivo .pbix ao repositório rh-planejamento-powerbi
- [ ] Preencher a descrição do projeto ia-aplicada-rh (contexto, objetivo, resultados, ética)
- [ ] Adicionar o notebook/script e os dados de exemplo ao repositório ia-aplicada-rh
- [ ] Atualizar os cards de "Projetos em destaque" no site (index.html) com as descrições finais
- [ ] Adicionar um e-mail de contato (opcional) no README do perfil e no site
- [ ] Revisar o site em https://jaqalves.github.io/ depois de cada atualização

---

## ❓ Dúvidas comuns

**Preciso instalar algo no computador?**
Não. Todos os passos deste guia são feitos direto no navegador, pelo site do GitHub.

**Posso editar pelo celular?**
Sim, o editor de arquivos do GitHub funciona no navegador do celular, embora seja mais confortável em um computador.

**Errei algo no commit, como desfazer?**
Cada commit fica salvo no histórico do arquivo (botão **History**, no topo do arquivo). É possível ver versões antigas e, se necessário, copiar o conteúdo de volta e commitar novamente.

**O site não atualizou depois do commit, o que fazer?**
Aguarde alguns minutos e atualize a página com Ctrl+F5 (ou Cmd+Shift+R no Mac) para forçar o navegador a buscar a versão mais recente.

**Posso deixar um repositório privado?**
Pode, mas para portfólio público (perfil, projetos, site) o recomendado é manter como **Public**, já que o objetivo é que outras pessoas vejam seu trabalho.
