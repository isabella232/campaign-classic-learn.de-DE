---
title: Konfigurieren von Validierungs-Workflows in Adobe Campaign Classic
description: Erfahren Sie, wie Sie verschiedene Validierungs-Workflows konfigurieren.
feature: Workflows, Validierungen
kt: 1566
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
exl-id: 34fbb91d-ae99-497c-872e-55ce2e6ea2aa
source-git-commit: 4e3ffe869c735138b50d54a72a569552952f03fc
workflow-type: tm+mt
source-wordcount: '271'
ht-degree: 0%

---


# Validierungs-Workflows erstellen

Adobe Campaign bietet Marketing-Experten verschiedene Möglichkeiten, Versandinhalte, Kampagnenziele, Datenextraktion und Budgetvalidierungen zu überprüfen und bereitzustellen.

In diesem Tutorial wird erläutert, wie verschiedene Validierungs-Workflows für die Genehmigung konfiguriert werden.

## Voraussetzung {#prerequisite}

Vor der Aktivierung der Validierungsschritte muss das Marketing-Team die einzelnen Validierer definieren:

* Die Adobe Campaign-Überprüferrolle innerhalb einer Genehmigungsaktivität kann entweder ein einzelner Validierer (Benutzer) oder eine Gruppe von Validierern (Benutzerrolle) sein.
* Damit die Kampagnenentwickler die Validierungsverantwortlichen als Validierer in einer Kampagne oder einem Versand auswählen können, müssen die Validierer und Validierergruppen von einem Administrator in Adobe Campaign konfiguriert werden.

## Validierungen für Kampagnen konfigurieren {#configuring-approvals-for-campaigns}

Wenn Sie in Ihrem Kampagnen-Workflow für alle Sendungen denselben Satz von Validierungsverantwortlichen haben, wenden Sie die Validierungsfunktion der Kampagne an, indem Sie Validierungen und Validierungsverantwortliche auf Kampagnenebene einrichten. Die Validierungsaufgaben und Validierungsverantwortlichen werden nach der Ausführung des Workflows in jede Versandaktivität Ihres Workflows verschoben.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Validierungen für Sendungen konfigurieren {#configuring-approvals-for-deliveries}

Sie können Validierungen auch auf Versandebene einrichten. Wenn sich die Schritte zur Validierung eines Versands und die Validierer von den Schritten zur Kampagnenvalidierung und den Validierern unterscheiden, werden die Kampagnenparameter durch die Versandeinstellungen außer Kraft gesetzt.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Validierungsaktivität konfigurieren {#configuring-an-approval-activity}

Im Gegensatz zu Versand- oder Kampagnengenehmigungen ermöglicht die Validierungsaktivität die Erstellung eines Validierungsprozesses innerhalb eines Workflows. Auf diese Weise kann die Targeting-Auswahllogik vor dem Start des Versands validiert werden. Sie ermöglicht bei Bedarf auch die Genehmigung auf mehreren Ebenen innerhalb des Workflows.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Weitere Informationen finden Sie in der [Validierungsdokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
