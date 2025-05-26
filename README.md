# **EDA-Most_Streamed_Sounds_Spotify**

## **Objetivo**

Os objetivos do projeto são:
- Encontrar os artistas mais ouvidos;
- Encontrar as músicas mais ouvidas;
- Encontrar os gêneros mais ouvidos;
- Entender o quanto os atributos musicais influenciam para uma música ser top streaming.
<br><br>

Conhecendo isto, saberemos em que tipo de conteúdo e em quais artistas investir para conseguir o melhor **retorno financeiro**.

## **Desenvolvimento**

Foram realizados os seguintes passos no desenvolvimento do projeto:

- Importação das bibliotecas;

- Carregamento do dataset;

- Visualização inicial dos dados;

- Verificação e tratamento de valores ausentes;

- Correção de tipos de dados;

- Análise univariada (distribuição de variáveis);

- Análise bivariada (correlações entre variáveis);

- Visualizações gráficas (gráficos de barras, histogramas, KDEplot, etc.);

- Insights e observações finais.

## **Conclusão**
<br>

Se pegarmos o Top 10 músicas mais tocadas e pesquisarmos os gêneros dos cantores ou bandas, podemos identificar quais os gêneros mais tocados:

| Nº | Artista(s)                   | Gêneros Musicais Principais            |
| -- | ---------------------------- | -------------------------------------- |
| 1  | The Weeknd                   | R\&B alternativo, Pop, Synthpop        |
| 2  | Ed Sheeran                   | Pop, Pop Rock, Folk Pop                |
| 3  | Lewis Capaldi                | Pop, Pop Rock, Soul                    |
| 4  | Tones and I                  | Indie Pop, Electropop, Alternative Pop |
| 5  | Post Malone, Swae Lee        | Hip Hop, Trap, Pop Rap, R\&B           |
| 6  | Drake, WizKid, Kyla          | Dancehall, Afrobeat, R\&B, Pop         |
| 7  | Justin Bieber, The Kid Laroi | Pop, Hip Hop, Pop Rap                  |
| 8  | Imagine Dragons              | Pop Rock, Electropop, Alternative Rock |
| 9  | The Chainsmokers, Halsey     | Electropop, EDM, Pop                   |
| 10 | The Weeknd, Daft Punk        | Synthpop, R\&B, Electronic             |

<br><br>

Podemos observar que gêneros como o **Pop** e variações como **Pop Rock**, **Folk Pop** e **Electropop** são gêneros que atraem uma grande quantidade de pessoas, então o ideal seria investir nesse tipo de gênero.

Também podemos verificar que "Feats." também atraem boa parte do público, então pode ser interessante criar este tipo de conteúdo.
<br><br>

Outros pontos em relação aos artistas e playlists são:

- A maior parte das músicas que estão no top 10 possuem no máximo 3 artistas ou bandas, diferente das outras que tem até 8 artistas;
- Temos músicas no top 100 que estão em poucas playlists, mas a maioria das músicas estão em muitas playlists, diferente das músicas fora do top 100, onde a grande maioria estão em poucas playlists;
<br><br>

Pensando sobre os atributos musicais, podemos dizer o seguinte:

- Grande parte das músicas do top 100 tem entre 80 e 140 batidas por minuto, um ritmo parecido com as músicas foras do top 100;
- Se comparado com as músicas fora do top 100, as músicas do top 100 tem uma dançabilidade mais baixa;
-  A maior parte das músicas do top 100 possuem 'valence' perto de 50%, ou seja, não transmitem nem felicidade nem tristeza, diferente das músicas de fora do top 100, que são mais felizes ou mais triste.
<br>

As ouras características não tem tanta diferença entre as músicas do top 100 e fora dele.
