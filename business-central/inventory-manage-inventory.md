---
title: Verwaltung von Bestand | Microsoft Docs
description: Beschreibt, wie physischen Produkte verwaltet werden, die Sie im Lagerbestand in Ihrem Lager verwalten.
documentationcenter: ''
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: warehouse, stock
ms.date: 01/13/2020
ms.author: sgroespe
ms.openlocfilehash: 79a640a01dbd0c1ca82b5190e690a4ff71a136a0
ms.sourcegitcommit: ead69ebe5b29927876a4fb23afb6c066f8854591
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/14/2020
ms.locfileid: "2952698"
---
# <a name="inventory"></a>Lagerbestand
Für jedes physische Produkt, mit dem Sie handeln, müssen Sie eine Artikelkarte vom Typ **Lagerbestand** erstellen. Artikel, die Sie Debitoren anbieten, aber nicht im Lager führen, können als Katalogartikel erfassen werden und Sie können Sie bei Bedarf in Lagerartikel konvertieren. Sie können die Menge eines Artikels im Lager erhöhen oder vermindern, indem Sie direkt in den Artikelposten buchen, beispielsweise nach einer physischen Zählung oder falls keine erworbenen Mengen erfasst wurden.

Lagerzugänge und Abgänge werden natürlich auch erfasst, wenn Sie Einkaufs- und Verkaufsbelege buchen. Weitere Informationen finden Sie unter [Erfassen eines Einkaufs](purchasing-how-record-purchases.md), [Produkte verkaufen](sales-how-sell-products.md) und [Fakturieren eines Verkaufs](sales-how-invoice-sales.md). Umlagerungen zwischen Lagerorten ändert Lagerbestandsmengen in den Lagern Ihres Mandanten.   

Um die Übersicht über Artikel zu erhöhen und die Suche zu erleichtern, können Sie Artikel kategorisieren und ihnen Attribute zuweisen, nach denen sie gesucht und sortiert werden können.

> [!NOTE]
> Die physische Bewegung der Artikel wird als Lageraktivitäten bezeichnet. Weitere Informationen finden Sie unter [Lagerortverwaltung](warehouse-manage-warehouse.md).

Die Planung von Artikeln zur Deckung des Bedarfs wird im Rahmen der Angebotsplanung abgedeckt. Weitere Informationen finden Sie unter [Planung](production-planning.md).  

## <a name="inventory-reconciliation"></a>Abstimmung des Lagerbestands
Wenn Sie Lagertransaktionen buchen, z. B. Verkaufslieferungen, Einkaufsrechnungen oder Lagerregulierungen, werden die veränderten Artikelkosten in den Artikelwerteinträgen aufgezeichnet. Um diese Änderung des Lagerwerts in Ihren Finanzbüchern wiederzugeben, werden die Lagerkosten automatisch zu den entsprechenden Lagerkonten in der Finanzbuchhaltung gebucht. Für jede Lagertransaktion, die Sie buchen, werden die entsprechenden Werte in der Hauptbuchhaltung im Lagerkonto, im Korrekturkonto und im Lagerverbrauchskonto gebucht. Weitere Informationen finden Sie unter [Lagerregulierung mit Finanzbuchhaltung abstimmen](finance-how-to-post-inventory-costs-to-the-general-ledger.md).

Selbst wenn Lagerkosten automatisch in die Finanzbuchhaltung gebucht werden, ist es immer noch notwendig sicherzustellen, dass die Kosten für Waren zur zugehörigen ausgehenden Transaktion weitergeleitet werden, insbesondere in Situationen, in denen Sie Waren verkaufen, bevor Sie den Kauf dieser Waren in Rechnung stellen. Dies wird als Kostenanpassung bezeichnet. Artikelkosten werden automatisch angepasst, wenn Sie Artikeltransaktionen buchen, Sie können jedoch auch Artikelpreise manuell anpassen. Weitere Informationen finden Sie unter [Artikelkosten anpassen](inventory-how-adjust-item-costs.md).

