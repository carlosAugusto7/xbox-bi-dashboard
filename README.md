# 🎮 Xbox Analytics Hub - BI Dashboard

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.20+-FF4B4B.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458.svg)
![Status](https://img.shields.io/badge/Status-Concluído-success.svg)

Um painel de Business Intelligence (BI) interativo desenvolvido inteiramente em Python. Este projeto simula e analisa o ecossistema de vendas da Xbox, permitindo o acompanhamento do desempenho de consolas, subscrições do Game Pass, acessórios e hardware de PC.

🌐 **[Clica aqui para veres o Dashboard ao vivo](INSERE_AQUI_O_LINK_DO_TEU_STREAMLIT)**

---

## ✨ Funcionalidades

- **Design Imersivo:** Interface personalizada (Slate Dark) com a identidade visual da Xbox (fundo escuro e destaques em verde).
- **Filtros Dinâmicos:** Barra lateral interativa para segmentação de dados por Plataforma (Xbox Series X|S, PC, Cloud) e Categorias de Produto.
- **KPIs em Tempo Real:** Cartões de métricas que calculam automaticamente a receita total, volume de pedidos, ticket médio e a categoria líder.
- **Gráficos Interativos (Altair):** Visualização elegante da evolução financeira mensal e repartição de vendas sem fundo branco a contrastar.
- **Exportação de Dados:** Capacidade de descarregar os registos filtrados diretamente para um ficheiro CSV.

## 🛠️ Tecnologias Utilizadas

- **Python:** Linguagem principal.
- **Streamlit:** Framework para a criação da interface web e servidor interativo.
- **Pandas:** Manipulação, agrupamento e tratamento de dados.
- **NumPy:** Geração de dados simulados (Random seed).
- **Altair:** Biblioteca de visualização estatística declarativa para gráficos responsivos.

---

## 🚀 Como executar este projeto localmente

Se quiseres correr o projeto no teu próprio computador, segue os passos abaixo:

 1. Clonar o repositório
```bash
git clone [https://github.com/carlosAugusto7/xbox-bi-dashboard.git](https://github.com/carlosAugusto7/xbox-bi-dashboard.git)
cd xbox-bi-dashboard

2. Criar e ativar o ambiente virtual (Recomendado)
Para Windows:
python -m venv env
.\env\Scripts\activate

Bash
python -m venv env
.\env\Scripts\activate
Para Mac/Linux:

Bash
python3 -m venv env
source env/bin/activate

3. Instalar as dependências
Bash
pip install -r requirements.txt

4. Executar a aplicação
Bash
streamlit run meu_dashboard.py

Desenvolvido por
Carlos Augusto

GitHub: @carlosAugusto7
