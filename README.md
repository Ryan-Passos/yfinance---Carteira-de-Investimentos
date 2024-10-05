# yfinance---Carteira-de-Investimentos

# Otimizador de Carteira de Investimentos

Este projeto é um otimizador de carteira de investimentos que permite ao usuário selecionar um nível de risco e calcula a alocação ideal de ativos com base nos retornos históricos das ações selecionadas. O sistema utiliza a biblioteca `yfinance` para coletar dados financeiros e técnicas de otimização para sugerir uma carteira eficiente.

## Funcionalidades

- Coleta de dados históricos de ações utilizando `yfinance`.
- Cálculo de retornos e volatilidade anualizados.
- Otimização da carteira com base em um nível de risco selecionado pelo usuário.
- Cálculo e exibição de métricas de risco: VaR (Value at Risk) e CVaR (Conditional Value at Risk).
- Visualização gráfica da alocação de ativos e evolução de retornos e riscos ao longo do tempo.

## Pré-requisitos

Para executar este projeto, você precisa ter as seguintes bibliotecas instaladas:

- `yfinance`
- `numpy`
- `pandas`
- `scipy`
- `matplotlib`

Você pode instalar essas bibliotecas usando `pip`:

```bash
pip install yfinance numpy pandas scipy matplotlib
