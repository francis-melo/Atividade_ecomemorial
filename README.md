# Acompanhamento de Atividades

Sistema simples para acompanhar tarefas e enviar pelo WhatsApp um link da página de andamento.

## Como publicar no GitHub Pages

1. Acesse https://github.com e entre na sua conta.
2. Clique em **New repository**.
3. Dê um nome ao repositório, por exemplo: `acompanhamento-atividades`.
4. Marque como **Public**.
5. Clique em **Create repository**.
6. Envie estes arquivos para o repositório:
   - `index.html`
   - `.nojekyll`
   - `README.md`
7. Depois, vá em **Settings**.
8. No menu lateral, clique em **Pages**.
9. Em **Build and deployment**, escolha:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
10. Clique em **Save**.

Depois de alguns minutos, o GitHub vai gerar um link parecido com:

`https://seu-usuario.github.io/acompanhamento-atividades/`

Esse é o link que deve ser colocado em **Configurações > Link da página de acompanhamento** dentro do sistema.

## Acesso do administrador

As opções de editar, enviar WhatsApp, excluir, agenda de envios e configurações ficam escondidas para visitantes.

Para abrir o modo administrador, clique em **Administrador** e use a senha:

`ecomemorial2026`

## Observação importante

O GitHub Pages publica a página, mas não salva dados em uma base online. Os dados cadastrados ficam no navegador de quem está usando a página.

Para todos verem exatamente os mesmos dados atualizados, será necessário conectar depois a uma base online, como Google Sheets, Airtable, Firebase ou um servidor.
