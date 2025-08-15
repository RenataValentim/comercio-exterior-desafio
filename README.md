# Dashboard de Comércio Exterior 

Este projeto é um **desafio proposto** para criar um dashboard interativo em Python que mostra os **Top 3 produtos por tipo** (exportação e importação) por ano e por mês, por estado. O dashboard foi desenvolvido com **Dash** e **Plotly**.

---

## Como executar

1. **Instalar dependências**:

```bash
pip install pandas dash plotly
```

2. **Adicionar os CSVs originais em `dados/raw/`**:
Você pode baixar os dados no site oficial do [Comércio Exterior do Brasil](https://www.gov.br/mdic/pt-br/assuntos/comercio-exterior/estatisticas/base-de-dados-bruta) em NCM.

- EXP_2020_MUN.csv  
- EXP_2021_MUN.csv  
- IMP_2020_MUN.csv  
- IMP_2021_MUN.csv  

3. **Rodar o pipeline para processar os dados**:

```bash
python run_pipeline.py
```

4. **Executar o dashboard**:

```bash
python app.py
```

5. **Abrir no navegador e acessar**:

```
http://127.0.0.1:8050/
```

6. **Usar o dashboard**:

- Use os dropdowns para selecionar **ano** e **estado**.  
- Visualize os **Top 3 produtos por ano e por mês**.

---

💜 Desenvolvido por **Renata Valentim** como parte de um desafio de visualização de dados.
