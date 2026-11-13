# Entre páginas & estrelas — para Manuela

Site em HTML, CSS e JavaScript puro. Não precisa instalar dependências nem compilar.

## Abrir

Extraia o ZIP e abra index.html no navegador. Para armazenamento mais previsível, publique no GitHub Pages. Alguns recursos de copiar/compartilhar dependem de HTTPS e do suporte do navegador. Há uma opção para baixar o texto.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub (exemplo: universo-da-manuela).
2. Use Add file → Upload files para enviar os arquivos extraídos. Não envie apenas o ZIP. index.html, style.css e script.js precisam ficar juntos na raiz.
3. Salve em Commit changes.
4. Abra Settings → Pages → Build and deployment.
5. Source: Deploy from a branch. Branch: main. Pasta: / (root). Clique em Save.
6. Aguarde a publicação e use o endereço mostrado em Visit site. Compartilhe esse link com a Manuela.

## O que funciona

- Mural de gostos com categorias, busca, favoritos, edição e exclusão com confirmação.
- Upload local de capas JPG, PNG ou WebP (até 5 MB), reduzidas antes de salvar.
- A decoração se atualiza com os gostos: adesivos, título do livro e foto em destaque.
- Perguntas opcionais sobre carinho, limites, histórias e preferências.
- Lista de ideias para fazer juntos, com conclusão e remoção.
- Bilhete romântico, modo claro/escuro e layout adaptável.
- Dados salvos no navegador via localStorage, com tratamento de erro de espaço.
- Compartilhamento de texto revisável, cópia e download de texto.
- Backup JSON com imagens e restauração com validação e confirmação.

## Como receber as respostas

Ela toca em “Compartilhar minhas páginas”, revisa o texto e escolhe um aplicativo para enviá-lo. No computador, pode copiar o texto e colar na conversa ou baixar o arquivo TXT. Você também pode receber o backup JSON e restaurá-lo no seu navegador para visualizar o mural inteiro; a restauração substitui o caderno local.

Não há sincronização automática entre dispositivos, login, banco de dados ou envio escondido. O GitHub Pages hospeda os arquivos, mas não recebe as respostas dela. Limpar os dados do navegador pode apagar o caderno: use “Salvar cópia”. Não coloque backups pessoais no repositório público.

As capas não são buscadas na internet automaticamente. Sem imagem enviada, o site cria um recorte tipográfico. As fontes vêm do Google Fonts; caso não carreguem, há fontes alternativas do sistema. Nenhuma chave de API é necessária.

## Personalizar

- index.html: textos, nome, bilhete e assinatura.
- style.css: paleta nas variáveis de :root e estilos responsivos.
- script.js: gostos iniciais em seed, perguntas em prompts e sugestões em ideas.

Alterar seed não substitui os dados que um navegador já salvou. Os itens de teste não fazem parte dos arquivos entregues.

## Limites

Até 150 gostos e 200 ideias, sujeitos à capacidade do navegador (em geral alguns MB). Se o espaço acabar, o site avisa e não confirma a gravação. Exporte uma cópia e reduza as imagens. Os dados locais não são criptografados; pessoas com acesso ao mesmo perfil de navegador podem abri-los.

Este pacote está pronto para envio ao GitHub, mas não inclui publicação em uma conta GitHub.
