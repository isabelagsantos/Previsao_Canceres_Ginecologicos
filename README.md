# Previsão de casos mensais de cânceres ginecológicos no Brasil (2018–2025)

Trabalho prático da disciplina de **Métodos Estatísticos de Previsão (MEP)** – UFMG.

Aplicação de métodos estatísticos de previsão a uma série temporal de **casos mensais de diagnóstico de cânceres ginecológicos (CID C51–C58)** no Brasil, de **jan/2018 a dez/2025**.

## Sobre a série

| Item | Descrição |
|---|---|
| Fenômeno | Diagnósticos mensais de cânceres ginecológicos (CID C51–C58) |
| Abrangência | Brasil |
| Período | Janeiro/2018 a dezembro/2025 |
| Frequência | Mensal (12 observações por ano) |
| Observações | 96 |
| Variáveis | `mes_ano_diag` (mês/ano do diagnóstico) e `diag` (número de casos) |
| Arquivo de dados | `serie_casos_diagnostico_cancer_ginecologico_mensal_2018_2025.csv` |

### Divisão treino/teste

- **Treino (80%)**: primeiras 77 observações
- **Teste (20%)**: últimas 19 observações

## Estrutura do repositório

```
.
├── README.md
├── trab_pratico_mep.Rmd      # Código e análise (R Markdown)
└── serie_casos_diagnostico_cancer_ginecologico_mensal_2018_2025.csv    # Série mensal de casos diagnosticados
```


## Requisitos

- [R](https://www.r-project.org/) (≥ 4.0) e RStudio (recomendado)
- Pacotes:

```r
install.packages(c("tidyverse", "knitr", "kableExtra",
                   "patchwork", "forecast", "tseries"))
```

## Como executar

1. Clone ou baixe este repositório.
2. Coloque o arquivo CSV de dados na pasta do projeto.
3. No `trab_pratico_mep.Rmd`, ajuste o caminho da leitura dos dados para o seu computador:

   ```r
   dados <- read.csv("caminho/para/o/arquivo.csv")
   ```

4. Abra o `.Rmd` no RStudio e execute os blocos (*Run*) ou gere o relatório completo com **Knit**.

## Desenvolvimento

**Projeto em andamento.**
