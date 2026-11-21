# Portfólio – Mário Castigo Muvambo

Portfólio pessoal em HTML, pronto para o GitHub Pages.

## Estrutura

```
index.html                 página principal (PT / EN)
images/                    fotografias e imagem de partilha (og-image.jpg)
images/projectos/          capturas de ecrã dos projectos (paroquia.jpg, mobilidade.jpg)
elearning/demo-1/          módulo do Articulate Storyline publicado (story.html)
cv/                        CV em português e inglês (PDF)
```

## Publicar no GitHub Pages

1. Crie um repositório público com o nome `mariomuvambo.github.io`.
2. Carregue todo o conteúdo desta pasta (Add file → Upload files).
3. Em Settings → Pages, escolha "Deploy from a branch", `main` e `/ (root)`.
4. O site fica disponível em `https://mariomuvambo.github.io`.

## Antes de publicar

- Os links do GitHub já apontam para github.com/mariomuvambo. Quando tiver o link de cada repositório, pode trocá-lo nos botões "Ver no GitHub".
- As capturas da Paróquia Digital estão em `images/paroquia/`. Falta a captura da Aplicação de Mobilidade em `images/projectos/mobilidade.jpg`.

## Adicionar um módulo do Storyline

1. No Storyline: Publish → Web (ou LMS) → Publish.
2. Copie a pasta publicada para `elearning/` (por exemplo `elearning/cenario-ramificado/`).
3. Coloque uma imagem de capa em `images/elearning/`.
4. No `index.html`, copie o bloco `<article class="modulo largo">` do quiz e troque a pasta (`data-src`), a imagem e os textos.

Módulo publicado: `elearning/quiz-seguranca-digital/story.html`.
Publique apenas módulos próprios ou com autorização do cliente.
