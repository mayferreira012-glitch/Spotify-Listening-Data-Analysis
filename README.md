# Spotify Listening Analytics Dashboard

## Sobre o Projeto

Dashboard analítico desenvolvido em Power BI utilizando o histórico completo de streaming exportado pelo Spotify.
O projeto foi criado com o objetivo de transformar dados brutos de reprodução musical em indicadores e visualizações capazes de revelar padrões de comportamento, hábitos de consumo e preferências musicais ao longo de mais de 10 anos de utilização da plataforma.
Os dados foram extraídos diretamente do Spotify e passaram por processos de tratamento, modelagem e enriquecimento para construção de uma solução analítica completa.

---

## Objetivos

* Analisar hábitos de consumo musical ao longo do tempo.
* Identificar artistas, músicas e álbuns mais reproduzidos.
* Avaliar padrões de escuta por horário e dia da semana.
* Investigar o comportamento de músicas concluídas e puladas.
* Medir o impacto do modo aleatório (shuffle) e do modo offline.
* Comparar o uso entre diferentes dispositivos e plataformas.

---

## Tecnologias Utilizadas

* Power BI
* Power Query
* DAX
* Modelagem Dimensional
* Bookmarks
* Data Visualization

---

## Arquitetura da Solução

```text
  Spotify Export 
        │
        ▼
 Power Query (ETL)
        │
        ▼
 Modelo Dimensional
        │
 ├── Fato Streaming
 └── Dimensão Calendário
        │
        ▼
      DAX
        │
        ▼
   Dashboards Power BI
```

---

## Estrutura dos Dados

Os dados de origem contêm informações detalhadas de cada reprodução realizada no Spotify, incluindo:
* Data e hora da reprodução
* Música
* Artista
* Álbum
* Tempo reproduzido
* Plataforma utilizada
* País de conexão
* Status de música pulada
* Uso de modo aleatório
* Uso offline

---

## Páginas do Dashboard

### Visão Geral

Indicadores gerais do histórico de consumo musical:
* Tempo total de reprodução
* Quantidade de reproduções
* Músicas distintas
* Álbuns distintos
* Evolução anual do tempo consumido
* Taxa de músicas concluídas e puladas

### Perfil de Consumo

Análise comportamental de utilização:
* Reprodução por período do dia
* Reprodução por dia da semana
* Heatmap horário
* Sazonalidade mensal

### Ranking Musical

Análise dos conteúdos mais consumidos:
* Artistas mais ouvidos
* Músicas mais reproduzidas
* Álbuns mais reproduzidos
* Participação percentual dos artistas mais relevantes

### Comportamento de Reprodução

Análises relacionadas ao uso da plataforma:
* Shuffle ligado vs desligado
* Offline vs online
* Distribuição do tempo de reprodução
* Plataformas mais utilizadas

### Análise Avançada de Artistas

Investigação do comportamento de reprodução por artista:
* Artistas mais ouvidos em modo aleatório
* Artistas com maior quantidade de músicas puladas
* Evolução dos artistas mais escutados por ano

---

## Principais Insights

### Forte concentração em poucos artistas

Apesar da grande diversidade musical, parte significativa do tempo total de reprodução está concentrada em um grupo reduzido de artistas favoritos.

### Consumo predominante durante tarde e noite

A maior parte das reproduções ocorre nos períodos da tarde e da noite.

### Celular como principal dispositivo

O smartphone representa a maior parcela das reproduções realizadas.

### Baixa taxa de músicas puladas

A maior parte das reproduções é concluída, indicando comportamento de escuta relativamente consistente.

### Evolução de preferências ao longo dos anos

Os rankings anuais permitem observar mudanças claras nos artistas mais consumidos ao longo do período analisado.

---

## Recursos de UX

O relatório utiliza:
* Navegação por bookmarks
* Filtros globais
* Segmentação por artista
* Segmentação por álbum
* Segmentação por período
* Navegação entre páginas

---

## Competências Demonstradas

* ETL com Power Query
* Modelagem Dimensional
* Uso de Dimensões
* DAX
* Storytelling com Dados
* Design de Dashboards
* Bookmarks e Navegação Avançada
* Análise Exploratória de Dados
* Business Intelligence

---

## Possíveis Evoluções

* Integração com Spotify API
* Classificação por gênero musical
* Análise de popularidade das músicas
* Clusterização de preferências musicais
* Comparação entre períodos de consumo
* Dashboard em atualização automática

## Acesso ao dashboard
[Spotify-Listening-Data-Analysis](https://bit.ly/4b4pBTj)


