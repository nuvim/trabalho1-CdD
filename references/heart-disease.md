### Análise do Conjunto de Dados: Heart Disease (Cleveland)

* **Número de Amostras (Linhas):** 303
* **Número de Atributos (Colunas):** 14

| Nome da Variável | Tipo | Descrição | Unidades | Valores Faltantes |
| :--- | :--- | :--- | :--- | :--- |
| `age` | Numero (inteiro) | Idade do paciente. | anos | Não |
| `sex` | Categórico | Sexo do paciente (1 = masculino; 0 = feminino). | N/A | Não |
| `cp` | Categórico | Tipo de dor no peito (Valor 1: angina típica, Valor 2: angina atípica, Valor 3: dor não anginosa, Valor 4: assintomático). | N/A | Não |
| `trestbps` | Numero (inteiro) | Pressão arterial em repouso na admissão. | mm Hg | Não |
| `chol` | Numero (inteiro) | Colesterol sérico. | mg/dl | Não |
| `fbs` | Categórico | Açúcar no sangue em jejum > 120 mg/dl (1 = sim; 0 = não). | N/A | Não |
| `restecg` | Categórico | Resultados do eletrocardiograma em repouso (0: normal, 1: anormalidade da onda ST-T, 2: hipertrofia ventricular esquerda). | N/A | Não |
| `thalach` | Numero (inteiro) | Frequência cardíaca máxima atingida. | bpm | Não |
| `exang` | Categórico | Angina induzida por exercício (1 = sim; 0 = não). | N/A | Não |
| `oldpeak` | Numero (float) | Depressão do segmento ST induzida pelo exercício em relação ao repouso. | N/A | Não |
| `slope` | Categórico | A inclinação do pico do segmento ST no exercício (Valor 1: ascendente, Valor 2: plano, Valor 3: descendente). | N/A | Não |
| `ca` | Numero (float) | Número de vasos principais (0-3) coloridos por fluoroscopia. | N/A | Sim |
| `thal` | Categórico | Resultado do teste de tálio (3 = normal; 6 = defeito fixo; 7 = defeito reversível). | N/A | Sim |
| `num` | Categórico | Diagnóstico de doença cardíaca (0 = ausência; 1,2,3,4 = presença). | N/A | Não |