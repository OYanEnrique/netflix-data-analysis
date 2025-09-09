[Read in english](README.en.md) 

# Netflix: Por Trás das Cenas de um Catálogo de Sucesso (2008-2021)

![Dashboard Netflix](dashboard.jpg)

## ❯ A Missão: Decodificando o Universo Netflix

A Netflix é mais do que um serviço de streaming; é uma das maiores bibliotecas de conteúdo digital do mundo, um universo em constante expansão. Mas, por trás da interface familiar, que história os dados nos contam? Quais são as estratégias, tendências e segredos escondidos em milhares de títulos?

Este projeto embarca em uma **jornada de análise de dados exploratória** para mergulhar fundo no catálogo da Netflix. Nossa missão é atuar como detetives de dados, usando Python e Looker Studio para desvendar os padrões que definiram o conteúdo da plataforma entre 2008 e 2021.

## 🗺️ O Mapa da Jornada: Fonte dos Dados

Toda grande expedição precisa de um mapa confiável. O nosso é um rico conjunto de dados obtido do Kaggle, detalhando cada filme e série na plataforma.

* **Fonte:** [Netflix Movies and TV Shows (Kaggle)](https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download)
* **Período:** 2008 a 2021

Este dataset foi nossa porta de entrada para entender a anatomia do catálogo, com informações cruciais como tipo, país de produção, ano de lançamento e gênero.

## 🛠️ O Arsenal do Explorador: Ferramentas Utilizadas

Para navegar neste mar de dados, fomos equipados com as melhores ferramentas do ecossistema de Data Science:

* **Linguagem de Programação:** Python 3
* **Mapa e Bússola (Manipulação de Dados):** Biblioteca Pandas
* **Lentes de Aumento (Visualização):** Bibliotecas Matplotlib & Seaborn
* **Diário de Bordo (Ambiente):** Jupyter Notebook
* **Painel de Comando Interativo:** Looker Studio

## 🧭 O Diário da Expedição: Análise Exploratória (EDA)

Nossa jornada foi documentada no notebook `Netflix.ipynb` e seguiu um roteiro claro para garantir que nenhum detalhe fosse perdido.

1.  **Primeiro Contato:** Carregamos o mapa (`netflix_titles.csv`) e fizemos uma inspeção inicial para entender o terreno, verificando a integridade e os tipos de dados.
2.  **Limpando o Terreno:** Lidamos com os territórios desconhecidos do mapa, tratando valores ausentes para diretores, elenco e países como "Unknown". Removemos algumas trilhas sem saída (linhas com dados nulos essenciais) e ajustamos nossas bússolas, convertendo as datas para um formato legível.
3.  **As Grandes Descobertas:** Com o mapa limpo, começamos a conectar os pontos, investigando a proporção de filmes e séries, identificando os principais centros de produção e mapeando a linha do tempo do crescimento do catálogo.

## 💡 As Revelações: Principais Insights Descobertos

Após a exploração, três grandes verdades sobre o universo Netflix vieram à tona.

### Revelação 1: O Reinado dos Filmes

Descobrimos que o catálogo é um reino dominado por filmes. Embora as séries gerem grandes discussões, são os longas-metragens que constituem a maior parte do território.

* **Filmes:** `69.7%` do catálogo
* **Séries de TV:** `30.3%` do catálogo

![Proporção de Filmes e Séries](pizza.png)

### Revelação 2: Os Titãs da Produção

A análise revelou uma clara superpotência na produção de conteúdo. Os Estados Unidos lideram de forma esmagadora, mas a presença de países como Índia e Reino Unido mostra a estratégia de investimento global da plataforma.

![Top 10 Países Produtores](bar.png)

### Revelação 3: A Era da Expansão

A linha do tempo do catálogo nos mostrou uma história de crescimento avassalador. A partir de 2016, a Netflix iniciou uma era de expansão agressiva, adicionando conteúdo a um ritmo sem precedentes, que atingiu seu auge em 2019.

![Evolução da Adição de Conteúdo](line.png)

## 📊 O Painel de Comando: Dashboard Interativo

Para permitir que outros exploradores naveguem por estas descobertas, todos os insights foram consolidados em um painel de comando interativo no Looker Studio. Filtre, explore e tire suas próprias conclusões!

**[>> Acesse o Dashboard Interativo aqui <<](https://lookerstudio.google.com/reporting/4cd71552-dd9b-4872-95e9-da4e3930505f)**

## 🚀 Refaça a Jornada: Como Utilizar

Quer seguir nossos passos e conduzir sua própria expedição? É simples:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/OYanEnrique/netflix-data-analysis.git
    ```
2.  **Prepare seu arsenal (instale as dependências):**
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  **Abra o diário de bordo:**
    ```bash
    jupyter notebook Netflix.ipynb
    ```

    ---

## 👨‍💻 O Arquiteto da Análise

* **Yan Enrique**
* **LinkedIn:** [https://www.linkedin.com/in/yanenrique/](https://www.linkedin.com/in/yanenrique/)
* **GitHub:** [https://github.com/OYanEnrique](https://github.com/OYanEnrique)
* **Landing page:** [https://yanenrique.carrd.co](https://yanenrique.carrd.co)
---
