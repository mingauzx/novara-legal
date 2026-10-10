# Novara — Termos e Privacidade

Este pacote contém páginas públicas para o Discord Developer Portal:

- `termos.html` — Termos de Serviço;
- `privacidade.html` — Política de Privacidade;
- `index.html` — entrada para os dois documentos;
- `style.css` — visual Dark Premium.

## IMPORTANTE ANTES DE PUBLICAR

1. Pesquise nos arquivos HTML por `[INSERIR` e substitua os dois marcadores:
   - `[INSERIR NOME DA ORGANIZAÇÃO OU RESPONSÁVEL PELO PROJETO]`;
   - `[INSERIR E-MAIL OU LINK PÚBLICO DE SUPORTE]`.
2. Confirme que as declarações condizem com o funcionamento atual do bot e sua rotina de retenção/exclusão. Principalmente, não há exclusão automática geral de todos os registros históricos segundo o código revisado.
3. O texto é um modelo informativo, não parecer jurídico. Um responsável pelo projeto deve revisar antes de publicar; aconselhamento jurídico profissional é recomendável se o aplicativo crescer ou se houver dúvida de conformidade.
4. Nunca envie `.env`, tokens, Client Secret, URLs privadas de banco ou arquivos de backup ao repositório público.

## Como publicar via GitHub Pages sem mexer na Railway

1. No GitHub, crie um repositório público chamado `novara-legal` (nome sugerido).
2. Envie os 4 arquivos (`index.html`, `termos.html`, `privacidade.html`, `style.css`) para a raiz do repositório e faça Commit.
3. Abra Settings → Pages → Build and deployment → Deploy from a branch; selecione `main` e `/(root)`, depois Save.
4. Aguarde até o GitHub mostrar a URL pública publicada. Abra as duas páginas em janela anônima para confirmar acessibilidade.
5. Na aplicação Novara no Discord Developer Portal, preencha:
   - **Terms of Service URL:** `https://SEU-USUARIO.github.io/novara-legal/termos.html`
   - **Privacy Policy URL:** `https://SEU-USUARIO.github.io/novara-legal/privacidade.html`
   Substitua `SEU-USUARIO` pelo nome real do dono do repositório. A URL deve ser a exibida pelo Pages, não presumida.

Se quiser, estas páginas também podem ser servidas pelo seu dashboard, mas isso exige confirmar as rotas públicas disponíveis nele.
