# Radar Estratégico de Supply Chain · GHT

Site estático (index.html + data.json + img/).

- `scripts/coletar_indicadores.py`: busca câmbio, Selic, IPCA e IGP-M no Banco Central e atualiza o `data.json`.
- `.github/workflows/atualizar.yml`: roda o script em dias úteis às 7h40 (Brasília) e salva o resultado.
- Notícias, status e textos dos blocos são editados no `data.json`.
