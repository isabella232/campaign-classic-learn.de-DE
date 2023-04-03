---
title: Konfigurieren wiederkehrender und kontinuierlicher E-Mail-Kampagnen
description: Erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und wie sich die beiden Ansätze unterscheiden.
feature: Workflows, Campaigns
kt: 1560
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 13f7ab2dd41216a603a22f181dc4d06302c5918a
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 100%

---

# Konfigurieren wiederkehrender und kontinuierlicher E-Mail-Kampagnen

In diesem Tutorial erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und wie sich die beiden Ansätze unterscheiden.

## Tracking des wiederkehrenden und des fortlaufenden Versands {#recurring-and-continuous-delivery-tracking}

Der wiederkehrende und der fortlaufende Versand unterscheiden sich bezüglich der Verwaltung von Kontaktdaten:

* Beim **fortlaufenden Versand** können Sie einem bestehenden Versand neue Empfänger hinzufügen, sodass Sie nicht jedes Mal einen neuen Versand erstellen müssen, wenn ein neuer Empfänger hinzugefügt wird. Sie können die kreativen Inhalte direkt im Kampagnen-Workflow aktualisieren, wodurch die Vorlage im Ressourcen-Ordner für Versandvorlagen aktualisiert wird.

   Bei einem fortlaufenden Versand wird EIN Versand erstellt. Versandlogs (Broadlog) und Trackinglogs, die auf diesen Versand verweisen, werden bei jeder Ausführung hinzugefügt.

   ![Versand (fortlaufend)](/help/assets/delivery_continuous.jpg)

* Ein **wiederkehrender Versand** erstellt bei jeder Ausführung eine neue Versandinstanz. Wenn der Workflow beispielsweise einmal pro Woche ausgeführt werden soll, führt dies nach einem Jahr zu 52 Sendungen. Dies bedeutet auch, dass das Broadlog und die Trackinglogs je Versandinstanz getrennt sind.

   ![Wiederkehrender Versand](/help/assets/delivery_recurring.jpg)

## Einrichten eines wiederkehrenden Versands {#how-to-set-up-a-recurring-delivery}

In diesem Video wird das Konfigurieren eines wiederkehrenden Versands und einer Planungsaktivität erläutert.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12&learn=on)

## Einrichten eines fortlaufenden Versands {#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie Sie einen fortlaufenden Versand mit einer inkrementellen Abfrage konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12&learn=on)
