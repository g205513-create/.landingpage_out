# Landing Page de Portfólio

Página web de uma página só (landing page) feita com HTML e CSS. O projeto apresenta uma pessoa/profissional, seus serviços e seus trabalhos, com visual escuro e layout responsivo.

## Funcionalidades

- **Cabeçalho fixo** com logotipo e menu de navegação com efeito de vidro (`backdrop-filter: blur`)
- **Seção inicial (hero)** com imagem de fundo em tela cheia, título grande, nome e dois botões de ação.
- **Seção de serviços** com 6 cards em grade flexível, alternando fundo claro translúcido e fundo transparente
- **Galeria de trabalhos** em grid de 4 colunas, com imagens em proporção 3:4 e efeito de escala de cinza ao passar o mouse
- **Design responsivo** com ajustes para tablets e celulares

## Tecnologias

- HTML5
- CSS3 (Flexbox, CSS Grid, CSS Nesting, `media queries`, `transition`, `mix-blend-mode`)

## Estrutura do projeto

```
.
├── index.html      # Estrutura da página
├── style.css       # Estilos e responsividade
└── assets/         # Imagens e ícones usados na página
    ├── background.jpg
    ├── logotype.jpg
    ├── img1.jpg ... img8.png
    └── ...
```

## Como executar

1. Baixe ou clone este repositório.
2. Garanta que a pasta `assets/` está na mesma pasta do `index.html`, com as imagens.
3. Abra o `index.html` no navegador (duplo clique ou, no VS Code, com a extensão Live Server).

Não é necessário instalar nada.

## Responsividade

| Largura da tela | Mudanças |
| --- | --- |
| Até 768px | Cabeçalho e título menores, cards em 1 por linha, galeria em 2 colunas |
| Até 480px | Galeria em 1 coluna |

## Personalização

- **Cores:** o fundo da página é definido em `body` (`#030013`); os botões e cards usam tons de cinza translúcidos no `style.css`.
- **Textos:** edite diretamente o `index.html` (nome, descrições dos serviços, título da hero).
- **Imagens:** troque os arquivos dentro de `assets/` mantendo os mesmos nomes, ou atualize os caminhos no HTML.
- **Serviços:** para adicionar um card, copie um bloco `<div class="card">` dentro de `.divCards`.

## Melhorias futuras

- Fazer os links do menu rolarem até as seções (âncoras com `id`)
- Adicionar textos alternativos (`alt`) nas imagens da galeria e dos cards
- Criar um formulário ou link real de contato
- Adicionar um rodapé

## Autor

Feito por **Gabriel Silva** como projeto de estudo de HTML e CSS.
