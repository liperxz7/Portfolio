# Portfólio pessoal — Arthur Filipe

Site pessoal feito com HTML, CSS e JavaScript. O objetivo é apresentar a formação, os conhecimentos, os projetos e as formas de contato do Arthur.

## Sobre o portfólio

O conteúdo apresenta Arthur como estudante de Engenharia de Software na UNA, técnico em Desenvolvimento de Sistemas e estagiário de TI. Os conhecimentos mencionados atualmente são Python, MySQL, HTML e CSS. Atualize essas informações sempre que sua formação, experiência ou tecnologias mudarem.

## Abrir o site

O projeto não precisa de instalação nem de um processo de compilação.

1. Abra a pasta `ModeloFrontEnd-main arthur filipe` no Visual Studio Code.
2. Abra `index.html` no navegador. No VS Code, a extensão Live Server também pode servir o site localmente e atualizar a página quando os arquivos forem salvos.

O arquivo principal está dentro dessa pasta, não na raiz do repositório.

## Estrutura dos arquivos

```text
Portfolio/
├── README.md
└── ModeloFrontEnd-main arthur filipe/
    ├── index.html       Conteúdo e estrutura das seções
    ├── estilo.css       Cores, tipografia, layout e adaptação para telas menores
    ├── script.js        Menu mobile, botão de voltar ao topo e carrossel
    └── image/           Imagens usadas pelo site
```

## Seções da página

- **Início:** apresentação profissional curta.
- **Projetos:** cartões para projetos, com espaço para descrição e links.
- **Sobre mim:** informações pessoais e profissionais exibidas em carrossel.
- **Profissionalmente, competências e pretensão:** formação, conhecimentos, habilidades e objetivo profissional.
- **Contato:** informações de contato e formulário.

Os cartões de projetos ainda contêm textos de exemplo. Troque título, descrição, imagem e links pelos dados dos projetos reais. As tags `<img>` e algumas informações sobre os times estão comentadas no `index.html`; remova `<!--` e `-->` do trecho que quiser exibir novamente.

## Personalizar o conteúdo

Edite `ModeloFrontEnd-main arthur filipe/index.html` para atualizar textos, links, projetos e dados de contato. Guarde as imagens novas dentro da pasta `image` e use caminhos relativos, por exemplo `image/meu-projeto.png`.

Edite `ModeloFrontEnd-main arthur filipe/estilo.css` para mudar cores, fontes, espaçamento e aparência dos componentes. As cores principais estão reunidas no bloco `:root`, no início do arquivo. O layout usa regras responsivas para ajustar os cartões, a navegação e o formulário em telas menores.

Edite `ModeloFrontEnd-main arthur filipe/script.js` para mudar o comportamento do menu, do botão de voltar ao topo ou do carrossel.

## Bibliotecas e serviços externos

O HTML carrega algumas dependências de CDN, então uma conexão com a internet é necessária para todos os recursos visuais e interativos:

- jQuery e Owl Carousel, usados pelo carrossel.
- Ionicons, usados nos ícones.
- Google Fonts, usados na tipografia.
- StaticForms, configurado como destino do formulário de contato.

O formulário inclui uma chave de acesso no HTML, que fica pública para qualquer pessoa que visitar o site. Antes de publicar, gere uma chave nova no serviço de formulários e confira as opções de proteção contra spam e redirecionamento. Não coloque senhas ou chaves privadas no HTML ou no JavaScript do navegador.

## Antes de publicar

1. Substitua os cartões de exemplo por projetos reais e teste todos os links.
2. Revise email, localização e demais informações que serão públicas.
3. Gere uma chave nova para o formulário e confirme que o envio funciona.
4. Abra o site em celular e computador e confira as imagens e o carrossel.

Se publicar pelo GitHub Pages, configure a pasta `ModeloFrontEnd-main arthur filipe` como origem do site ou mova os arquivos do site para a pasta que o Pages publica.
