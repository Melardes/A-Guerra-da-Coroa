# A Guerra da Coroa · Códex

**Um universo literário explorado como uma experiência interativa.**

## Explore o projeto

[**Abrir o Códex no Cloudflare →**](https://codex.thewarofcrown.workers.dev/)

Projeto de **Otávio Tavares**, autor de *A Guerra da Coroa*, desenvolvido com assistência de IA. O Códex conecta personagens, famílias, Casas, lugares, povos e sistemas do mundo em uma aplicação interativa.

**Apresentação atualizada em 13 de outubro de 2026**, conforme a versão aprovada pelo autor.

## A experiência

- **Atlas narrativo:** explore o mapa de Azafor por livros, anos e eras; selecione acontecimentos e acompanhe as localizações e os trajetos dos personagens.
- **Globo de relações:** explore Casas e famílias em uma esfera interativa, com brasões, descrições e conexões genealógicas.
- **Genealogias:** consulte retratos, vínculos familiares e conexões entre famílias, preservando informações ainda desconhecidas na narrativa.
- **Cronologia:** navegue pelas eras e pelos acontecimentos, com acesso ao evento correspondente no atlas.
- **Busca do universo:** encontre personagens, Casas, lugares, povos e relações documentadas.
- **Malarin:** traduza, consulte o dicionário e explore as regras da língua criada para a obra. Propostas novas são identificadas como pendentes de aprovação do autor.
- **Celular e computador:** navegue por mouse ou toque, com zoom nos mapas e nas árvores.
- **Menus com retorno visual:** as setas giram suavemente ao abrir e fechar as opções.

O site contém spoilers e informações de planejamento da saga.

## Leitura pública, gestão do autor

A exploração do universo, a tradução e a consulta ao dicionário são públicas. A edição do cânone, as ferramentas de revisão editorial e o registro, a edição e a exclusão de palavras exigem autenticação do autor. As permissões de escrita são verificadas no servidor.

No Cloudflare, o autor entra por nome de usuário e senha, com opção de mostrar a senha e encerrar a sessão. A versão no ChatGPT Sites mantém sua própria autenticação.

As ferramentas autorais incluem revisão do cânone e dos livros, decisões sobre apontamentos e marcação dos trechos a corrigir. As sugestões de tradução não são registradas automaticamente.

## Construção

**TypeScript · React · Vinext · Cloudflare Workers · Cloudflare D1 (SQL)**

A interface combina mapas e visualizações interativas com armazenamento persistente. O Cloudflare Workers hospeda a aplicação externa, e o Cloudflare D1 armazena seus dados. Parte do processamento da interface usa um Web Worker no navegador.

As fontes portuguesas orientam o cânone; fontes de tradução não substituem datas ou informações da obra. Atualizações do código preservam as decisões e as edições manuais armazenadas no banco.

As duas hospedagens usam bancos e sessões próprios. A publicação do código em ambas não sincroniza automaticamente as revisões entre elas.

## Sobre este repositório

Este repositório público é a **apresentação do projeto para portfólio**. O acesso à aplicação está no link do Cloudflare acima.

O código-fonte completo, os manuscritos, os materiais editoriais e as configurações privadas permanecem no repositório privado da aplicação. Este repositório não hospeda o Códex.

*A Guerra da Coroa e seu universo são uma criação de Otávio Tavares. Esta apresentação não concede licença de reprodução da obra ou de seus materiais.*
