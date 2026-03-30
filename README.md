# 📊 Estatística com Python: Frequências e Medidas

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)
![NumPy](https://img.shields.io/badge/NumPy-Latest-orange.svg)
![Status](https://img.shields.io/badge/Status-Completo-success.svg)

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Origem e Contexto](#-origem-e-contexto)
- [Funcionalidades](#-funcionalidades)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Dataset](#-dataset)
- [Estrutura do Projeto](#-estrutura-do-projeto)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Uso](#-uso)
- [Conteúdo Programático](#-conteúdo-programático)
- [Conceitos Estatísticos Abordados](#-conceitos-estatísticos-abordados)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Contribuindo](#-contribuindo)
- [Licença](#-licença)
- [Contato](#-contato)

## 🎯 Sobre o Projeto

Este projeto é uma implementação prática e completa de análise estatística descritiva utilizando Python, focando em **frequências** e **medidas estatísticas**. O objetivo é fornecer uma base sólida para compreensão e aplicação de conceitos estatísticos fundamentais através de notebooks Jupyter interativos.

O projeto utiliza dados reais da **Pesquisa Nacional por Amostra de Domicílios (PNAD) 2015** do IBGE, proporcionando uma experiência prática com dados demográficos brasileiros.

## 🎓 Origem e Contexto

> **Importante:** Este projeto foi desenvolvido como parte do **Curso de Estatística com Python: frequências e medidas** da [DevMedia](https://www.devmedia.com.br/).

O curso aborda conceitos fundamentais de estatística aplicados com Python, permitindo que desenvolvedores e analistas de dados compreendam e apliquem técnicas estatísticas em seus projetos profissionais.

## ✨ Funcionalidades

- 📊 **Análise Descritiva Completa**: Exploração detalhada de datasets com pandas
- 📈 **Visualização de Dados**: Geração de gráficos e histogramas com seaborn
- 🔢 **Distribuição de Frequências**: Criação de tabelas de frequência absoluta e relativa
- 📉 **Medidas de Tendência Central**: Cálculo de média, mediana e moda
- 📐 **Medidas Separatrizes**: Análise de quartis, decis e percentis
- 📏 **Medidas de Dispersão**: Cálculo de variância, desvio padrão e coeficiente de variação
- 🎯 **Classificação de Variáveis**: Identificação e tratamento de variáveis qualitativas e quantitativas
- 🔍 **Análise Exploratória**: Exercícios práticos com respostas detalhadas

## 🛠 Tecnologias Utilizadas

### Linguagem
- **Python 3.x** - Linguagem de programação principal

### Bibliotecas Python

| Biblioteca | Versão | Propósito |
|-----------|--------|-----------|
| **pandas** | Latest | Manipulação e análise de dados tabulares |
| **NumPy** | Latest | Computação numérica e operações matemáticas |
| **seaborn** | Latest | Visualização estatística de dados |
| **SciPy** | Latest | Funções estatísticas avançadas |
| **Jupyter Notebook** | Latest | Ambiente interativo de desenvolvimento |

### Ferramentas
- **Jupyter Notebook** - Desenvolvimento interativo
- **CSV** - Formato de armazenamento de dados

## 📦 Dataset

### Fonte de Dados

**Pesquisa Nacional por Amostra de Domicílios (PNAD) - 2015**

A PNAD é uma pesquisa do IBGE que investiga anualmente características gerais da população brasileira, incluindo educação, trabalho, rendimento e habitação.

**Fonte oficial:** [IBGE - PNAD 2015](https://ww2.ibge.gov.br/home/estatistica/populacao/trabalhoerendimento/pnad2015/microdados.shtm)

### Características do Dataset

- **Registros:** 76.840 observações
- **Formato:** CSV (Comma-Separated Values)
- **Tamanho:** ~2.2 MB
- **Escopo:** Pessoas de Referência de cada domicílio

### Variáveis Disponíveis

| Variável | Tipo | Descrição |
|----------|------|-----------|
| **UF** | Qualitativa Nominal | Unidade Federativa (código do estado brasileiro) |
| **Sexo** | Qualitativa Nominal | Sexo do morador (0=Masculino, 1=Feminino) |
| **Idade** | Quantitativa Discreta | Idade em anos completos |
| **Cor** | Qualitativa Nominal | Cor/raça declarada |
| **Anos de Estudo** | Quantitativa Discreta | Anos completos de escolaridade |
| **Renda** | Quantitativa Contínua | Rendimento mensal do trabalho principal (em R$) |
| **Altura** | Quantitativa Contínua | Altura em metros (variável elaborada) |

### Tratamento de Dados

Os seguintes pré-processamentos foram realizados:

1. ✅ Eliminação de registros com renda inválida (999.999.999.999)
2. ✅ Remoção de registros com renda ausente (missing values)
3. ✅ Filtro para pessoas de referência dos domicílios
4. ✅ Dados prontos para análise estatística

## 📁 Estrutura do Projeto

```
statistics-frequencies-measurements-main/
│
├── 📓 Curso_de_Estatística_Parte_1.ipynb
│   └── Notebook principal com todo o conteúdo do curso
│
├── 📓 Análise_Descritiva.ipynb
│   └── Exercícios práticos de análise descritiva
│
├── 📓 Análise_Descritiva_Respostas.ipynb
│   └── Soluções dos exercícios propostos
│
├── 📓 Verifica_versão.ipynb
│   └── Verificação de versões das bibliotecas
│
├── 📊 dados.csv
│   └── Dataset completo da PNAD 2015
│
└── 📄 README.md
    └── Documentação original do projeto
```

## 🔧 Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- **Python 3.7+** 
- **pip** (gerenciador de pacotes Python)
- **Jupyter Notebook** ou **JupyterLab**

### Verificação do Ambiente

```bash
# Verificar versão do Python
python --version

# Verificar pip
pip --version

# Verificar Jupyter
jupyter --version
```

## 📥 Instalação

### 1. Clone ou baixe o projeto

```bash
# Se estiver em um repositório Git
git clone <url-do-repositorio>
cd statistics-frequencies-measurements-main
```

### 2. Instale as dependências

```bash
# Criar ambiente virtual (recomendado)
python -m venv venv

# Ativar ambiente virtual
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate

# Instalar bibliotecas necessárias
pip install pandas numpy scipy seaborn jupyter matplotlib
```

### 3. Verifique a instalação

Execute o notebook `Verifica_versão.ipynb` para confirmar que todas as bibliotecas estão instaladas corretamente.

## 🚀 Uso

### Iniciando o Jupyter Notebook

```bash
# Navegar até o diretório do projeto
cd statistics-frequencies-measurements-main

# Iniciar Jupyter Notebook
jupyter notebook
```

O navegador abrirá automaticamente com a interface do Jupyter.

### Ordem de Estudo Recomendada

1. **Verifica_versão.ipynb** - Confirme seu ambiente
2. **Curso_de_Estatística_Parte_1.ipynb** - Conteúdo principal
3. **Análise_Descritiva.ipynb** - Pratique os conceitos
4. **Análise_Descritiva_Respostas.ipynb** - Confira suas respostas

### Execução dos Notebooks

```python
# Cada célula pode ser executada com Shift + Enter
# Ou usar o menu: Cell > Run All

# Exemplo de código básico presente nos notebooks:
import pandas as pd
import numpy as np
import seaborn as sns

# Carregar dados
dados = pd.read_csv('dados.csv')

# Visualizar primeiras linhas
dados.head()
```

## 📚 Conteúdo Programático

### 1. Conhecendo os Dados

- ✅ Importação e exploração do dataset
- ✅ Tipos de variáveis estatísticas
  - Qualitativas (Nominais e Ordinais)
  - Quantitativas (Discretas e Contínuas)
- ✅ Classificação de variáveis
- ✅ Estrutura e características dos dados

### 2. Distribuição de Frequências

- ✅ Tabelas de frequência absoluta
- ✅ Tabelas de frequência relativa
- ✅ Frequência acumulada
- ✅ Histogramas
- ✅ Método de Sturges para definição de classes
- ✅ Construção de intervalos de classe

### 3. Medidas de Tendência Central

- ✅ **Média aritmética**
  - Simples
  - Ponderada
- ✅ **Mediana**
  - Conceito e cálculo
  - Robustez a outliers
- ✅ **Moda**
  - Distribuições unimodais, bimodais e multimodais
- ✅ Comparação entre as medidas
- ✅ Escolha da medida adequada

### 4. Medidas Separatrizes

- ✅ **Quartis** (Q1, Q2, Q3)
- ✅ **Decis** (D1 a D9)
- ✅ **Percentis** (P1 a P99)
- ✅ Interpretação e aplicações
- ✅ Box plots e análise de dispersão

### 5. Medidas de Dispersão

- ✅ **Amplitude total**
- ✅ **Variância**
  - População
  - Amostra
- ✅ **Desvio padrão**
- ✅ **Coeficiente de variação**
- ✅ Interpretação da dispersão
- ✅ Comparação entre diferentes grupos

## 🎯 Conceitos Estatísticos Abordados

### Tipos de Variáveis

#### Qualitativas
- **Nominais**: Não possuem ordem (ex: Sexo, Cor, UF)
- **Ordinais**: Possuem ordem natural (ex: Escolaridade)

#### Quantitativas
- **Discretas**: Valores contáveis (ex: Idade, Anos de Estudo)
- **Contínuas**: Valores mensuráveis (ex: Renda, Altura)

### Medidas Estatísticas

```python
# Exemplo de cálculos disponíveis nos notebooks

# Média
media_renda = dados['Renda'].mean()

# Mediana
mediana_renda = dados['Renda'].median()

# Moda
moda_idade = dados['Idade'].mode()[0]

# Desvio padrão
desvio_renda = dados['Renda'].std()

# Quartis
q1 = dados['Renda'].quantile(0.25)
q2 = dados['Renda'].quantile(0.50)  # Mediana
q3 = dados['Renda'].quantile(0.75)

# Descrição completa
dados.describe()
```

## 💡 Exemplos de Uso

### Análise de Renda por Estado

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Carregar dados
dados = pd.read_csv('dados.csv')

# Estatísticas de renda por UF
renda_por_uf = dados.groupby('UF')['Renda'].describe()
print(renda_por_uf)

# Visualização
plt.figure(figsize=(12, 6))
sns.boxplot(x='UF', y='Renda', data=dados)
plt.title('Distribuição de Renda por Estado')
plt.xticks(rotation=45)
plt.show()
```

### Distribuição de Frequências

```python
# Criar classes de renda
bins = [0, 1000, 2000, 5000, 10000, 50000]
labels = ['0-1k', '1k-2k', '2k-5k', '5k-10k', '10k+']

dados['Faixa_Renda'] = pd.cut(dados['Renda'], bins=bins, labels=labels)

# Tabela de frequências
freq_absoluta = dados['Faixa_Renda'].value_counts().sort_index()
freq_relativa = dados['Faixa_Renda'].value_counts(normalize=True).sort_index()

tabela_freq = pd.DataFrame({
    'Frequência Absoluta': freq_absoluta,
    'Frequência Relativa': freq_relativa,
    'Percentual': freq_relativa * 100
})

print(tabela_freq)
```

### Comparação de Medidas de Tendência Central

```python
# Analisar variável Renda
print("=== ANÁLISE DA RENDA ===")
print(f"Média: R$ {dados['Renda'].mean():.2f}")
print(f"Mediana: R$ {dados['Renda'].median():.2f}")
print(f"Moda: R$ {dados['Renda'].mode()[0]:.2f}")
print(f"Desvio Padrão: R$ {dados['Renda'].std():.2f}")

# Histograma
plt.figure(figsize=(10, 6))
plt.hist(dados['Renda'], bins=50, edgecolor='black', alpha=0.7)
plt.axvline(dados['Renda'].mean(), color='r', linestyle='--', label='Média')
plt.axvline(dados['Renda'].median(), color='g', linestyle='--', label='Mediana')
plt.xlabel('Renda (R$)')
plt.ylabel('Frequência')
plt.title('Distribuição de Renda')
plt.legend()
plt.show()
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você deseja melhorar este projeto:

1. Fork o repositório
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

### Sugestões de Melhorias

- 📊 Adicionar mais visualizações
- 🔍 Incluir análises mais avançadas
- 📝 Expandir a documentação
- 🧪 Adicionar testes estatísticos
- 🎨 Melhorar visualizações existentes

## 📄 Licença

Este projeto é baseado no curso da DevMedia e destina-se a fins educacionais.

Os dados utilizados são de domínio público, disponibilizados pelo IBGE.

## 📞 Contato

**Projeto baseado em:** Curso de Estatística com Python - DevMedia

**Dataset:** [IBGE - PNAD 2015](https://ww2.ibge.gov.br/home/estatistica/populacao/trabalhoerendimento/pnad2015/microdados.shtm)

---

## 📌 Notas Adicionais

### Recursos de Aprendizado

- 📖 [Documentação Pandas](https://pandas.pydata.org/docs/)
- 📖 [Documentação NumPy](https://numpy.org/doc/)
- 📖 [Documentação Seaborn](https://seaborn.pydata.org/)
- 📖 [Documentação SciPy Stats](https://docs.scipy.org/doc/scipy/reference/stats.html)

### Troubleshooting

**Problema:** Erro ao importar bibliotecas
```bash
# Solução: Reinstalar dependências
pip install --upgrade pandas numpy scipy seaborn matplotlib
```

**Problema:** Jupyter Notebook não abre
```bash
# Solução: Verificar instalação
pip install --upgrade jupyter
jupyter notebook --version
```

**Problema:** Arquivo dados.csv não encontrado
```python
# Solução: Verificar caminho relativo
import os
print(os.getcwd())  # Mostra diretório atual
# Ajustar caminho se necessário
```

---

<div align="center">

### ⭐ Se este projeto foi útil para você, considere dar uma estrela!

**Desenvolvido com** ❤️ **para aprendizado de Estatística com Python**

[🔝 Voltar ao topo](#-estatística-com-python-frequências-e-medidas)

</div>
