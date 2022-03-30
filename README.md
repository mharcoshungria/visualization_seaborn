<img src="https://i.imgur.com/YX6UATs.png"  width="160">

# Gerando Resultados com o Seaborn

Este repositório é parte das tarefas da Formação Intensiva de Data Science da [Awari](https://awari.com.br/). 

##  Considerações iniciais

Este notebook tem o objetivo de orientá-lo sobre o uso inicial da biblioteca Seaborn.

### Por que o Seaborn?

O Seaborn fornece uma interface de alto nível para o Matplotlib, uma biblioteca de visualização Python poderosa, mas às vezes pesada. Apesar o Matplotlib ser bem completo, muitas vezes, você precisa Dentre as séries de vantagens do seaborn tenta facilitar do, a biblioteca tenta facilitar:
- Usar temas padrão que são esteticamente agradáveis.
- Definir paletas de cores personalizadas.
- Fazer gráficos estatísticos atraentes.
- Exibit distribuições com facilidade e flexibilidade.
- Visualizar as informações de matrizes e DataFrames.

Esses três últimos pontos são o motivo pelo qual a Seaborn é a nossa ferramenta preferida por muitos cientistas de dados, pois torna muito fácil "conhecer" seus dados com rapidez e eficiência.

**Contudo, não se esqueca!** Seaborn é um complemento, e não um substituto, para o Matplotlib. Existem alguns ajustes que ainda exigem o Matplotlib.

### Prepare seu ambiente

Se necessário, faça a instalação da biblioteca no seu sistema usando o gerenciador de pacotes da linguagem Python:
```
$ pip install seaborn
```

Ou caso esteja usando o Anaconda:
```
$ conda install seaborn
```

### Conjunto de dados

O conjunto de dados que iremos utilizar é a base de dados de alguns pokemons.

#### Descrição do dados

No arquivo [pokemon.csv](https://github.com/mharcoshungria/visualization_seaborn/blob/main/pokemon.csv), você encontrará as seguintes colunas:
- Name: Nome em inglês do pokemon
- Type 1: Tipo primário do pokemon
- Type 2: Tipo secundário do pokemon
- Total: Total
- HP: Pontos de vida
- Attack: Pontos de ataque
- Defense: Pontos de defesa
- Sp. Atk: Pontos base do ataque especial
- Sp. Def: Pontos base da defesa especial
- Speed: Pontos de agilidade
- Stage: Estágio de evolução
- Legendary: Se o pokemon é legendário.
