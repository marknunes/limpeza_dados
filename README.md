📊 Análise e Limpeza de Dados de Churn
Este projeto tem como objetivo realizar a limpeza e padronização dos dados de churn de clientes, garantindo que o dataset esteja pronto para análises futuras e modelos preditivos.

📂 Sobre o Dataset
O dataset contém informações sobre clientes, como idade, saldo bancário, pontuação de crédito, estado, gênero, salário e se o cliente saiu ou não da empresa (churn).

🛠️ Etapas do Processamento
🔹 Carregamento dos dados

Importação do dataset Churn.csv.
Exibição das primeiras linhas (head()).
Verificação do tamanho da base de dados (shape).
🔹 Tratamento de valores ausentes (NaN)

Identificação das colunas com valores ausentes (isnull().sum()).
Substituição de valores nulos na coluna salário pela mediana.
Preenchimento dos valores nulos na coluna gênero com a moda (Masculino).
🔹 Padronização de dados categóricos

Ajuste de valores inconsistentes na coluna gênero (M → Masculino, F → Feminino).
Correção de estados inválidos (RP, SP, TD → RS).
🔹 Tratamento de valores inconsistentes

Correção de idades fora do intervalo esperado (< 0 ou > 120) pela mediana.
Identificação e remoção de IDs duplicados.
🔹 Tratamento de outliers

Detecção de outliers no salário (acima de 2 desvios padrão).
Substituição desses valores pela mediana.
🔹 Exportação do dataset limpo

O dataset tratado foi salvo como Churn_tratado.csv e disponibilizado para download.
🚀 Como Executar
1️⃣ Faça upload do arquivo Churn.csv no Google Colab.
2️⃣ Execute os blocos de código do notebook para limpeza e análise dos dados.
3️⃣ Baixe o dataset tratado Churn_tratado.csv para uso em modelos de machine learning ou análise estatística.

🛠️ Tecnologias Utilizadas
Pandas → Manipulação e limpeza de dados
Seaborn → Visualização gráfica
Statistics → Cálculo de estatísticas descritivas
Google Colab → Ambiente de execução
📌 Este projeto faz parte do estudo sobre limpeza e preparação de dados para análise exploratória e modelagem preditiva.

