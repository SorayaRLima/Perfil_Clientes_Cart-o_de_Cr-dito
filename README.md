# 📊 Análise do Perfil Financeiro de Clientes

Este projeto tem como objetivo analisar dados de clientes adimplentes de uma instituição financeira fictícia, identificando padrões de comportamento, níveis de engajamento e oportunidades para estratégias de negócio.

---

## 🎯 Objetivos

- Entender o perfil demográfico e financeiro dos clientes adimplentes
- Identificar padrões de uso de produtos financeiros
- Explorar relações entre escolaridade, renda, tipo de cartão e valor transacionado
- Auxiliar na construção de estratégias de marketing, upgrades e retenção

---

## ⚙️ Estrutura do Projeto

1. **Configuração do Ambiente**

   O ambiente virtual foi criado com o comando:
   ```bash
   python -m venv trabalho_python
   ```
   E ativado com:
   ```bash
   .\trabalho_python\Scripts\activate
   ```

2. **Instalação de Bibliotecas**

   As principais bibliotecas utilizadas são:
   ```bash
   pip install pandas matplotlib numpy seaborn
   ```

   | Biblioteca   | Função principal                                                             |
   |--------------|------------------------------------------------------------------------------|
   | pandas       | Leitura e manipulação de dados em tabelas (DataFrames)                       |
   | matplotlib   | Visualizações básicas (gráficos de barras, linhas)                           |
   | seaborn      | Gráficos estatísticos com foco em análise visual                             |
   | numpy        | Operações numéricas e vetoriais                                              |

---

## 📂 Dados Utilizados

O dataset foi carregado a partir de um arquivo `.csv`, contendo informações como:

- Idade
- Escolaridade
- Faixa salarial
- Tipo de cartão
- Valor médio transacionado
- Tempo de inatividade (meses sem transações)

Após o carregamento, foi feita uma filtragem para manter apenas clientes adimplentes.

---

## 🔍 Etapas da Análise

### 🔹 Limpeza e Preparação dos Dados

- Tratamento de valores ausentes (NaN)
- Conversão de tipos de dados
- Padronização de categorias (ex: escolaridade, tipo de cartão)
- Criação de métricas como `valor_médio_transacionado`

### 🔹 Análise Exploratória

Foram realizadas análises descritivas e visuais, como:

- Distribuição de idade
- Comparativo de movimentação por tipo de cartão
- Relações entre escolaridade, renda e engajamento
- Perfil dos clientes inativos

---

## 📈 Principais Gráficos

- **Gráfico 1: Escolaridade x Valor Transacionado**  
  Mostra que quanto maior a escolaridade e a faixa salarial, maior o valor movimentado.  
  Clientes com pós-graduação e cartões premium (Black/Platinum) lideram em transações.

- **Gráfico 2: Inatividade x Tipo de Cartão**  
  Evidencia que clientes com maior inatividade usam cartões básicos e movimentam menos dinheiro, enquanto usuários de cartões premium tendem a manter movimentações constantes.

---

## 🧠 Conclusões

- A renda e escolaridade influenciam diretamente o volume transacionado
- Cartões premium estão associados a clientes mais engajados
- Cartões básicos concentram a maioria dos usuários com longos períodos de inatividade

---

## 💼 Aplicações para o Negócio

Com base nos dados, é possível aplicar estratégias como:

- Campanhas de upgrade para clientes de alto potencial (ex: de Básico para Platinum)
- Segmentação de marketing baseada em perfis de engajamento
- Ajuste de limites de crédito de forma inteligente
- Retenção ativa de clientes premium
- Monitoramento de risco com base em tempo de inatividade

---

## 📁 Organização do Código

```
projeto-perfil-financeiro-clientes/
├── trabalho_modulo_3_python.ipynb   # Notebook principal da análise
├── dados/
│   └── clientes.csv                 # Dataset de clientes
├── README.md                        # Documentação explicativa
└── imagens/                         # Gráficos exportados para uso em apresentação
```

---

## 🙏 Agradecimentos

Este projeto foi desenvolvido como projeto final do módulo de Python do curso de Data analytics da @Digital College.  
Agradeço a professora @Nayara Walewski por todo apoio e ensinamento.
