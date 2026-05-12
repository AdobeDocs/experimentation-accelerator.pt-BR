---
solution: Journey Optimizer
product: journey optimizer
title: Acelerador de experimentação do Journey Optimizer
description: Uso de dados na IA com o Journey Optimizer Experimentation Accelerator
topic: Content Management
role: User
level: Beginner
keywords: conteúdo, experimento, vários, público-alvo, tratamento
TQID: https://experienceleague.adobe.com/FaQ5-cPzhnIplEoL1HwVh390jot-EA8G5u6JP8CVneI
product_v2:
  - id: cb954087-f4fc-4456-afb9-e939cabcdc79
feature_v2:
  - id: b3538224-471e-4c63-a444-9b19d89ae29c
  - id: b49ca41f-eb7a-4f4b-abeb-a97c06fd0c04
  - id: dc22c819-3f29-4e91-8b7d-5c6719831141
subfeature_v2:
  - id: fb9a80eb-bebc-492f-a0e9-584595621ebb
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: e8ccd51f-da0d-4e3b-939b-e30d5ebb1ea5
topic_v2:
  - id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
  - id: b5ce8718-c3af-4fdb-a1a9-fca32f83a87c
  - id: bcc5edb5-84c3-4940-9f84-ed88b6c16274
  - id: d095671a-1355-40aa-8b5f-06c33c68080b
  - id: e1e0219c-f879-479f-8427-888ed2a6e9c2
  - id: eb30f47f-d87a-400f-8f78-63ce7979ff56
source-git-commit: 659a4723ac8b7cbaf3ea06c34107bf876612ccb4
workflow-type: tm+mt
source-wordcount: 441
ht-degree: 2%

---

# Uso de dados na IA com o Journey Optimizer Experimentation Accelerator{#experiment-accelerator-security}

O **Adobe Journey Optimizer Journey Optimizer Experimentation Accelerator** permite que você descubra insights automaticamente e recomende oportunidades para melhorar seus experimentos e programa de experimentação. A solução usa IA e aprendizado de máquina para fornecer essas recomendações. Esta instrução esclarece como os dados de seus clientes são usados no **Journey Optimizer Experimentation Accelerator**.

## Quais dados a Journey Optimizer Experimentation Accelerator usa?

Atualmente, há três tipos de dados usados pelo **Journey Optimizer Experimentation Accelerator**:

* **Metadados de experimento**: nome do experimento, a definição do público-alvo usado no experimento e os tratamentos no experimento, por exemplo, nome, porcentagens divididas, local ou superfície em que o experimento é tratado.

* **Desempenho dos tratamentos**: número de pessoas, média da métrica de sucesso e desvio padrão para cada tratamento.

* **Conteúdo do tratamento**: o HTML renderizado e a captura de tela do tratamento como ele apareceria para um usuário no seu site.

## O que a Journey Optimizer Experimentation Accelerator faz com esses dados?

O **Journey Optimizer Experimentation Accelerator** pega o conteúdo de cada tratamento e cria uma incorporação, ou seja, uma representação matemática do conteúdo, e então correlaciona essas incorporações com o desempenho dos tratamentos. Esse processo permite a extração dos atributos de conteúdo que tiveram melhor desempenho para uso futuro. Esses atributos são alimentados em um modelo de linguagem grande hospedado pela Adobe, que os converte em instruções legíveis por humanos usadas para gerar insights e sugerir oportunidades.

## Quais restrições o Journey Optimizer Experimentation Accelerator tem sobre os dados usados?

Cada cliente é atribuído a uma organização e sandbox específicas. Um modelo dedicado é treinado para cada sandbox. Quando uma sandbox é excluída, todos os dados, sinais e modelos relacionados são removidos permanentemente.

* Usamos apenas os dados do cliente para treinar ou ajustar o modelo desse cliente.

* Nunca misturamos clientes para treinar ou ajustar um modelo.

## Os modelos do Adobe ou a IA mudarão a experiência do usuário de uma marca automaticamente?

Não. O **Journey Optimizer Experimentation Accelerator** faz recomendações somente sobre o que pode ser alterado e como pode ser alterado. Somente os usuários com permissões para alterar a experiência usando o Journey Optimizer ou o Target poderão agir de acordo com essas recomendações. Todas as recomendações podem ser revisadas e editadas antes de serem enviadas.

## Há algum risco para a estabilidade dos dados ou do sistema?

O **Journey Optimizer Experimentation Accelerator** assimila e analisa somente dados, produzindo insights e recomendações para testes futuros. Ele não tem acesso para modificar configurações de teste. Todas as sugestões geradas na ferramenta são enviadas ao Target e à Journey Optimizer para implementação, garantindo que não haja impacto nas atividades atuais de um cliente.
