# README - Análise de Dados Financeiros do Programa de Aquisição de Alimentos (PAA)

## 📋 Sobre o Projeto

Este repositório contém um notebook Jupyter (`analytics.ipynb`) que realiza uma análise detalhada de dados financeiros e operacionais do **Programa de Aquisição de Alimentos (PAA)** no Brasil. Os dados analisados abrangem pactuações financeiras entre estados e municípios, com foco em identificar padrões, avaliar a execução dos recursos e explorar os públicos atendidos.

O **PAA** é uma iniciativa governamental voltada para a promoção da segurança alimentar e nutricional, além do fortalecimento da agricultura familiar. Os dados fornecem informações valiosas sobre a destinação de recursos, status dos planos operacionais e públicos beneficiados, como indígenas, quilombolas e comunidades vulneráveis.

---

## 🛠️ Funcionalidades

O notebook oferece as seguintes funcionalidades:

- **Importação e Manipulação de Dados:**
  - Leitura de arquivos Excel contendo informações financeiras detalhadas.
  - Tratamento e organização dos dados para análise.

- **Análise Estatística:**
  - Cálculo de métricas como valores pactuados, pagos e não executados.
  - Percentual de execução financeira por estado, município ou público atendido.

- **Visualizações Gráficas:**
  - Geração de gráficos para ilustrar a distribuição dos recursos.
  - Comparações entre diferentes categorias, como origem do orçamento e tipo de adesão.

- **Agrupamentos e Resumos:**
  - Consolidação dos dados por estado (UF), ano da pactuação, público atendido, entre outros.

---

## 🗂️ Descrição dos Dados

Os dados analisados estão organizados em um arquivo CSV/Excel com as seguintes colunas principais:

| Coluna                  | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| `CÓDIGO IBGE`           | Código IBGE do estado ou município.                                      |
| `UF`                    | Unidade Federativa (estado).                                             |
| `ESTADO/MUNICÍPIO`      | Nome do estado ou município.                                             |
| `TIPO ADESÃO`           | Tipo de adesão (Municipal ou Estadual).                                  |
| `ANO DA PACTUAÇÃO`      | Ano em que o plano foi pactuado.                                         |
| `Nº DO PLANO OPERACIONAL` | Número identificador do plano operacional.                              |
| `VIGÊNCIA`              | Data final da vigência do plano.                                         |
| `VALOR PACTUADO`        | Valor total pactuado em reais.                                           |
| `VALOR PAGO`            | Valor efetivamente pago em reais.                                        |
| `VALOR NÃO EXECUTADO`   | Diferença entre o valor pactuado e o valor pago.                        |
| `% DE EXECUÇÃO`         | Percentual de execução financeira.                                       |
| `ORIGEM DO ORÇAMENTO`   | Fonte dos recursos financeiros (ex.: Recurso Ordinário do Ministério).   |
| `STATUS`                | Status atual do plano (ex.: LIBERADO).                                   |
| `PÚBLICO ATENDIDO`      | Público-alvo dos recursos (ex.: Indígenas, Quilombolas).                 |
| `DATA DE REFERÊNCIA`    | Data usada como referência para os dados analisados.                     |

---

## 🔍 Destaques dos Dados

Os dados fornecem uma visão abrangente sobre a execução financeira do PAA:

- **Origem do Orçamento:** 
  - Recursos ordinários do ministério.
  - Créditos extraordinários.
  - Emendas parlamentares individuais ou coletivas.

- **Públicos Atendidos:**
  - Indígenas, quilombolas, comunidades rurais e outros grupos vulneráveis.
  - Regiões específicas, como Norte ou Sul.

- **Execução Financeira:**
  - Estados como Pará (PA) e Bahia (BA) apresentam os maiores valores pactuados.
  - Municípios com alta execução financeira (>90%) contrastam com outros que não executaram os valores pactuados.

- **Distribuição Regional:**
  - Comparação entre adesões estaduais e municipais.
  - Identificação de estados com maior percentual de execução.

---

## 🚀 Tecnologias Utilizadas

As seguintes bibliotecas Python foram utilizadas no desenvolvimento:

- **Pandas:** Manipulação e análise de dados tabulares.
- **NumPy:** Operações matemáticas e estatísticas.
- **Matplotlib:** Criação de gráficos básicos.
- **Seaborn:** Visualizações estatísticas avançadas.
- **OpenPyXL:** Leitura e escrita de arquivos Excel.

---

## 📈 Exemplos de Análises Realizadas

1. **Distribuição por Estado:**
   - Total de valores pactuados e pagos por estado (UF).
   - Percentual médio de execução por estado.

2. **Origem do Orçamento:**
   - Comparação entre diferentes fontes orçamentárias, como recursos ordinários e extraordinários.

3. **Público Atendido:**
   - Valores destinados a públicos específicos, como indígenas, quilombolas e regiões específicas.

4. **Performance Financeira:**
   - Identificação dos estados/municípios com maior percentual de execução financeira.

---

## 📋 Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Abra o notebook:
   ```bash
   jupyter notebook analytics.ipynb
   ```

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

---

## 📧 Contato

Para dúvidas ou sugestões, entre em contato pelo email: [danilo_ali1997@outlook.com]

--- 

**Licença:** Este projeto está licenciado sob a [MIT License](LICENSE).


---