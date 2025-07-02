# Análise de Campanha com Cupom - iFood Case

Este repositório contém a solução para o case técnico de Data Analyst do iFood, focado em analisar os efeitos de uma campanha promocional com cupons e propor melhorias baseadas em dados.

## Objetivo
Avaliar a eficácia de uma campanha com cupons de desconto através de um experimento A/B, identificar segmentos com maior responsividade e retorno financeiro, e sugerir estratégias mais eficientes para a empresa.

## Arquivos
- `1_data_preparation.ipynb`: Pipeline de extração, tratamento e agregação dos dados.
- `2_analysis.ipynb`: Análise do experimento A/B com teste de proporção e teste t.
- `3_financial_viability`: Análise de viabilidade financeira.
- `4_user_segmentation.ipynb`: Segmentação de usuários e avaliação estatística por grupo.
- `Case iFood.pdf`: Versão em slides com os principais achados, testes e recomendações estratégicas.

## Instruções de Execução

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
   ```

2. **Crie um ambiente virtual (opcional)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute os notebooks na ordem:**
   - `1_data_preparation.ipynb`
   - `2_analysis.ipynb`
   - `3_financial_viability.ipynb`
   - `4_user_segmentation.ipynb`

5. **Visualize a apresentação final**
   - O arquivo `Case iFood.pdf` contém a análise consolidada e visual.

## Tecnologias Usadas

- Python 3.x
- Pandas, NumPy
- SciPy, Statsmodels
- Seaborn, Matplotlib
- Jupyter Notebook
- requests

---