|An |Siehe |
|---|----|
|Erstellen Sie Artikelkarten für Lagerartikel, mit denen Sie handeln.|[Neue Artikel registrieren](inventory-how-register-new-items.md)|
|Strukturieren Sie übergeordnete Artikel, die Sie als Sets verkaufen, die aus den Komponenten des übergeordneten Artikels bestehen oder für die Sie die Auftragsmontage oder das Lager haben.|[Mit Fertigungsstücklisten arbeiten](inventory-how-work-BOMs.md)|
|Aktualisert eine Übersicht über Artikel und erleichtert das Suchen und das Sortieren von Artikeln, indem diese in Kategorien organisiert werden.|[Artikel kategorisieren](inventory-how-categorize-items.md)|
|Weisen Sie Ihren Artikeln Artikelattribute verschiedener Werttypen zu, um das Sortieren und Finden von Artikel zu erleichtern.|[Arbeiten mit Artikelattributen](inventory-how-work-item-attributes.md)|
|Erstellen Sie spezielle Artikelkarten, die Sie Debitoren anbieten, für die Sie aber keinen Bestand verwalten.|[Arbeiten mit Katalogartikeln](inventory-how-work-nonstock-items.md)|
|Führen Sie mit den Seiten **Inventurauftrag** und **Inventurerfassung** eine physische Erfassung des Lagerbestands durch.|[Erfassung des Lagerbestand mithilfe von Belegen](inventory-how-count-inventory-with-documents.md)|
|Beschreibt, wie eine physische Zählung ausgeführt wird, negative oder Zugängen gemacht werden und wie Informationen wie Lagerort oder Chargennummer in Artikelposten und Lagerplatzposten geändert werden.|[Erfassen, Regulieren und Umbuchen von Lagerbestand mithilfe von Buch.-Blättern](inventory-how-count-adjust-reclassify.md)|
|Zeigt die Verfügbarkeit der Artikel pro Lagerort, nach Periode, nach Verkaufs- oder Einkaufsereignis oder anhand ihrer Verwendung auf Produktionsstücklisten an.|[Artikelverfügbarkeit anzeigen](inventory-how-availability-overview.md)|
|Lagern Sie Artikel zwischen Lagerorten mit Umlagerungsaufträgen oder Artikel Umlag. Buch.-Blatt, um Lageraktivitäten zu verwalten.|[Lagerbestand zwischen Lagerplätzen umlagern](inventory-how-transfer-between-locations.md)|
|Reservieren Sie Lager oder eingehenden Artikel für Verkaufsaufträge, Bestellungen, Serviceaufträge, Montageaufträge oder Fertigungsaufträge.|[Artikel reservieren](inventory-how-to-reserve-items.md)|
|Richten Sie eine eigene Beschreibung des Kreditors oder Debitors für einen Artikel ein, sodass Sie die Artikelbeschreibung in Geschäftsbelegen einfach einfügen können.|[Artikelreferenzen verwenden](inventory-how-use-item-cross-refs.md)|
|Serien- oder Chargennummern zu den einzelnen ausgehenden oder eingehende Belege oder Buch.-Blattzeile, beispielsweise um Artikel im Fall von Rückrufen nachzuverfolgen.|[Arbeiten mit Chargennummern und Seriennummern](inventory-how-work-item-tracking.md)|
|Richten Sie eine eigene Beschreibung des Kreditors oder Debitors für einen Artikel ein, sodass Sie die Artikelbeschreibung in Geschäftsbelegen schnell einfügen können.|[Artikelreferenzen verwenden](inventory-how-use-item-cross-refs.md)|
|Suchen Sie, wo eine Serien- oder Chargennummer in der gesamten Lieferkette verwendet wurde, z. B. in Rückrufsituationen.|[Verfolgen von Artikeln mit Artikelverfolgung](inventory-how-to-trace-item-tracked-items.md)|
|Artikel sperren, damit Sie nicht auf Verkaufs- oder Einkaufszeilen eingetragen oder in einer Transaktion gebucht werden können.|[Artikel sperren](inventory-how-block-items.md)|
|Verwalten von Geschäften in den Verkaufsbüros, in den Einkaufsabteilungen oder in den Fabrikplanungsbüros von mehreren Standorten.|[Arbeiten mit Zuständigkeitseinheiten](inventory-responsibility-centers.md)|



## <a name="see-also"></a>Siehe auch  
[Logistik](warehouse-manage-warehouse.md)  
[Einkauf](purchasing-manage-purchasing.md)  
[Verkauf](sales-manage-sales.md)    
[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Allgemeine Geschäftsfunktionen](ui-across-business-areas.md)

## [!INCLUDE[d365fin](includes/free_trial_md.md)]  
