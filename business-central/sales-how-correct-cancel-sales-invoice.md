---
title: Ändern oder Löschen einer gebuchten Verkaufsrechnung| Microsoft Docs
description: Beschreibt, wie eine gebuchte Verkaufsrechnung korrigiert, rückgängig gemacht oder eine Gutschrift angewendet wird.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 01/25/2020
ms.author: sgroespe
ms.openlocfilehash: 95653acf28c553d8331e2c086b7e84f1518bc3c0
ms.sourcegitcommit: 877af26e3e4522ee234fbba606615e105ef3e90a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/28/2020
ms.locfileid: "2992048"
---
# <a name="correct-or-cancel-unpaid-sales-invoices"></a>Ändern oder Löschen einer unbezahlten Verkaufsrechnung
Sie können eine bezahlte Verkaufsrechnung korrigieren oder abbrechen. Dies ist nützlich, wenn Ihnen ein Fehler unterläuft, oder wenn der Debitor eine Änderung anfordert.

> [!NOTE]  
>   Nachdem eine gebuchte Verkaufsrechnung teilweise oder vollständig gezahlt wurde, können Sie die Nummer aus der gebuchten Verkaufsrechnung selbst nicht korrigieren oder stornieren. Stattdessen müssen Sie eine Verkaufsgutschrift manuell erstellen, um den Verkauf zu stornieren und den Debitor zurückzuerstatten. Weitere Informationen finden Sie unter [Retouren verarbeiten oder Stornieren](sales-how-process-sales-returns-cancellations.md).

Auf der Seite **Geb. Verkaufsrechnung** können Sie auf die Schaltfläche **Korrigieren** oder auf die Schaltfläche **Abbrechen** klicken, um die Aktionen auszuführen, die in der folgenden Tabelle beschrieben werden.

| Aktion | Beschreibung |
| --- | --- |
| **Korrigiereh** |Die gebuchte Verkaufsrechnung ist storniert. Eine neue Verkaufsrechnung mit den gleichen Informationen wird erstellt. Sie können die Korrektur machen, bevor Sie den Verkaufsprozess fortsetzen. Die neue Verkaufsrechnung hat eine andere Nummer als die erste Verkaufsrechnung. Eine Korrekturverkaufsgutschrift wird automatisch erstellt und gebucht, um die ursprüngliche gebuchte Verkaufsrechnung zu stornieren. In der ursprünglich gebuchten Verkaufsrechnung werden die Kontrollkästchen "Storniert" und "Bezahlt" aktiviert. |
| **Abbrechen** |Die gebuchte Verkaufsrechnung ist storniert. Eine Korrekturverkaufsgutschrift wird automatisch erstellt und gebucht, um die ursprüngliche gebuchte Verkaufsrechnung zu stornieren. In der ursprünglich gebuchten Verkaufsrechnung werden die Kontrollkästchen "Storniert" und "Bezahlt" aktiviert. |

Wenn Sie eine gebuchte Verkaufsrechnung korrigieren oder stornieren, wird sie in allen Sach- und Inventurposten angewendet, die erstellt wurden, als die erste Verkaufsrechnung gebucht wurde. Dadurch wird die gebuchte Verkaufsrechnung in Ihren Finanzdatensätzen storniert und verlässt die gebuchte Korrekturverkaufsgutschrift für Ihr Protokoll.

## <a name="to-correct-a-posted-sales-invoice"></a>Gebuchte Verkaufsrechnung korrigieren
1. Wählen Sie das Symbol ![Glühbirne, das die Funktion „Sie wünschen“ öffnet](media/ui-search/search_small.png "Was möchten Sie tun?") aus, geben Sie **Gebuchte Verkaufsrechnungen** ein, und wählen Sie dann den entsprechenden Link.  
2. Wählen Sie die gebuchte Verkaufsrechnung, die Sie korrigieren möchten.

    > [!NOTE]  
    >   Wenn Sie das Kontrollkästchen **Storniert** auswählen, dann können Sie die gebuchte Einkaufsrechnung nicht korrigieren, da sie bereits korrigiert wurde oder storniert wurde.
3. Auf der Seite **Gebuchte Verkaufsrechnung** wählen Sie **Korrekt** aus.  
4. Eine neue Verkaufsrechnung mit den gleichen Informationen wird erstellt, auf dem Sie die Korrektur machen können. Das Feld **Storniert** am Anfang gebuchten Verkaufsrechnung wird auf **Ja** geändert.

    Eine Verkaufsgutschrift wird automatisch erstellt und gebucht, um die ursprüngliche gebuchte Verkaufsrechnung zu stornieren.
5. Wählen Sie die Registerkarte **Korrekturgutschrift anzeigen** aus, um die gebuchte Verkaufsgutschrift anzuzeigen, die die gebuchte Verkaufsrechnung storniert.

## <a name="to-cancel-a-posted-sales-invoice"></a>Gebuchte Verkaufsrechnung stornieren
1. Wählen Sie das Symbol ![Glühbirne, das die Funktion „Sie wünschen“ öffnet](media/ui-search/search_small.png "Was möchten Sie tun?") aus, geben Sie **Gebuchte Verkaufsrechnungen** ein, und wählen Sie dann den entsprechenden Link.  
2. Wählen Sie die gebuchte Verkaufsrechnung, die Sie stornieren möchten.

    > [!NOTE]  
    >   Wenn Sie das Kontrollkästchen **Storniert** auswählen, dann können Sie die gebuchte Einkaufsrechnung nicht korrigieren, da sie bereits korrigiert wurde oder storniert wurde.
3. Auf der Seite **Gebuchte Verkaufsrechnung** wählen Sie **Abbrechen** aus.

    Eine Verkaufsgutschrift wird automatisch erstellt und gebucht, um die ursprüngliche gebuchte Verkaufsrechnung zu stornieren. Das Feld **Storniert** am Anfang gebuchten Verkaufsrechnung wird auf **Ja** geändert.
4. Wählen Sie die Registerkarte **Korrekturgutschrift anzeigen** aus, um die gebuchte Verkaufsgutschrift anzuzeigen, die die gebuchte Verkaufsrechnung storniert.

### <a name="partial-invoice-posting-also-supported"></a>Rechnungsteilbuchung wird ebenfalls unterstützt
Wenn sich die Stornierung auf eine Rechnungsteilbuchung bezieht, wird die ursprüngliche Verkaufsauftragszeile aktualisiert, um die stornierte fakturierte Menge widerzuspiegeln. Die Felder **Zu fakturierende Menge** und **Fakturierte Menge** zur zugehörigen Verkaufsauftragszeile werden auf die Werte vor der Teilbuchung zurückgesetzt.

## <a name="see-also"></a>Siehe auch
[Verkauf](sales-manage-sales.md)  
[Einrichten von Verkäufen](sales-setup-sales.md)  
[Senden von Belegen über E-Mail](ui-how-send-documents-email.md)  
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
