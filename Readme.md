🛠️ EM DESENVOLVIMENTO 🚧

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

A análise sugere que as ações implementadas para elevar os padrões de segurança na aviação — possivelmente envolvendo manutenção, treinamento, tecnologia e protocolos — foram eficazes. Houve redução consistente de acidentes, incidentes e incidentes graves, evidenciando uma melhoria significativa na segurança operacional ao longo dos anos.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">


📊 1. Análise Temporal
Quantidade de ocorrências por ano (ano)

Tendência temporal das classificações: acidentes, incidentes e incidentes graves por ano (ocorrencia_classificacao)

Datas e horários com mais ocorrências: analisar ocorrencia_dia e ocorrencia_hora

Tempo médio entre ocorrência e publicação de relatório (divulgacao_dia_publicacao - ocorrencia_dia)

🌎 2. Análise Geográfica
Cidades e estados com mais ocorrências (ocorrencia_cidade, ocorrencia_uf, ocorrencia_pais)

Mapa de calor com latitude e longitude (ocorrencia_latitude, ocorrencia_longitude)

Aeródromos mais recorrentes (ocorrencia_aerodromo)

✈️ 3. Análise de Aeronaves
Modelos mais envolvidos em ocorrências (aeronave_modelo, aeronave_fabricante)

Tipo de motor mais comum em ocorrências (aeronave_motor_tipo, aeronave_motor_quantidade)

Fase de operação com mais ocorrências (aeronave_fase_operacao)

Nível de dano mais frequente (aeronave_nivel_dano)

Total de fatalidades (aeronave_fatalidades_total) — média, mediana e valores extremos

🔍 4. Classificação das Ocorrências
Distribuição entre acidente, incidente, incidente grave (ocorrencia_classificacao)

Tipo de ocorrência mais comum (ocorrencia_tipo, ocorrencia_tipo_categoria, taxonomia_tipo_icao)

Ocorrência com saída de pista? (ocorrencia_saida_pista)

📄 5. Recomendações de Segurança
Quantidade de recomendações por ocorrência (total_recomendacoes)

Destinatários mais recorrentes (recomendacao_destinatario)

Status das recomendações (recomendacao_status)

Tempo médio entre recomendação e feedback (diferença entre recomendacao_dia_assinatura, recomendacao_dia_encaminhamento, recomendacao_dia_feedback)

🧠 6. Fatores Contribuintes
Áreas mais citadas como causadoras (fator_area)

Nome e aspecto dos fatores mais comuns (fator_nome, fator_aspecto, fator_condicionante)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

🧰 Ferramentas utilizadas:
pandas para agrupar e filtrar dados

matplotlib / seaborn / plotly para gráficos de linha, barras, pizza e mapa

folium ou plotly express para mapas interativos com latitude/longitude
