# Machine Learning — Olist Analytics

## 📊 Sobre o Projeto

Projeto de ciência de dados focado em exploração, análise e modelagem de machine learning utilizando dados da Olist (plataforma brasileira de e-commerce). Este repositório contém notebooks Jupyter com análises completas, visualizações e modelos preditivos.

**Objetivo:** Demonstrar pipeline completo de análise de dados, desde a exploração inicial até a implementação de modelos de machine learning para insights de negócio.

---

## 📁 Estrutura do Projeto

| Arquivo/Pasta | Descrição |
|---------------|----------|
| `analise_vendas_olist.ipynb` | Notebook principal com análise exploratória e modelagem |
| `Untitled*.ipynb` | Notebooks experimentais de análise e testes |
| `data/` | Diretório para arquivos `.csv` (ignorado pelo Git) |
| `feature_importance*.png` | Gráficos de importância de features gerados |
| `wordcloud*.png` | Nuvens de palavras e outras visualizações |
| `requirements.txt` | Lista de dependências Python do projeto |
| `.gitignore` | Arquivos e pastas ignorados pelo controle de versão |

---

## 🚀 Como Usar

### 1. Clone o Repositório

```bash
git clone https://github.com/Ivaanildo/Machine-Learning.git
cd Machine-Learning
```

### 2. Configure o Ambiente Virtual (Recomendado)

**Windows (PowerShell):**
```powershell
python -m venv .venv
./.venv/Scripts/Activate.ps1
```

**Linux/Mac:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Instale as Dependências

```bash
pip install -r requirements.txt
```

### 4. Adicione os Dados

- Baixe os dados da Olist do [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Coloque os arquivos `.csv` na pasta `data/`
- Exemplo de estrutura:
  ```
  data/
  ├── olist_orders_dataset.csv
  ├── olist_customers_dataset.csv
  └── ...
  ```

### 5. Execute os Notebooks

```bash
jupyter lab
# ou
jupyter notebook
```

**Nota:** Se os notebooks referenciam arquivos na raiz, ajuste os caminhos para `data/<arquivo>.csv`.

---

## 📚 Conteúdo dos Notebooks

- **Análise Exploratória de Dados (EDA):** Estatísticas descritivas, distribuições e correlações
- **Visualizações:** Gráficos interativos e informativos sobre vendas, produtos e clientes
- **Feature Engineering:** Criação e transformação de variáveis para modelagem
- **Modelagem:** Algoritmos de machine learning para previsões e classificações
- **Avaliação:** Métricas de performance e interpretação de resultados

---

## 🔒 Segurança e Boas Práticas

- ✅ Arquivos `.env` e credenciais são ignorados pelo `.gitignore`
- ✅ **Nunca inclua** chaves de API, tokens ou senhas diretamente nos notebooks
- ✅ Utilize **variáveis de ambiente** para informações sensíveis
- ✅ Se necessário, crie um arquivo `.env` local e um `.env.example` (sem valores reais) como template

**Exemplo de `.env`:**
```
API_KEY=sua_chave_aqui
DATABASE_URL=sua_url_aqui
```

---

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Jupyter Notebook/Lab
- Pandas, NumPy (manipulação de dados)
- Scikit-learn (machine learning)
- Matplotlib, Seaborn (visualização)
- E outras listadas em `requirements.txt`

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Consulte o arquivo `LICENSE` para mais detalhes.

---

## 👤 Autor

**Ivaanildo**
- GitHub: [@Ivaanildo](https://github.com/Ivaanildo)

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
- Abrir issues para reportar bugs ou sugerir melhorias
- Enviar pull requests com novos recursos ou correções
- Compartilhar feedback sobre as análises

---

**⭐ Se este projeto foi útil, considere dar uma estrela no repositório!**
