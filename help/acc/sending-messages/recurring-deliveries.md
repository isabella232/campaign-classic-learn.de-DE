---
title: Einrichten laufender und kontinuierlicher E-Mail-Kampagnen
description: In diesem Lernprogramm wird erläutert, wie ein wiederkehrender und kontinuierlicher Versand und die Unterschiede zwischen den beiden Ansätzen in Adobe Campaign Classic (ACC) eingerichtet werden.
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: d1799d978a9a29f69d637178439fe770ffd4b281
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 4%

---


# Einrichten laufender und kontinuierlicher E-Mail-Kampagnen

In diesem Lernprogramm wird erläutert, wie ein wiederkehrender und kontinuierlicher Versand und die Unterschiede zwischen den beiden Ansätzen eingerichtet werden.

## Verfolgung wiederkehrender und fortlaufender Versand {#recurring-and-continuous-delivery-tracking}

Die wiederkehrenden und kontinuierlichen Versände unterscheiden sich bei der Verwaltung der Kontaktdaten:

* The **continuous delivery** lets you add new recipients to an existing delivery and avoids you having to create a new delivery each time a new recipient is added. Sie können die Kreativelemente direkt im Arbeitsablauf für Kampagnen aktualisieren und die Vorlage im Ordner &quot;Versandvorlage-Ressourcen&quot;aktualisieren.

   Ein kontinuierlicher Versand erstellt einen SINGLE-Versand und Versandlogs (wideLog) und Trackinglogs, die auf diesen einen Versand verweisen, werden bei jeder Ausführung hinzugefügt.

![Kontinuierlicher Versand](/help/acc/assets/delivery_continuous.jpg)

* Ein **wiederkehrender Versand** erstellt bei jeder Ausführung eine neue Versand-Instanz. Wenn der Workflow beispielsweise einmal pro Woche ausgeführt werden soll, ergibt dies 52 Versand nach einem Jahr. Dies bedeutet auch, dass das breite Protokoll und die Trackinglogs durch jede Versand-Instanz getrennt werden.

![Wiederkehrender Versand](/help/acc/assets/delivery_recurring.jpg)

## So richten Sie einen wiederkehrenden Versand ein {#how-to-set-up-a-recurring-delivery}

In diesem Video wird beschrieben, wie Sie einen wiederkehrenden Versand und eine Planung-Aktivität konfigurieren.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Einrichten eines kontinuierlichen Versands {#how-to-set-up-a-continuous-delivery}

In diesem Video wird gezeigt, wie ein kontinuierlicher Versand mit inkrementeller Abfrage konfiguriert wird.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## Zusätzliche Ressourcen

[Erstellen eines wiederkehrenden Versands in einem Zielgruppen-Workflow](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)