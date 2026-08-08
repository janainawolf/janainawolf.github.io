# Portfólio GitHub de Ana.codes

Página de portfólio pessoal construída com HTML, CSS e JavaScript puro. O objetivo é exibir seus projetos GitHub de forma visual, responsiva e moderna.

## Estrutura do projeto

- `index.html` — página principal do portfólio.
- O CSS está embutido no próprio HTML para simplificar o projeto.
- Os cards de repositório são gerados dinamicamente a partir de um array de objetos em JavaScript.

## O que está incluído

- Cabeçalho com avatar, nome e redes sociais.
- Seção "Sobre mim" com descrição curta e lista de tecnologias.
- Listagem de repositórios com nome, descrição, linguagem, estrelas e forks.
- Links externos seguros com `target="_blank"` e `rel="noopener noreferrer"`.
- Layout responsivo para dispositivos móveis e desktop.

## Personalização

1. Atualize os dados do perfil em `index.html`:
   - Nome
   - localização
   - username GitHub
   - links para GitHub, LinkedIn, Twitter e e-mail
   - avatar

2. Edite o array `repos` no script JavaScript para usar seus projetos reais:
   - `name`
   - `description`
   - `language`
   - `languageColor`
   - `stars`
   - `forks`
   - `visibility`
   - `url`

3. Ajuste o texto da seção "Sobre mim" para refletir sua experiência e objetivos.

## Publicação no GitHub Pages

1. Faça commit do projeto no repositório GitHub.
2. Vá em `Settings` > `Pages` no repositório.
3. Selecione a branch `main` (ou `master`) e a pasta `/` como fonte.
4. Salve para publicar o site.

## Melhorias futuras

- Buscar os repositórios diretamente da API do GitHub.
- Adicionar seção de projetos em destaque com screenshots.
- Inserir links para LinkedIn e currículo.
- Tornar o portfólio mais acessível com mais elementos semânticos e aria-labels.

---

### Sobre

Este projeto é um exemplo de portfólio simples e elegante para apresentar seus repositórios GitHub. É ideal para GitHub Pages e para usar como landing page pessoal.
