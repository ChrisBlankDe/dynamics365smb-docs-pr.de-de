---
title: 'Designdetails: Kostenkomponenten | Microsoft Docs'
description: Kostenkomponenten sind unterschiedliche Arten von Kosten, die den Wert eines Lagerzugangs erhöhen oder vermindern.
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: ''
ms.date: 10/01/2019
ms.author: sgroespe
ms.openlocfilehash: bc8af7c62702aa701251459a9b373200c61d2035
ms.sourcegitcommit: cfc92eefa8b06fb426482f54e393f0e6e222f712
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/03/2019
ms.locfileid: "2880550"
---
# <a name="design-details-cost-components"></a>Designdetails: Kostenkomponenten
Kostenkomponenten sind unterschiedliche Arten von Kosten, die den Wert eines Lagerzugangs erhöhen oder vermindern.  

 Die folgende Tabelle zeigt die verschiedenen Kostenkomponenten und alle untergeordneten Kostenkomponenten an, aus denen sie bestehen.  

|Kostenkomponenten|Unterstellte Kostenkomponente|Description|  
|--------------------|--------------------------------|---------------------------------------|  
|Direkte Kosten|Einstandspreis (Preis des direkten Kaufs)|Kosten, die direkt auf das Kostenobjekt zurückzuführen sind.|  
|Direkte Kosten|Fracht Kosten (Artikelgebühren)|Kosten, die direkt auf das Kostenobjekt zurückzuführen sind.|  
|Direkte Kosten|Versicherungskosten (Artikelgebühren)|Kosten, die direkt auf das Kostenobjekt zurückzuführen sind.|  
|Indirekte Kosten||Kosten, die nicht auf ein Kostenobjekt zurückzuführen sind.|  
|Abweichung|Einkaufsabweichung|Der Unterschied zwischen tatsächlichen Kosten und dem Einstandspreis (fest), der nur für Artikel mit der Lagerabgangsmethode **Standard** gebucht wird.|  
|Abweichung|Materialabweichung|Der Unterschied zwischen tatsächlichen Kosten und dem Einstandspreis (fest), der nur für Artikel mit der Lagerabgangsmethode **Standard** gebucht wird.|  
|Abweichung|Kapazitätsabweichung|Der Unterschied zwischen tatsächlichen Kosten und dem Einstandspreis (fest), der nur für Artikel mit der Lagerabgangsmethode **Standard** gebucht wird.|  
|Abweichung|Fremdarbeitskostenabweichung|Der Unterschied zwischen tatsächlichen Kosten und dem Einstandspreis (fest), der nur für Artikel mit der Lagerabgangsmethode **Standard** gebucht wird.|  
|Abweichung|Abweichung Kapazitätsgemeinkosten|Der Unterschied zwischen tatsächlichen Kosten und dem Einstandspreis (fest), der nur für Artikel mit der Lagerabgangsmethode **Standard** gebucht wird.|  
|Abweichung|Prod.-Gemeinkostenabw.|Der Unterschied zwischen tatsächlichen Kosten und dem Einstandspreis (fest), der nur für Artikel mit der Lagerabgangsmethode **Standard** gebucht wird.|  
|Neubewertung||Eine Auf- oder Abwertung des aktuellen Lagerwerts.|  
|Rundung||Restbeträge, die durch die Berechnung von Bestandsminderungen entstehen.|  

> [!NOTE]  
>  Fracht- und Versicherungskosten sind Artikel-Gebühren, die jederzeit zu den Kosten des Artikels addiert werden können. Wenn Sie die Stapelverarbeitung **Artikeleintrag Kosten anpassen** ausführen, wird der Wert aller zugehörigen Lagerabgänge entsprechend aktualisiert.  

## <a name="see-also"></a>Siehe auch  
 [Designdetails: Lagerkostenberechnung](design-details-inventory-costing.md)   
 [Designdetails: Abweichungen](design-details-variance.md) [Verwalten der Lagerkosten](finance-manage-inventory-costs.md)  
 [Finanzen](finance.md)  
 [Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
