Descrição do Projeto
Este projeto analisa a pegada de carbono do Brasil em comparação com métricas globais, regionais (Américas), países da OCDE e os Estados Unidos. Ele combina técnicas de análise de dados, estatísticas descritivas e aprendizado de máquina para responder a questões relevantes sobre emissões de CO₂ e prever padrões ambientais. O objetivo é oferecer insights para políticas públicas e estratégias de mitigação ambiental.

Objetivos Principais
Entender a evolução da pegada de carbono do Brasil ao longo do tempo.
Comparar a pegada de carbono brasileira com médias globais, regionais e da OCDE.
Analisar a contribuição de diferentes fontes de combustível nas emissões do Brasil.
Identificar fatores relevantes para prever emissões e classificar países em altos ou baixos emissores.
Propor estratégias para o Brasil reduzir sua pegada de carbono.
Estrutura do Projeto
Etapa de Perguntas de Pesquisa:
Definição de 10 perguntas-chave sobre a pegada de carbono e os fatores relacionados.

Exploração e Limpeza de Dados:

Conjunto de dados sobre emissões de CO₂ e consumo de combustíveis.
Tratamento de inconsistências, como substituição de valores inválidos e merge de tabelas.
Análise Descritiva:
Visualização da distribuição de emissões globais e comparações entre Brasil, América Latina, OCDE e Estados Unidos.

Aplicação de Modelos de Machine Learning:

Regressão Linear: Previsão de emissões com base no consumo de combustíveis.
Árvore de Decisão: Classificação de países como altos ou baixos emissores.
Visualizações:
Gráficos para ilustrar a evolução das emissões e comparações entre regiões.

Conclusões:

Identificação de disparidades nas emissões.
Sugestões para mitigação de impacto ambiental no Brasil.
Pré-requisitos
Linguagem: Python 3.8+
Bibliotecas:
pandas
matplotlib
seaborn
scikit-learn
Instruções de Execução
Instale as dependências:

bash
Copiar código
pip install pandas matplotlib seaborn scikit-learn
Prepare os dados:
Insira os arquivos de dados no diretório correto e ajuste os caminhos no código.

tidy_format_co2_emission_dataset.csv
GCB2022v27_MtCO2_flat.csv
Execute o script principal:
Execute o notebook ou script Python para gerar análises e previsões.

Resultados Obtidos
Insights:

O Brasil tem emissões maiores do que a média global e da OCDE.
Combustíveis fósseis e desmatamento são as principais fontes de emissão.
Políticas de mitigação precisam focar na expansão de energia renovável e redução do desmatamento.
Modelos de Machine Learning:

A regressão linear mostrou-se eficaz na previsão de emissões.
A árvore de decisão classificou países com alta precisão como altos ou baixos emissores.
Autores
Samuel Ramos de Almeida
Guilherme Silva dos Santos
