---
solution: Journey Optimizer
product: journey optimizer
title: Métricas do Journey Optimizer Experimentation Accelerator
description: Melhore a sua capacidade de conduzir experimentos com eficiência e gerar insights
topic: Content Management
role: User
level: Beginner
keywords: conteúdo, experimento, vários, público-alvo, tratamento
TQID: https://experienceleague.adobe.com/OrtdIfQfKMIWODRi9fr-dEuc7g06hISv6-Dq-54qGeY
product_v2: id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2: id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2: id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2: id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2: id: aa2f3246-cb95-4b30-8899-fdf7d73550ccid: bcc5edb5-84c3-4940-9f84-ed88b6c16274id: e1e0219c-f879-479f-8427-888ed2a6e9c2
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 364
ht-degree: 6%

---

# Métricas {#experiment-accelerator-metrics}

A página **[!UICONTROL Métricas]** exibe as métricas de sucesso dos experimentos do Journey Optimizer e do Target em um único local, permitindo o monitoramento do desempenho, a comparação e insights mais profundos.

## Painel {#dashboard}

Ao acessar a guia **[!UICONTROL Métricas]**, todas as métricas de sucesso disponíveis do Journey Optimizer e do Adobe Target são listadas em uma exibição consolidada para ajudá-lo a acompanhar o desempenho nas iniciativas, comparar resultados e identificar rapidamente as áreas que exigem atenção.

Acesse filtros clicando em ![](assets/do-not-localize/Smock_Filter_18_N.svg), que oferece opções específicas de contexto, como filtragem por **[!UICONTROL Source]** ou **[!UICONTROL Usado em experimentos ativos]**.

Como alternativa, localize rapidamente qualquer métrica digitando seu nome na barra de pesquisa.

![](assets/experiment-monitor-metrics.png)

## Detalhes da métrica {#metric-details}

### Incremental ao longo do tempo

![](assets/experiment-monitor-metrics-2.png)

O gráfico **[!UICONTROL Incremental ao longo do tempo]** fornece um detalhamento visual de como a métrica selecionada está em tendência ao longo de um intervalo de tempo escolhido. Use o menu suspenso para alternar entre exibições diárias ou semanais a fim de ajustar o nível de granularidade.

Os seguintes valores de resumo estão disponíveis para referência rápida:

* **[!UICONTROL Total]**: o valor cumulativo da métrica selecionada durante o período do relatório.

* **[!UICONTROL Média]**: o valor típico da métrica calculada através do intervalo de tempo selecionado. Ao equilibrar as flutuações diárias ou semanais, ele fornece um quadro mais claro do desempenho normal e pode ser usado como uma linha de base para comparação.

* **[!UICONTROL Taxa de conversão]**: porcentagem de perfis que concluíram a ação desejada (por exemplo, compra, inscrição) após verem o tratamento.

Cada valor inclui uma alteração de porcentagem em relação ao período anterior, tornando fácil ver se o desempenho está melhorando, diminuindo ou permanecendo estável.

### Efeito do experimento

![](assets/experiment-monitor-metrics-3.png)

Esta seção exibe todos os experimentos ativos dentro do período selecionado (Últimos 90 dias, Últimos 30 dias ou Últimos 7 dias) e destaca sua contribuição para a métrica.

As seguintes métricas estão disponíveis:

* **[!UICONTROL Aumento]**: medida da melhora da porcentagem na taxa de conversão de um determinado tratamento em relação à linha de base.

* **[!UICONTROL Confiança]**: evidência de que um determinado tratamento é igual ao tratamento de linha de base. [Saiba mais](http://experienceleague.adobe.com/en/docs/journey-optimizer/using/content-management/content-experiment/technotes/experiment-calculations)

* **[!UICONTROL Contribuição]**: a proporção da alteração geral na métrica que pode ser atribuída a um experimento ou tratamento específico, permitindo a identificação das iniciativas que exercem o maior impacto relativo.
