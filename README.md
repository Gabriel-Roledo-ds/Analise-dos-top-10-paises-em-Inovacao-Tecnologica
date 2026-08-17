# Análise de Indicadores de Inovação Tecnológica

Trabalho da disciplina de Economia da Informação — curso de Ciência de Dados, FATEC Ourinhos.

## Objetivo

Avaliar o nível de inovação tecnológica de diferentes países, comparando **esforço** (investimento em P&D) com **resultado** (produção de conhecimento e tecnologia), a partir de dados públicos do Banco Mundial e da WIPO (Organização Mundial da Propriedade Intelectual).

Perguntas que o projeto busca responder:
- Quais países mais investem em P&D e possuem mais pesquisadores?
- Quais países mais geram patentes, marcas, desenhos industriais e exportações de alta tecnologia?
- Existe relação entre esforço e resultado?
- Como o Brasil se posiciona frente aos líderes?
- Como o Top 10 de cada indicador evolui ao longo de duas décadas?

## Fontes de dados

- **Banco Mundial**: Gasto em P&D (% do PIB), Pesquisadores em P&D, Pedidos de patentes, Exportações de alta tecnologia
- **WIPO**: Pedidos de patentes, Pedidos de marcas, Pedidos de desenhos industriais

Frequência de análise: recortes de 5 em 5 anos (2001, 2006, 2011, 2016, 2021 para o Banco Mundial; 2004, 2009, 2014, 2019, 2024 para a WIPO).

## Metodologia

O projeto segue a metodologia **CRISP-DM** (Cross-Industry Standard Process for Data Mining):

1. Entendimento do Negócio
2. Entendimento dos Dados
3. Preparação dos Dados (limpeza, padronização, consolidação)
4. Modelagem (rankings Top 10 e análise de correlação entre indicadores)
5. Avaliação
6. Implantação (tabelas finais e relatório)

## Status do projeto

- [x] Coleta e limpeza das 7 bases (Banco Mundial + WIPO)
- [x] Padronização de nomes de país e tradução para português
- [x] Base consolidada única
- [x] Top 10 por indicador (ano-base)
- [ ] Evolução do Top 10 ao longo dos 5 recortes de cada indicador
- [ ] Análise de correlação entre indicadores (esforço x resultado)
- [ ] Relatório final

## Como executar

O notebook foi desenvolvido no Google Colab, com os dados armazenados no Google Drive. Para rodar:
1. Faça o upload das bases de dados para uma pasta no seu Drive
2. Ajuste a variável `CAMINHO` no notebook para apontar para essa pasta
3. Execute as células em ordem (Setup → Funções → Carregamento → Preparação → Modelagem)

## Explorações extras

Ao longo do projeto, farei algumas análises pontuais para compartilhar no LinkedIn — não fazem parte da entrega formal do trabalho, mas documentam o processo e trazem recortes adicionais sobre os dados.

- **Brasil x China: 20 anos de inovação tecnológica** — comparação de trajetórias em investimento em P&D, patentes, marcas e desenhos industriais. [link do post]
- *(mais posts serão adicionados aqui conforme o projeto avança)*

## Autor

Gabriel Roledo — [GitHub](https://github.com/Gabriel-Roledo-ds)
