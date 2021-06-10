---
title: Einrichten wiederkehrender und kontinuierlicher E-Mail-Kampagnen
description: Erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und die Unterschiede zwischen den beiden Ansätzen verstehen.
feature: Workflows
kt: 1560
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
exl-id: 42f2a7e6-7d88-473b-b913-fe09b7016b28
source-git-commit: 5fb898eca821c5078393003c41032801f8454fd5
workflow-type: tm+mt
source-wordcount: '268'
ht-degree: 67%

---

# Einrichten wiederkehrender und kontinuierlicher E-Mail-Kampagnen

In diesem Tutorial erfahren Sie, wie Sie einen wiederkehrenden und einen fortlaufenden Versand einrichten und die Unterschiede zwischen den beiden Ansätzen erläutern.

## Tracking des wiederkehrenden und kontinuierlichen Versands {#recurring-and-continuous-delivery-tracking}

Der wiederkehrende und kontinuierliche Versand unterscheidet sich bei der Verwaltung der Kontaktdaten:

* Beim **fortlaufenden Versand** können Sie einem bestehenden Versand neue Empfänger hinzufügen, sodass Sie nicht jedes Mal einen neuen Versand erstellen müssen, wenn ein neuer Empfänger hinzugefügt wird. Sie können die kreativen Inhalte direkt im Kampagnen-Workflow aktualisieren, wodurch die Vorlage im Ressourcen-Ordner für Versandvorlagen aktualisiert wird.

   Bei einem fortlaufenden Versand wird EIN Versand erstellt. Versandlogs (Broadlog) und Trackinglogs, die auf diesen Versand verweisen, werden bei jeder Ausführung hinzugefügt.

   ![Versand (fortlaufend)](/help/assets/delivery_continuous.jpg)

* Ein **wiederkehrender Versand** erstellt bei jeder Ausführung eine neue Versandinstanz. Wenn der Workflow beispielsweise einmal pro Woche ausgeführt werden soll, führt dies nach einem Jahr zu 52 Sendungen. Dies bedeutet auch, dass das Broadlog und die Trackinglogs je Versandinstanz getrennt sind.

   ![Wiederkehrender Versand](/help/assets/delivery_recurring.jpg)

## Einrichten eines wiederkehrenden Versands {#how-to-set-up-a-recurring-delivery}

In diesem Video wird das Konfigurieren eines wiederkehrenden Versands und einer Planungsaktivität erläutert.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Einrichten eines Versands (fortlaufend){#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie man einen fortlaufenden Versand mit einer inkrementellen Abfrage konfiguriert.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Zusätzliche Ressourcen

[Erstellen eines wiederkehrenden Versands in einem Zielgruppen-Workflow](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/use-cases/deliveries/sending-a-birthday-email.html?lang=en#creating-a-recurring-delivery-in-a-targeting-workflow)
