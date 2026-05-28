---
keywords: acelerador de experimentação;espaço de trabalho de destino;atribuição de sandbox;otimizador do adobe jornada;integrações
description: Saiba como mapear espaços de trabalho do Adobe Target para sandboxes do Experimentation Accelerator para que as equipes possam exibir experimentos da Adobe Target e do Adobe Journey Optimizer em um único local.
title: Como integrar o  [!DNL Target]  ao Experimentation Accelerator?
feature: Integrations
source-git-commit: 6c8e2f6297a649e103dea9d5f4d3ff4c0fbf2aa4
workflow-type: tm+mt
source-wordcount: '237'
ht-degree: 5%

---

# Integrar o [!DNL Target] ao Experimentation Accelerator

O Experimentation Accelerator ajuda os administradores a gerenciar como as atividades do espaço de trabalho do [!DNL Adobe Target] são organizadas e exibidas no aplicativo. Mapeando cada espaço de trabalho do [!DNL Target] para a sandbox apropriada do Experimentation Accelerator, as equipes podem exibir experimentos de [!DNL Adobe Target] e [!DNL Adobe Journey Optimizer] em um único local.

➡️ [Saiba mais sobre o Adobe Experimentation Accelerator](https://experienceleague.adobe.com/pt-br/docs/experimentation-accelerator/using/overview)

## Antes de começar

Antes de configurar atribuições de sandbox, confirme se você tem as permissões necessárias. Para acessar a **[!UICONTROL Administração]** no Experimentation Accelerator, você deve ter a permissão **[!UICONTROL Gerenciar configuração]**.

Os usuários podem atribuir espaços de trabalho [!DNL Target] a sandboxes somente quando ambas as condições são atendidas:

* O usuário tem a permissão **[!UICONTROL Gerenciar configuração]** no Experimentation Accelerator.
* O usuário é um administrador de produto [!DNL Target].

## Configurar atribuição de sandbox para [!DNL Target] espaços de trabalho

Antes de atribuir espaços de trabalho, observe que o espaço de trabalho [!DNL Target] pode ser atribuído a apenas uma sandbox para evitar entradas duplicadas para o mesmo teste.

Para escolher qual sandbox cada espaço de trabalho [!DNL Target] aparece em:

1. No Experimentation Accelerator, abra **[!UICONTROL Administração]**.

   ![](assets/experimentation-1.png)

1. Revise a tabela de [!DNL Target] atribuições atuais de espaço de trabalho para sandbox.

   ![](assets/experimentation-2.png)

1. Clique em **[!UICONTROL Edit]**.

   ![](assets/experimentation-3.png)

1. Para cada sandbox, atribua os espaços de trabalho [!DNL Target] apropriados.

   ![](assets/experimentation-4.png)

1. Clique em **[!UICONTROL Salvar]** para aplicar as alterações.

Depois que a conexão inicial for criada para um espaço de trabalho [!DNL Target], aguarde até 30 minutos para que as atualizações se propaguem pelo sistema.
