# Macros

App web (um único `index.html`) para registar os macronutrientes do dia, pensada para telemóvel.

- **Primeira vez:** nome, idade, altura, peso → nº de refeições (3–7) → tipo/hora de cada uma → hora de treino (marca pré e pós-treino).
- **Registar macros do dia:** uma página por refeição, só com os alimentos habituais dessa refeição. `−`/`+` (10 g ou 1 un) ou toca no número para escolher quantidade rápida. "Igual à última vez" repete a refeição do último registo. No fim: totais, gráfico, tabela por refeição e resumo → **Gravar** ou **Descartar**.
- **Tabela nutricional:** todos os alimentos (por 100 g / unidade / scoop), editar e criar novos.
- **Histórico:** médias por dia (7 / 30 dias / sempre), gráfico de 14 dias, médias por semana e lista de dias.
- **Definições:** perfil, plano alimentar (refeições e alimentos), hora de treino, objetivo diário, cópia de segurança.

## Dados
Tudo fica guardado no próprio telemóvel (`localStorage`, chave `macros.v1`). Em **Definições → Exportar cópia**
gera um ficheiro `.json`; em **Importar** recupera tudo noutro telemóvel ou depois de reinstalar.

## Publicar
GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.
