## Machine Learning — Olist Analytics

Projeto de exploração e modelagem com notebooks Jupyter. Repositório limpo para publicação no GitHub (sem dados brutos, segredos ou arquivos grandes sensíveis).

**Estrutura**
- `analise_vendas_olist.ipynb`, `Untitled*.ipynb`: notebooks de análise/modelagem
- `data/`: coloque aqui os `.csv` (ignorado pelo Git)
- `feature_importance*.png`, `wordcloud*.png`, etc.: artefatos gerados
- `requirements.txt`: dependências

**Como Usar**
- Crie e ative um ambiente virtual (opcional):
  - `python -m venv .venv && ./.venv/Scripts/Activate.ps1` (Windows PowerShell)
- Instale dependências: `pip install -r requirements.txt`
- Coloque os dados na pasta `data/` (ex.: arquivos da Olist do Kaggle)
- Abra os notebooks: `jupyter lab` ou `jupyter notebook`

Se os notebooks referenciam arquivos na raiz, ajuste os caminhos para `data/<arquivo>.csv`.

**Segurança**
- `.env` e credenciais são ignorados por `.gitignore`.
- Não inclua chaves de API, tokens ou senhas nos notebooks. Prefira variáveis de ambiente.
- Se algum segredo for necessário, crie um `.env` local e, opcionalmente, um `.env.example` com chaves sem valores.

**Licença**
- Sem licença explícita. Adicione uma se desejar compartilhar sob termos específicos.

