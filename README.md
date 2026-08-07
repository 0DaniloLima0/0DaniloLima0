# 📈 Home Broker Profissional & Análise Fundamentalista (Método Barsi)

Terminal desktop desenvolvido em Python utilizando a biblioteca gráfica **Tkinter** para análise fundamentalista de ações da B3, inspirado na filosofia de investimentos de Luis Barsi (foco em dividendos, preço teto e margem de segurança).

---

## 🚀 Principais Funcionalidades

- **📊 Mercado Completo (B3):** Varredura e cálculo em tempo real de dezenas de ativos da B3 utilizando as bibliotecas `Fundamentus` e `Yahoo Finance`.
- **🎯 Critérios do Método Barsi:** Filtro inteligente de ativos com base no Preço Teto calculado com a média de dividendos dos últimos 6 anos, P/L e ROE.
- **📁 Relatório Setorizado em PDF:** Exportação de relatórios profissionais em PDF divididos por setores (Energia Elétrica, Bancos, Saneamento, etc.) com resumo executivo global.
- **⭐ Watchlist / Favoritos:** Acompanhamento rápido dos seus ativos prediletos.
- **💼 Mesa de Aportes e Carteira:** Simulador completo de investimentos com cálculo automático de Preço Médio, PM Ajustado por proventos, Yield on Cost (YoC), Caixa disponível e Gráfico de Alocação Setorial.
- **📰 Feed Macro ao Vivo:** Acompanhamento em tempo real do Ibovespa, Cotação do Dólar e notícias recentes de economia da B3.

---

## ⚙️ Tecnologias e Diferenciais Técnicos

- **Multithreading (`concurrent.futures`):** Utilização de `ThreadPoolExecutor` para processamento paralelo e carregamento em alta velocidade de dezenas de ativos da B3.
- **Web Scraping & APIs Financeiras:** Integração com `Fundamentus` para coleta de indicadores fundamentalistas e `yfinance` para monitoramento de cotações e feed macro ao vivo (Ibovespa e USD/BRL).
- **Geração Automatizada de Relatórios (`ReportLab`):** Motor customizado de exportação em PDF estruturado por setores e com resumo executivo global.
- **Interface Gráfica Nativa (`Tkinter`):** Desenvolvimento de dashboard profissional customizado com suporte a abas, canvas dinâmicos e alocação de carteira via gráficos de pizza.

---

## 🛠️ Stack Tecnológica

- **Python 3.x**
- **Tkinter** (Interface gráfica nativa)
- **Pandas** (Tratamento e análise de dados)
- **YFinance** (Dados de mercado e cotações em tempo real)
- **Fundamentus** (Indicadores fundamentalistas)
- **ReportLab** (Geração de relatórios em PDF)

---

## 📦 Como Instalar e Executar

1. **Clone ou baixe** este repositório para o seu computador.
2. Abra o terminal na pasta do projeto e instale as dependências necessárias executando o comando:
   ```bash
   pip install -r requirements.txt
