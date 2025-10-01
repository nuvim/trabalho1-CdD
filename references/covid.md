### Análise do Conjunto de Dados: COVID-19 Brasil

* **Número de Amostras (Linhas):** (Preencha com o número que aparece no `.info()`)
* **Número de Atributos (Colunas):** (Preencha com o número total de colunas)

| Nome da Variável | Tipo | Descrição | Unidades | Valores Faltantes |
| :--- | :--- | :--- | :--- | :--- |
| `date` | Data/Hora | Data em que os dados foram registrados. | N/A | 0 |
| `state` | Categórico | Sigla da Unidade Federativa (Estado) do registro. | N/A | 0 |
| `city` | Categórico | Nome do município do registro. Pode ser nulo para totais estaduais. | N/A |20119 |
| `place_type` | Categórico | Indica se o registro se refere a uma 'city' (cidade) ou 'state' (estado). | N/A | 0 |
| `new_confirmed` | Número (inteiro) | Número de novos casos confirmados registrados na data. | Casos | 0 |
| `new_deaths` | Número (inteiro) | Número de novas mortes confirmadas registradas na data. | Mortes | 0 |
| `last_available_confirmed` | Número (inteiro) | Total acumulado de casos confirmados até a data do registro. | Casos | 0 |
| `last_available_deaths` | Número (inteiro) | Total acumulado de mortes confirmadas até a data do registro. | Mortes | 0 |
| `city_ibge_code` | Número (inteiro) | Código IBGE que identifica unicamente o município. | N/A | 13646 |
| `estimated_population` | Número (inteiro) | População estimada para o local (cidade/estado). | Pessoas | 13646 |
| `epidemiological_week` | Número (inteiro) | Semana epidemiológica do ano correspondente à data. | N/A | 0 |
| `order_for_place` | Número (inteiro) | Dia sequencial da pandemia para aquele local (1º dia, 2º dia, etc.). | N/A | 0 |
| `is_last` | Categórico (booleano) | Indica se é o registro mais recente para aquele local (`True`/`False`). | N/A | 0 |
| `last_available_death_rate`| Número (float) | Taxa de letalidade (mortes / casos) calculada até a data. | Taxa | 0 |
| `last_available_confirmed_per_100k_inhabitants`| Número (float) | Casos confirmados por 100 mil habitantes. | Casos por 100k hab. | 29166 |