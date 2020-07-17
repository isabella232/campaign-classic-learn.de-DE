---
title: Konfigurieren von Workflows in Adobe Campaign Classic
seo-title: Konfigurieren von Workflows in Adobe Campaign Classic
description: Adobe Campaign bietet Marketingexperten mehrere Möglichkeiten zur Überprüfung und Bereitstellung von Versand-, Kampagne-, Extraktion- und Budgetgenehmigungen. In diesem Lernprogramm wird beschrieben, wie Sie verschiedene Workflows für die Genehmigungsüberprüfung konfigurieren.
seo-description: In diesem Video wird erläutert, wie Sie eine Versandvorlage in ACCAdobe Kampagne konfigurieren und verwenden können. Es werden verschiedene Optionen für Marketingexperten zur Überprüfung und Bereitstellung von Versand-Inhalten, Kampagne-Zielgruppe, Extraktion von Daten und Budgetgenehmigungen erläutert. In diesem Lernprogramm wird beschrieben, wie Sie verschiedene Workflows für die Genehmigungsüberprüfung konfigurieren.
uuid: fdeb7aef-95aa-4bc1-9c51-2eb7ce802107
discoiquuid: 29abc57d-c359-472d-817a-0671818894f0
feature: Workflow
topics: Validation
kt: KT-1566
doc-type: feature video
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '356'
ht-degree: 0%

---


# Konfigurieren von Workflows in Adobe Campaign Classic

Adobe Campaign bietet Marketingexperten mehrere Möglichkeiten zur Überprüfung und Bereitstellung von Versand-, Kampagne-, Extraktion- und Budgetgenehmigungen.

In diesem Lernprogramm wird beschrieben, wie Sie verschiedene Workflows für die Genehmigungsüberprüfung konfigurieren.

## Voraussetzung {#prerequisite}

Vor der Aktivierung der Genehmigungsschritte muss das Marketingteam einzelne Prüfer definieren:

* Die Rolle &quot;Adobe Campaign-Reviewer&quot;in einer Aktivität der Genehmigung kann entweder ein einzelner Reviewer (Operator) oder eine Gruppe von Reviewern (Operator-Rolle) sein.
* Die Reviewer- und Reviewer-Gruppen müssen zuvor in Adobe Campaign von einer Administratorrolle konfiguriert werden. Auf diese Weise können Entwickler von Kampagnen die Prüfer als Genehmiger in einer Kampagne oder einem Versand auswählen.

## Genehmigungen für Kampagnen konfigurieren  {#configuring-approvals-for-campaigns}

Wenn Sie im Arbeitsablauf für die Kampagne dieselben Prüfer für alle Versand verwenden, würden Sie die Genehmigungsfunktionen nutzen [!DNL Campaign] . Durch die Einrichtung von Genehmigungen und Prüfern auf der Ebene der Kampagne werden die Aufgaben und Prüfer für die Genehmigung nach der Ausführung des Workflows auf die einzelnen Versand-Aktivitäten Ihres Workflows heruntergefahren.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Genehmigungen für Versand konfigurieren  {#configuring-approvals-for-deliveries}

Sie können auch Genehmigungen auf Versand-Ebene einrichten. Wenn Versand Schritte und Prüfer genehmigen und sich von den Genehmigungsschritten und Prüfern der Kampagne unterscheiden, werden die Einstellungen für die Kampagne durch die Versand außer Kraft gesetzt.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Konfigurieren einer Aktivität zur Genehmigung  {#configuring-an-approval-activity}

Im Gegensatz zu Versand- oder Kampagne-Genehmigungen ermöglicht die Aktivität für die Genehmigung die Erstellung eines Genehmigungsprozesses in einem Workflow. Auf diese Weise kann die Targeting-Auswahllogik genehmigt werden, bevor der Versand gestartet wird. Sie ermöglicht bei Bedarf auch eine Genehmigung auf mehreren Ebenen im Workflow.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

For more information, refer to the [Approval Documentation](https://docs.adobe.com/help/en/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
