# ETL com python
## Dio lab-project

Neste projeto fiz o download da página com os livros mais vendidos da amazom.com.br, extrai as informações de título e autor e criei mensagens de marketing para cada livro usando Chat GPT.
### Etapas
1. Usando 'requests' obtive o conteúdo da url.
2. Com ajuda de BeautifulSoup extrai o nome dos livros e seus autores e os adicionei a listas.
3. Transformei os 10 primeiros itens das listas em um dictionary e depois em um dataframe de pandas.
4. Com ajuda de ChatGPT criei mensagens de marketing para os 10 mais vendidos e adicionei estas mensagens em uma nova columna do dataframe