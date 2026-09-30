# Análise de Vendas — Olist

Análise exploratória de dados do Olist, marketplace brasileiro, desenvolvida com Python e Pandas.

O projeto busca transformar dados de clientes, pedidos e vendas em informações relevantes para compreender padrões de consumo, desempenho comercial e distribuição geográfica das vendas.

---

## Sobre o projeto

Este projeto faz parte da construção do meu portfólio em análise de dados e representa a aplicação prática de conhecimentos de Administração, pesquisa e análise quantitativa.

A análise utiliza dados do Olist para investigar diferentes aspectos do comportamento das vendas, buscando responder questões como:

- Quais estados concentram maior número de clientes?
- Quais estados apresentam maior volume de receita?
- Quais cidades possuem maior quantidade de pedidos?
- Como o volume de pedidos se relaciona com a receita?
- Quais cidades apresentam maior ticket médio?
- Existe concentração geográfica relevante das vendas?

---

## Relação com minha trajetória acadêmica

Minha aproximação com análise de dados está relacionada à minha trajetória acadêmica e profissional.

Minha monografia foi desenvolvida sobre **comportamento de consumo**, tema que também se relaciona com as pesquisas que desenvolvo atualmente no **Mestrado em Administração**.

Este projeto representa uma forma de aproximar essa experiência acadêmica da análise de dados aplicada a problemas de negócios.

A proposta é utilizar dados para compreender comportamentos, identificar padrões e transformar informações em insights que possam apoiar processos de decisão.

---

## Ferramentas utilizadas

- Python
- Pandas
- Matplotlib
- Google Colab
- GitHub

---

## Principais análises

### Clientes e vendas por estado

Foi realizada uma análise da distribuição de clientes, pedidos e receita entre os estados brasileiros.

Os resultados indicaram forte concentração das vendas em alguns estados, com destaque para:

- São Paulo
- Rio de Janeiro
- Minas Gerais
- Rio Grande do Sul
- Paraná

São Paulo apresentou a maior concentração de clientes e receita entre os estados analisados.

---

### Receita por estado

Também foi analisada a participação dos principais estados na receita total.

Os três estados com maior receita representaram aproximadamente **63,37% da receita analisada**.

São Paulo, individualmente, representou aproximadamente **38,28% da receita total**.

---

### Análise por cidade

A análise também foi direcionada para o nível municipal.

Entre as cidades com maior número de clientes destacaram-se:

1. São Paulo
2. Rio de Janeiro
3. Belo Horizonte
4. Brasília
5. Curitiba

São Paulo apresentou uma diferença significativa em relação às demais cidades em volume de clientes e pedidos.

---

### Relação entre pedidos e receita

Foi desenvolvido um gráfico de dispersão para observar a relação entre a quantidade de pedidos e a receita gerada por cada cidade.

De forma geral, cidades com maior volume de pedidos também apresentaram maior receita, embora existam diferenças no valor médio gerado por pedido.

---

### Ticket médio

Também foi analisado o ticket médio das cidades, considerando apenas aquelas com **pelo menos 100 pedidos**.

Entre os maiores tickets médios encontrados estão:

| Cidade | Pedidos | Ticket médio |
|---|---:|---:|
| Divinópolis | 135 | R$ 261,49 |
| João Pessoa | 254 | R$ 209,31 |
| Porto Velho | 109 | R$ 201,27 |
| Nova Friburgo | 150 | R$ 186,83 |
| Belém | 445 | R$ 181,97 |
| Maceió | 246 | R$ 181,72 |
| Campo Grande | 315 | R$ 181,34 |
| Palmas | 109 | R$ 181,12 |
| Teresina | 280 | R$ 178,46 |
| Natal | 205 | R$ 175,27 |

Essa análise permite observar que **volume de pedidos e valor médio por pedido são dimensões diferentes do desempenho comercial**.

---

## Visualizações

Foram utilizadas visualizações para facilitar a interpretação dos resultados, incluindo:

- Concentração de clientes e receita por estado;
- Relação entre quantidade de pedidos e receita por cidade;
- Comparação de ticket médio entre cidades;
- Distribuição geográfica das vendas.

---

## Principais insights

A análise permitiu identificar alguns padrões relevantes:

- As vendas apresentam forte concentração geográfica;
- São Paulo possui posição de destaque tanto em número de clientes quanto em receita;
- As maiores cidades concentram grande parte do volume de pedidos;
- Maior quantidade de pedidos não significa necessariamente maior ticket médio;
- Algumas cidades com menor volume apresentam ticket médio elevado;
- A análise conjunta de volume, receita e ticket médio permite uma visão mais completa do desempenho comercial.

---

## Arquivos

- `analise_olist_portfolio_(1).ipynb` — notebook desenvolvido no Google Colab.
- `analise_olist_portfolio_(1).py` — código Python da análise.
- `README.md` — documentação e principais resultados do projeto.

---

## Próximos passos

Como evolução deste projeto, pretendo ampliar a análise com:

- análise temporal das vendas;
- análise de categorias de produtos;
- avaliação de vendedores;
- análise de avaliações dos clientes;
- indicadores de logística e entrega;
- novas visualizações e dashboards.

---

## Sobre mim

Sou **Elias Trindade**, mestrando em Administração, com formação em Turismo e interesse em análise de dados, comportamento do consumidor e aplicação de métodos quantitativos à tomada de decisão.

Este repositório faz parte da construção do meu portfólio profissional em análise de dados.
