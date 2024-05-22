# Web Scrapping no Mercado Livre
## [Fonte - Luciano Galvão](https://github.com/lvgalvao/projetoscrapingaovivo)

Para rodar o web scraping

```bash
cd src\coleta
scrapy crawl mercadolivre -o ../../data/data.jsonl
cd ..\..
```

Para rodar o PANDAS tem que fazer isso dentro da pasta SRC

```bash
cd src\
python transformacao/main.py
cd..
```

Para rodar o Streamlit tem que fazer isso dentro da pasta SRC

```bash
cd src\
streamlit run dashboard/app.py 
cd..
```