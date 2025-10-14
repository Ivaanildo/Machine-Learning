## Machine Learning â€” Olist Analytics

Projeto de exploraÃ§Ã£o e modelagem com notebooks Jupyter. RepositÃ³rio limpo para publicaÃ§Ã£o no GitHub (sem dados brutos, segredos ou arquivos grandes sensÃ­veis).

**Estrutura**
- `analise_vendas_olist.ipynb`, `Untitled*.ipynb`: notebooks de anÃ¡lise/modelagem
- `data/`: coloque aqui os `.csv` (ignorado pelo Git)
- `feature_importance*.png`, `wordcloud*.png`, etc.: artefatos gerados
- `requirements.txt`: dependÃªncias

**Como Usar**
- Crie e ative um ambiente virtual (opcional):
  - `python -m venv .venv && ./.venv/Scripts/Activate.ps1` (Windows PowerShell)
- Instale dependÃªncias: `pip install -r requirements.txt`
- Coloque os dados na pasta `data/` (ex.: arquivos da Olist do Kaggle)
- Abra os notebooks: `jupyter lab` ou `jupyter notebook`

Se os notebooks referenciam arquivos na raiz, ajuste os caminhos para `data/<arquivo>.csv`.

**SeguranÃ§a**
- `.env` e credenciais sÃ£o ignorados por `.gitignore`.
- NÃ£o inclua chaves de API, tokens ou senhas nos notebooks. Prefira variÃ¡veis de ambiente.
- Se algum segredo for necessÃ¡rio, crie um `.env` local e, opcionalmente, um `.env.example` com chaves sem valores.

**Licença**
- MIT — veja LICENSE para detalhes.

