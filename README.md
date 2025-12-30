# 🎯 Mega-Sena Data Analysis with Python

Análise estatística da **Mega-Sena (1999 → atual)** utilizando **Python**, **dados oficiais da Caixa** e técnicas básicas de **Data Analysis**.

> ⚠️ **Aviso importante:**
> Este projeto **não prevê resultados**, **não garante ganhos** e **não promete números vencedores**.
> O objetivo é **educacional e técnico**, focado em **método, código e raciocínio estatístico**.

---

## 📌 Objetivo do Projeto

Demonstrar como:

* Coletar dados reais via HTTP
* Processar arquivos XLSX oficiais
* Aplicar análise estatística básica
* Gerar insights a partir de grandes volumes de dados
* Estruturar um projeto de análise em Python

Usando a Mega-Sena apenas como **estudo de caso didático**.

---

## 📊 O que é analisado

* 📅 Histórico completo dos concursos (desde 1999)
* 🔢 Frequência das dezenas
* ⚖️ Distribuição par x ímpar
* ➕ Soma média dos números sorteados
* 🎯 Geração de jogos baseada em critérios estatísticos

---

## 🧠 Resultados (Exemplo)

```text
Total de concursos carregados: 2954
Soma média histórica: 183.23
Par x Ímpar: 50.2% pares | 49.8% ímpares
Top dezenas: [10, 53, 5, 37, 34, 33, 38, 4, 30, 27]
```

🎯 **Jogos gerados (base estatística):**

```text
Jogo 1: [5, 7, 24, 34, 45, 47]
Jogo 2: [11, 12, 15, 52, 53, 56]
...
```

> ❗ Jogos gerados **não aumentam probabilidade**.
> Servem apenas para **organização estatística de escolhas**.

---

## 📥 Fonte dos Dados

* Dados oficiais da Caixa Econômica Federal
* Download automático via requisição HTTP:

```
https://servicebus2.caixa.gov.br/portaldeloterias/api/resultados/download?modalidade=Mega-Sena
```

---

## 🛠️ Tecnologias Utilizadas

* Python 3.10+
* Pandas
* Requests
* OpenPyXL
* Logging
* Estatística descritiva

---

## 📂 Estrutura do Projeto

```
mega-sena-analysis/
│
├── megasenavirada.py
├── data/
│   └── mega-sena.xlsx
├── logs/
│   └── execution.log
├── README.md
└── requirements.txt
```

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/mega-sena-analysis.git
cd mega-sena-analysis
```

2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute o script:

```bash
python megasenavirada.py
```

---

## 🎓 Finalidade Educacional

Este projeto foi desenvolvido para:

* Estudo de **Python aplicado**
* Demonstração de **análise de dados real**
* Base para **conteúdo educacional** e **curso futuro**

Não é uma ferramenta de apostas.

---

## 🤝 Contribuições

Contribuições são bem-vindas:

* Refatoração
* Visualizações gráficas
* Testes automatizados
* Melhorias estatísticas
* Documentação

Abra uma **issue** ou envie um **pull request**.

---

## 📢 Autor

**DEV BAGUAL**
Desenvolvedor • Python • Data Analysis
Instagram / Twitch: **@dev_bagual**

---

## ⭐ Observação Final

> **Aprenda o método.
> Ignore a promessa.
> Use dados.**

---
