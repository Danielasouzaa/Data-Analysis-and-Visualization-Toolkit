# Data Analysis and Visualization Toolkit

## Descrição

Este projeto é uma ferramenta simples e eficiente de análise exploratória de dados e visualização de gráficos. Ele permite carregar dados de arquivos CSV, incluindo URLs do Google Drive, para realizar diversas análises estatísticas e gerar gráficos automaticamente. A ferramenta também inclui uma análise especializada personalizada.

## Funcionalidades

- Carregamento de dados CSV a partir de URLs.
- Análise exploratória com estatísticas descritivas e informações sobre o conjunto de dados.
- Geração automática de gráficos: histograma, gráfico de barras, gráfico de pizza, gráfico de linha, gráfico de dispersão, boxplot e matriz de correlação.
- Análise especializada personalizada para fornecer insights adicionais sobre os dados.

## Tecnologias Utilizadas

- Python
- Pandas
- Matplotlib
- Seaborn
- Requests
  

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/data-analysis-toolkit.git

   Instale as dependências necessárias:
   !pip install -r requirements.txt
   Execute o script main.py com suas URLs de dados:
   python main.py
Exemplo de Uso
A seguir um exemplo de como fornecer URLs para análise:
urls = [
    "https://drive.google.com/file/d/1Yt8X9u62TWW-dkH4Kn-XYo4LegUcX_Ix/view?usp=sharing"
]
main(urls)
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

