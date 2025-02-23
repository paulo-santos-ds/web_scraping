# Web Scraping de Dados do IBGE

## 📌 Descrição
Este projeto realiza **Web Scraping** no site do **IBGE** para coletar e processar dados socioeconômicos do Brasil. A extração dos dados permite gerar insights, visualizar informações relevantes e utilizá-las para análises estatísticas.

## 🛠️ Tecnologias Utilizadas
- **Python** 🐍
- **Requests** - Para requisições HTTP
- **BeautifulSoup** - Para extração e parsing de HTML
- **Pandas** - Para manipulação e análise de dados
- **Jupyter Notebook** (opcional) - Para testes e desenvolvimento iterativo


## 📂 Estrutura do Projeto
```
/webscraping_ibge/
│-- main.py                # Script principal para extração e processamento dos dados
│-- requirements.txt       # Dependências do projeto
│-- data/                  # Pasta onde os dados extraídos serão salvos
│-- notebooks/             # Notebooks para testes e análises exploratórias
│-- README.md              # Documentação do projeto
```


## 🚀 Como Executar
### 1️⃣ Clone o repositório:
```bash
git clone https://github.com/seu-usuario/webscraping_ibge.git
cd webscraping_ibge
```

### 2️⃣ Instale as dependências:
```bash
pip install -r requirements.txt
```

### 3️⃣ Execute o script principal:
```bash
python main.py
```

Os dados extraídos serão salvos na pasta **data/**.

## 📊 Exemplos de Dados Coletados
O script extrai informações como:
- População por estado/município
- PIB per capita
- Taxa de desemprego
- Expectativa de vida

## ⚠️ Aviso Legal
O uso dos dados segue os termos e condições do IBGE. Certifique-se de consultar a **[Política de Uso de Dados](https://www.ibge.gov.br/)** antes de utilizar as informações extraídas.



