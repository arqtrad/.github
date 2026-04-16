# Documentário da Arquitetura Tradicional luso-brasileira #

Uma base de dados de edificações e sítios tradicionais
em formato de texto simples, em acesso aberto e podendo ser transposta
para apresentação online e análise por
*scripts* e programas especializados.

Projeto financiado pelo CNPq 2025–2028, processo 406601/2025-9.

- Coordenação : [Pedro P. Palazzo](https://github.com/p3palazzo)
- Execução : [Universidade de Brasília](http://unb.br), laboratório Vereda
- Equipe : NUTHAU, Universidade Federal de Uberlândia e Universidade 
  Regional do Cariri
- Colaboradores em diversas outras instituições e localidades

## Sumário ##

1. [Conteúdo](#conteúdo)
2. [Metodologia](#metodologia)
3. [Antes de começar](#antes-de-começar)
4. [Como contribuir](#como-contribuir)
5. [Sistemas de informação](#sistemas-de-informação)

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
- [Casas](https://github.com/arqtrad/casa)
  (em preenchimento);
- [Arquitetura cívica](https://github.com/arqtrad/civica);
- Arquitetura religiosa (previsto);
- Cidades (em elaboração inicial);
- [Thesaurus](https://github.com/arqtrad/thesaurus)
  (em elaboração inicial);
- [Desenhos técnicos](https://github.com/arqtrad/desenho)
  (em elaboração inicial).


## Metodologia ##

Este projeto adota duas premissas :

- Cadastramento das informações em formato de texto simples estruturadas 
  segundo a especificação YAML
  ([explicação introdutória aqui][1] e [tutorial técnico aqui][2]),
  de modo a garantir maior acessibilidade, portabilidade, durabilidade e
  facilidade de tradução dos dados para diferentes formatos ; e

- Uso de ferramentas e plataformas em software livre, visando a
  garantir que os dados permaneçam sempre abertos e legíveis, e
  protegendo o projeto contra a irregularidade no financiamento público
  da pesquisa / investigação.

O ponto de partida do cadastramento de edificações e sítios nos 
Documentários foi o formato [DublinCore][3] de inserção de metadados.
Atualmente, estamos no processo de enriquecer as fichas adaptando-as 
para o formato [LIDO][4] de descrição de objetos,
criado pelo Conselho Internacional de Museus (ICOM) com base no seu 
próprio padrão [CIDOC–CRM][5] de documentação.

O LIDO é especialmente adequado para registrar informações sobre
bens imóveis em comparação com outros sistemas de cadastramento 
museológico.
Existe um [manual de preenchimento][6] (em alemão) associado a
[exemplos de fichas][7] mostrando a aplicação da maior parte da 
especificação LIDO.

Em tempo, será lançada uma interface de preenchimento das fichas para 
auxiliar o cadastramento de dados por usuários sem expertise digital,
e também para evitar erros de preenchimento.

[1]: https://www.linkedin.com/pulse/xml-json-markdown-e-yaml-explicação-simples-vitor-martins-ufv5e

[2]: https://www.yaml.info/learn/index.html

[3]: https://dublincore.org

[4]: https://icom-documentation.mini.icom.museum/working-groups/lido/lido-overview/

[5]: https://cidoc-crm.org/

[6]: http://dx.doi.org/10.11588/arthistoricum.1407

[7]: https://doi.org/10.11588/DATA/LKORVT


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

[**Discussões**]: https://github.com/orgs/arqtrad/discussions

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
[subprojetos](https://github.com/orgs/arqtrad/repositories)
referentes a cada categoria de edificações.
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

- 🆔 [Open Location Codes](https://github.com/google/open-location-code) 
  para identificar os bens sem ambiguidade;
- 🗺️ [Global Building Atlas](https://github.com/zhu-xlab/GlobalBuildingAtlas)
  para padronizar a locação das edificações;
- 🌎 [QGIS](https://qgis.org) com o plugin
  [Lat Lon Tools](https://github.com/hamiltoncj/qgis-latlontools-plugin)
  para georreferenciar e gerar os códigos de locação;
- 🎈 [Eleventy](https://11ty.dev) para renderização dos sites;
- 🥾 [Bootstrap](https://getbootstrap.com) como base para os estilos de apresentação dos sites;
- 📋 [Table of contents plugin for Bootstrap](https://afeld.github.io/bootstrap-toc/);
- 🍃 [Leaflet.js](https://leafletjs.com/) para apresentação dos mapas;
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

