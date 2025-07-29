# ✈️ Análise de Atrasos de Voos em Nova York (2013)

Este projeto em R realiza uma análise dos dados de voos a partir dos aeroportos de Nova York no ano de 2013, utilizando a base `nycflights13`. O foco é identificar quais companhias aéreas tiveram os **maiores atrasos médios na decolagem**.

---

## 📌 Objetivos

- Explorar a base `flights` da biblioteca `nycflights13`
- Calcular o atraso médio de cada companhia aérea
- Visualizar os resultados com um gráfico de barras horizontal
- Salvar o gráfico como imagem

---

## 📦 Pacotes utilizados

- [`dplyr`](https://dplyr.tidyverse.org/)
- [`ggplot2`](https://ggplot2.tidyverse.org/)
- [`nycflights13`](https://cran.r-project.org/web/packages/nycflights13/index.html)

---

## 📁 Arquivos do projeto

| Arquivo                    | Descrição                                  |
|---------------------------|---------------------------------------------|
| `analise_atrasos_voos.R`  | Script principal em R com toda a análise    |
| `grafico_atrasos.png`     | Gráfico de barras gerado com ggplot2        |
| `README.md`               | Documentação do projeto                     |

---

## 🧪 Como executar

1. Instale os pacotes necessários:
   ```r
   install.packages(c("dplyr", "ggplot2", "nycflights13"))

2. Rode o script analise_atrasos_voos.R no RStudio:
   source("analise_atrasos_voos.R")

3. O gráfico será salvo automaticamente como grafico_atrasos.png.


📚 Fonte dos dados

Os dados são disponibilizados pelo pacote nycflights13, que contém registros públicos da FAA sobre voos nos EUA em 2013.

👩‍💻 Autor(a)

Projeto desenvolvido por Glaucia.
Sinta-se à vontade para adaptar e usar em seus estudos ou portfólio.

📜 Licença

Este projeto está sob a licença MIT.


