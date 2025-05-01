# 📊 Análise de Cancelamentos de Clientes

Este projeto realiza uma análise exploratória de dados para entender os **motivos de cancelamento de clientes** com base em uma base de dados (`cancelamentos.csv`). A análise visa encontrar padrões e propor possíveis soluções para **reduzir a taxa de cancelamento**.

## 🛠️ Tecnologias Utilizadas

- Python
- pandas
- plotly.express (para visualização de dados)

## 📂 Etapas da Análise

1. **Carregamento da base de dados**  
   - Leitura do arquivo CSV.  
   - Exclusão da coluna `CustomerID`.

2. **Tratamento de dados ausentes**  
   - Identificação e remoção de linhas com valores nulos.

3. **Análise inicial dos cancelamentos**  
   - Proporção de clientes que cancelaram ou não.

4. **Investigação de variáveis relacionadas**  
   - Duração do contrato.  
   - Tipo de assinatura.  
   - Ligações ao callcenter.  
   - Dias de atraso.

5. **Filtragem de dados relevantes**  
   - Foco em clientes com menos de 5 ligações ao callcenter.  
   - Consideração de até 20 dias de atraso no pagamento.

6. **Visualização gráfica**  
   - Geração de histogramas interativos para cada variável em relação ao cancelamento.

## 📈 Exemplos de Insights

- Contratos mensais apresentam maior taxa de cancelamento.  
- Clientes com mais ligações ao callcenter e mais dias de atraso tendem a cancelar mais.

## 📁 Como Usar

1. Certifique-se de ter o Python instalado com as bibliotecas `pandas` e `plotly`.
2. Coloque o arquivo `cancelamentos.csv` na mesma pasta do script.
3. Execute o script Python para visualizar a análise e gráficos interativos.

```bash
pip install pandas plotly
python analise_cancelamentos.py
