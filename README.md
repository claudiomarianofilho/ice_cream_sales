# 🍦 Previsão de Vendas de Sorvetes com Machine Learning

Bem-vindo ao repositório do projeto de **Ice Cream Sales**! Este projeto utiliza algoritmos de Machine Learning para prever as vendas de sorvetes com base em dados históricos e fatores como clima.

## 🧐 Sobre o Projeto

O objetivo deste projeto é desenvolver um modelo preditivo que ajude comerciantes e empresas de sorvete a otimizar suas estratégias de estoque e vendas. Compreendendo melhor os padrões de consumo, é possível tomar decisões mais informadas e minimizar perdas.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 🐍
- **Bibliotecas:**
  - Pandas (manipulação de dados)
  - NumPy (operações matemáticas)
  - Scikit-learn (treinamento de modelos)
  - Matplotlib e Seaborn (visualizações de dados)
- **Ferramentas:**
  - Jupyter Notebook (análises e experimentos)

## 📂 Estrutura do Projeto

```plaintext
|-- data/                # Dados brutos e processados
|-- notebooks/           # Notebooks para análise e experimentos
|-- models/              # Modelos treinados e arquivos de configuração
|-- src/                 # Código-fonte do projeto
    |-- preprocess.py    # Scripts para processamento de dados
    |-- train.py         # Treinamento de modelos
    |-- predict.py       # Script para previsões
|-- requirements.txt     # Dependências do projeto
|-- README.md            # Documentação do projeto
```

## 🧪 Como Executar

### Pré-requisitos:
1. Tenha o Python 3.8+ instalado.
2. Instale as dependências do projeto:
   ```bash
   pip install -r requirements.txt
   ```

### Passos:
1. Clone este repositório:
   ```bash
   git clone https://github.com/claudiomarianofilho/previsao-vendas-sorvetes.git
   cd previsao-vendas-sorvetes
   ```
2. Coloque os dados na pasta `data/`.
3. Execute os notebooks na pasta `notebooks/` para explorar e treinar o modelo.
4. Faça previsões executando o script:
   ```bash
   python src/predict.py --input data/novos_dados.csv
   ```

## 📈 Resultados Esperados

Com base nos dados fornecidos (como temperatura, dia da semana, etc.), o modelo retorna a previsão de vendas em unidades de sorvete. O desempenho do modelo pode ser avaliado utilizando métricas como RMSE, MAE e R².

## 🚀 Próximos Passos

- Incorporar mais variáveis externas, como eventos locais e dados demográficos.
- Testar outros algoritmos de aprendizado, como Redes Neurais e XGBoost.
- Criar uma interface gráfica para facilitar o uso do modelo por comerciantes.

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Siga os passos abaixo para contribuir:
1. Faça um fork do repositório.
2. Crie uma branch com sua feature/bugfix:
   ```bash
   git checkout -b minha-feature
   ```
3. Envie um pull request. Vamos revisar com carinho! 😊

## 📄 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

💡 **"Saber prever é o primeiro passo para saber crescer!"**
