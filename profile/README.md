# Documentário da Arquitetura Tradicional luso-brasileira #

## Sumário ##

- [Conteúdo](#conteúdo)
- [Como contribuir](#como-contribuir)
- [Sistemas de informação](#sistemas-de-informação)

## Conteúdo ##

Este projeto se dedica a documentar a arquitetura tradicional
no mundo de cultura portuguesa, a começar pelo Brasil.
O conceito de "tradicional" e o de "cultura portuguesa"
que adotamos é intencionalmente amplo,
e permite abarcar adaptações vernaculares da modernidade
assim como tradições de outras origens que se encontrem
em territórios outrora colonizados por Portugal.

O objetivo deste projeto é realizar o cadastramento em massa de sítios 
históricos em formato de texto simples, de modo a fornecer insumos para 
investigações futuras e a permitir análises digitais do conjunto de 
dados.
Atualmente, o esforço de documentação se concentra em três eixos 
temáticos:

1. Cadastramento de informações básicas que permitam identificar 
   inequivocamente cada sítio em sua localização geográfica e conhecer 
   suas características construtivas;
2. Registro do processo histórico dos sítios por meio da identificação 
   dos agentes e eventos relevantes para sua constituição e 
   transformação;
3. Documentação da configuração espacial e formal de cada sítio, 
   inicialmente por meio de desenhos técnicos, podendo evoluir para 
   modelos virtuais e gráficos topológicos.

O projeto está estruturado nas seguintes partes:

- [Portal do projeto](https://github.com/arqtrad/arquitetura),
  compreendendo a apresentação da pesquisa, da equipe e de
  abordagens específicas;
- [Casas](https://github.com/arqtrad/casa-data);
- [Arquitetura cívica](https://github.com/arqtrad/civica-data);
- Arquitetura religiosa (previsto);
- Cidades (em elaboração inicial);
- [Thesaurus](https://github.com/arqtrad/thesaurus)
  (em elaboração inicial);
- [Desenhos técnicos](https://github.com/arqtrad/dwg-data)
  (em elaboração inicial).


## Metodologia ##

O ponto de partida do cadastramento de edificações e sítios nos 
Documentários foi o formato [DublinCore][] de inserção de metadados.
Atualmente, estamos no processo de enriquecer as fichas adaptando-as 
para o padrão [CIDOC–CRM][] de cadastramento de objetos, agentes e 
eventos.
Em tempo, será lançada uma interfaz de preenchimento das fichas para 
auxiliar o cadastramento de dados por usuários sem expertise com código, 
e também para evitar erros de preenchimento.

[DublinCore]: https://dublincore.org

[CIDOC–CRM]: https://cidoc-crm.org/


## Antes de começar

Há diversas modalidades de colaboração
se tem vínculo formal com o projeto,
se tem conhecimento sobre arquitetura tradicional,
ou ainda se domina os sistemas de informação
que estruturam os sites dos Documentários.

- 💬 [**Discussões**] são um fórum geral para
  trocar ideias, tirar dúvidas (sobretudo de conteúdo)
  e fazer propostas de inclusão de dados,
  ou ainda oferecer apoio para o projeto.
  Para postar nas discussões,
  basta [criar uma conta gratuita no GitHub] —
  e se for docente ou discente de uma escola ou universidade,
  pode [criar uma conta educacional] com alguns recursos a mais.

[**Discussões**]: https://github.com/arqtrad/.github/discussions

[criar uma conta gratuita no GitHub]: https://github.com

[criar uma conta educacional]: https://github.com/education

- 🗺️ Na nossa [**Wiki**] do projeto encontrará os objetivos imediatos
  a serem vencidos na implantação do projeto, bem como
  a visão de longo prazo que orienta o nosso trabalho, e ulteriores
  informações acerca das ferramentas de trabalho e dos subprojetos
  específicos em andamento.

[**Wiki**]: https://github.com/arqtrad/.github/wiki

- 🗂️ O projeto está dividido em vários
  **repositórios** listados na [página principal].
  Cada repositório abriga um aspecto do projeto:
  seja um documentário individual, seja
  recursos de apoio, como estilos ou
  vocabulários controlados.
  Em cada repositório, encontrará instruções específicas
  para aquele tipo de conteúdo, e exemplos de código.

[página principal]: https://github.com/arqtrad

- 📚 No [**Zotero**] temos a biblioteca pública do projeto,
  onde pode ver todas as referências que utilizamos.

[**Zotero**]: https://www.zotero.org/groups/2495935/arquitetura_tradicional_luso-brasileira/


## Como contribuir ##

As contribuições de conteúdo são feitas nos
[subprojetos](#subprojetos) referentes a cada categoria de
edificações.
Para contribuir diretamente com este portal,
inicie uma discussão com os administradores.

Para contribuir com o conteúdo do projeto, vai necessitar das
ferramentas seguintes:

1. Gerenciador de citações e bibliografia
   [Zotero](https://zotero.org) com o plugin
   [Better BibTeX](https://retorque.re/zotero-better-bibtex).
2. Acesso à [biblioteca partilhada](https://www.zotero.org/groups/2495935/arquitetura_tradicional_luso-brasileira)
   deste projeto no Zotero, fazendo uma solicitação ao
   proprietário do grupo no link acima.
3. Conhecimento das nossas normas editoriais e gráficas para
   preencher as fichas.
4. É recomendável um domínio básico do funcionamento do Git
   para maior conveniência na edição das fichas.

## Sistemas de informação

Atualmente, os Documentários utilizam os seguintes sistemas
para a estruturação e apresentação do conteúdo:

- 🎈 [Eleventy](https://11ty.dev) para renderização dos sites;
- 🥾 [Bootstrap](https://getbootstrap.com) como base para os estilos de apresentação dos sites;
- 🗺️ [Leaflet.js](https://leafletjs.com/) para apresentação dos mapas;
- ⏳ [Knightlab TimelineJS 3](https://timeline.knightlab.com/) para apresentação das linhas do tempo;
- 🇺🇳 [Country Code Emoji](https://www.npmjs.com/package/country-code-emoji) para mostrar emojis com as bandeiras nacionais;
- 📜 [js-yaml](https://www.npmjs.com/package/js-yaml) para tornar os metadados mais legíveis;
- 📊 [csv-parse](https://www.npmjs.com/package/csv-parse) para ler tabelas;
- 📝 [Pandoc](https://pandoc.org) e [node-pandoc](https://www.npmjs.com/package/node-pandoc) para formatar o texto das fichas;
- 🪢 [Node.js e NPM](https://www.npmjs.com/) para gerenciar tudo isso e mais alguns plugins.

--------------------------------------------------------

 Documentário da Arquitetura Tradicional
 (c) 2024-2025 Pedro P. Palazzo & equipe
 
 ArqTrad is licensed under a
 Creative Commons Attribution-ShareAlike 4.0 License.
 
 You should have received a copy of the license along with this
 work.  If not, see <https://creativecommons.org/licenses/by-sa/4.0/>.

